# High level language
เป็นภาษาที่ถูกสร้างขึ้นเพื่อให้สามารถเขียน และอ่านโปรแกรมได้ง่ายขึ้น โดยจะทำงานได้ก็ต่อเมื่อมีการแปลงเป็นภาษาเครื่องก่อน
# Low level language
เป็นภาษาที่มีความยุ่งยากซึ่งจะการใช้ตัวอักษรภาษาอังกฤษแทนรหัสแทนการทำงาน และใช้ตั้งชื่อตัวแปล ซึ่งจะมีความซับซ้อน จึงไม่นิยมใช้
# Machine language
เป็นภาษาระดับต่ำสุด เพราะใช้เลขฐานสองแทนข้อมูลและคำสั่งต่างๆ เช่น เขียนคำสั่งด้วย 0 หรือ 1

# ตัวอย่างการเปรียบเทียบความสัมพันธ์
1.) ใช้ภาษา C กับอุปกรณ์ RISC-V rv64gc clang 10.0.0
    High level - assembly
    <img width="1440" alt="ภาพถ่ายหน้าจอ 2565-04-03 เวลา 18 13 51" src="https://user-images.githubusercontent.com/98943422/161425973-24fc6441-431e-4aa5-93b9-406da78d2ce9.png">
    High level - Machine
    <img width="1440" alt="ภาพถ่ายหน้าจอ 2565-04-03 เวลา 18 13 57" src="https://user-images.githubusercontent.com/98943422/161425995-c3d3759a-9013-4172-a1f7-88758391ca5f.png">
    
2.) ใช้ภาษา C++ กับอุปกรณ์ RISC-V rv64gc clang 10.0.0
    High level - assembly
    <img width="1440" alt="ภาพถ่ายหน้าจอ 2565-04-03 เวลา 18 14 07" src="https://user-images.githubusercontent.com/98943422/161426176-f55aaf52-2d89-4553-b1d1-23d77fe58d9d.png">
    High level - Machine
    <img width="1440" alt="ภาพถ่ายหน้าจอ 2565-04-03 เวลา 18 14 13" src="https://user-images.githubusercontent.com/98943422/161426198-c6b00f11-8544-4b54-b57c-a06b3be6d4ec.png">

3.)ใช้ภาษา C กับอุปกรณ์ x86-64 icc 17.0.0
    High level - assembly
    <img width="1440" alt="ภาพถ่ายหน้าจอ 2565-04-03 เวลา 18 14 23" src="https://user-images.githubusercontent.com/98943422/161426263-365c79e8-3ae0-4a55-a4c9-1db26bd045df.png">
    High level - Machine
    <img width="1440" alt="ภาพถ่ายหน้าจอ 2565-04-03 เวลา 18 14 27" src="https://user-images.githubusercontent.com/98943422/161426271-9a2abd31-8aa1-4a99-9400-1a2f01ea2a7e.png">

4.) ใช้ภาษา C++ กับอุปกรณ์ x86-64 icc 17.0.0
    High level - assembly
    <img width="1440" alt="ภาพถ่ายหน้าจอ 2565-04-03 เวลา 18 14 36" src="https://user-images.githubusercontent.com/98943422/161426294-3e67b6b8-1165-446b-a419-1a00cf5db362.png">
    High level - Machine
    <img width="1440" alt="ภาพถ่ายหน้าจอ 2565-04-03 เวลา 18 14 41" src="https://user-images.githubusercontent.com/98943422/161426309-feaf886e-2de6-49a1-ad45-8e55af8a1a5c.png">

