# The Basic of Nest

# การทำงานของ Server ปกติ

![](attachments/d46a25cb-8b6b-47a4-90d9-be8ef6ec15dd.png ' =1328x464')

# NestJS จะมีตัวช่วยพิเศษคือ

![](attachments/cc133841-b617-40b8-9b6e-110bf10afffc.png ' =1119x573')

## Pipe

- ช่วย Validate ข้อมูลที่เข้ามาจาก Request

## Guard

- จะช่วยเรื่อง Request ที่เข้ามาจาก User ที่ได้ทำการ Authenticate หรือ Authorized เพื่อเข้าใช้ Application

## Controller

- เหมือนเป็น Routing logic

## Service

- จัดการเกี่ยวกับ Business Logic

## Repository

- จัดการเกี่ยวกับ Database ตรงตัวเลย Access a database

## And these is other tools of NestJS

![](attachments/04db2bc2-fee3-4a90-9057-c1a02f01e38b.png ' =1171x752')

## Controller and Module are required to make the most simple, basic app

# Basic main.ts Files

![](attachments/614acc85-05eb-4679-9d25-2acee97223a2.png ' =1235x646')

## เราจะแยก AppController และ AppModule ออกจาก main.ts ดังนี้

![](attachments/2156f4cc-ccfe-4d04-8c31-dff57016f900.png ' =1193x652')

## โดยจะมีชื่อ Specific ตามภาพด้านบน

### ปกติเราจะตั้งชื่อตาม ชื่อส่วนหน้าของ Controller หรือ Module เช่น

- class AppController {} เราจะตั้งชื่อไฟล์ว่า app.controller.ts

### Filename template: name.type_of_thing.ts
