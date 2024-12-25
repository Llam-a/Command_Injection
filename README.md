# Command_Injection

Command Injection hay còn là OS command injection.

*OS command là những mệnh lệnh instruction tương tác trực tiếp với hệ điều hành để nói cho nó biết rằng cần phải thực thi những gì.*

Website để tìm hiểu thêm về OS Command: https://explainshell.com/ 

OS command injection còn được biết theo cách khác là Shell Injection. Nó cho phép hacker thực thi các OS command ở server đang chạy những cái ứng dụng(web,app,game,vv). 

Ngoài OS Command Injection, còn hàng chục lỗi Injection khác bao gồm:SQL Injection, HTML Injcection, LDAP Injection, Xpath Injection,Code Injection, v.v.2.

## Cấu trúc Application

![image](https://github.com/user-attachments/assets/bf5b5d8c-12c2-4978-abc5-6424136d528e)


- Application được cấu tạo từ nhiều lớp khác nhau
- Trong đó, OS Command ra lệnh trực tiếp cho hệ điều hành
