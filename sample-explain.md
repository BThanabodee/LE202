# การเขียนโปรแกรมเพื่อรันบนไมโครคอนโทรเลอร์

ในส่วนของการเขียนโปรแกรม จะใช้ภาษา c และ c++

ทั้งนี้ในการทดลองที่ 1 โปรแกรมจะแบ่งออกเป็น 2ส่วน ดังนี้

ส่วนของ void setup()

- void setup () คำสั่งนี้จะแสดงให้รันเพียงครั้งเดียว
- Serial.begin(115200) คำสั่งนี้จะเกี่ยวกับความเร็วที่ใช้

ส่วนของ void loop()

- cnt++; คำสั่งนี้คือตัวแปร count คือจะบวกค่าตั้งแต่ 0 ไปเรื่อยๆ ทีละ 1
- Serial.printf("PATTANT :%d\n",cnt); คำสั่งนี้คือการแสดง count
- Delay(1000); คือการหน่วงเวลา 1 วินาที หรือ 1000 ms


# การเขียนโปรแกรมค้นหา wifi

ในการทดลองที่ 2 จะแบ่งออกเป็น 2 ส่วนดังนี้

ส่วนของ void setup()

- Serial.begin(115200) คำสั่งนี้จะเกี่ยวกับความเร็วที่ใช้
- Wifi.mode(WIFI_STA);
- WiFi.disconnect();      ทั้งหมดนี้จะ setup wifi ให้พร้อมทำงาน
- Delay(100)
- Serial.println("\n\n\n");

ส่วนของ void loop() จะแสกนหา wifi รอบตัว


# การเขียนโปรแกรม output สัญญานดิจิทัล

ส่วนของ void setup()  จะset ให้ port 0 เป็น output

- Serial.begin(115200)
- pinMode(0, OUTPUT);
- Serial.println("\n\n\n");

ส่วนของ void loop();

- digitalWrite(0, HIGH);  คำสั่งนี้ เมื่อ cnt เป็นเลขคู่ จะส่งค่าเป็น high คือ off
- digitalWrite(0, HIGH);  คำสั่งนี้ เมื่อ cnt เป็นเลขคี่ จะส่งค่าเป็น low คือ on
- delay(500);  คำสั่งนี้จะวนลูป ทุกครึ่งวิ


# การเขียนโปรแกรม input สัญญานดิจิทัล

ส่วนของ void setup()  จะกำหนด port ในการแสดง input และ output

- pinMode(0, INPUT);   
- pinMode(2, OUTPUT);

ส่วนของ void loop()

- int val = digitalRead(0);  คือการอ่านข้อมูลจาก port 0 รับค่าเข้ามาเป็น 0,1
- digitalWrite(2, LOW);  แสดงถ้าเป็น 1 ไฟLEDดับ
- digitalWrite(2, HIGH);  แสดงถ้าเป็น 0 ไฟLEDติด


# การเขียนโปรแกรมเชื่อมต่อไวไฟและเซอร์เวอร์

ส่วนของ void setup()  คือการ connect wifi

- Wifi.mode(WIFI_STA);
- Wifi.begin(ssid. password);
- while (WiFi.status() != WL_CONNECTED)


# การเขียนโปรแกรมสร้างไวไฟแอดเซสพอยต์

- const char* ssid = "MY-ESP8266";  สร้างช่ื่อ wifi
- const char* password = "choompol";  สร้างรหัสผ่าน
