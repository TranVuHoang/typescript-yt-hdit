# Chapter 1: Getting started

```
#0. Setup Environment
VSCode - Công cụ để code Javascript/Typescript:
  - Tải VSCode: https://code.visualstudio.com/download
  - Sử dụng VSCode vì nó free, và support mạnh mẽ cho javascript/typescript

Node.js - Môi trường thực thi Javascript/Typescript
  - Download Node.js: https://nodejs.org/en/download/
  - Node.js là môi trường để chạy code, chứ không phải là framework hay library.
  Nó là platform. Tương tự như windows là môi trường để chạy ứng dụng
  Microsoft Words (ở đây, node.js là môi trường để chạy ứng dụng React - viết bằng ngôn ngữ javascript)

Full source code của cả khóa học:
  - Download project với Github: https://github.com/haryphamdev/hoidanit-typescript-basic

  - Các bước cần thực hiện để cài đặt project thực hành:
    B1: Đảm bảo rằng máy tính các bạn đã cài đặt Git

    B2: Download project từ link ở trên với Git clone

    B3: Chạy project theo từng video hướng dẫn trong khóa học (sẽ đề cập trong quá trình học)
```

```
# DEMO KẾT QUẢ ĐẠT ĐƯỢC

1. Mục tiêu của khoá học
Xây dựng niềm đam mê lập trình với ngôn ngữ JavaScript/TypeScript từ số 0 dành cho
người mới bắt đầu.

Bạn sẽ học được gì?
- Kiến thức căn bản về lập trình: biến, kiểu dữ liệu, hàm, vòng lặp, điều kiện, object,
array,...

- Hiểu và thao tác với DOM, xử lý sự kiện, tương tác với giao diện HTML.

- Cách làm việc với bất đồng bộ: callback, Promise, async/await.

- Làm quen và nắm vững Typescript: kiểu dữ liệu tĩnh, interface, class, function,
typing,...

- Xây dựng dự án thực hành giúp bạn áp dụng ngay kiến thức đã học.

2. Demo dự án
// todo

3. Khoá học phù hợp với ai?

 - Người mới học lập trình từ số 0, muốn xây dưng đam mê lập trình

 - Sinh viên, nguời trái ngành chuyển sang IT, học với ngôn ngữ Javascript/ Typescript

 - Dev Javascript muốn nâng cấp lên Typescript một các bài bản.

# TỔNG QUAN VỀ KIẾN THỨC SẼ HỌC
Khóa học bao gồm 16 chapters, chia thành 2 mảng kiến thức chính:

Từ chapter 1 tới hết chapter 8: Học & thực hành ngôn ngữ JavaScript từ số 0.
Mục tiêu của phần kiến thức này, giúp bạn nắm vững kiến thức cơ bản & cốt lõi nhất của
JavaScript, cũng như hiểu rõ “nhược điểm” của JavaScript (khi cần scale, maintain...)

Từ chapter 9 tới hết chapter 16: Học & thực hành ngôn ngữ Typescript từ số 0.

Nhờ việc nắm vững JavaScript, bạn tiếp cận TypeScript một các dễ dàng hơn (không
cần học lại cú pháp, datatype, function,...) vì:
Typescript = Javascript + Type

Trọng tâm của khoá học là Typescript, tuy nhiên cần học JS để thấy được lịch sử
phát triển của công nghệ, nhược điểm cuả JS và lý do Typescript ra đời.

Ngoài ra, việc nắm vững cả JS/TS sẽ giúp bạn thích nghi tốt nhất với cuộc sống khi đi làm,
cho dù rơi vào dự án JS hay TS, đều có thể tham gia.
```

## 1. Typescript là gì?

```
1.1 GIỚI THIỆU VỀ TYPESCRIPT

TypeScript (viết tắt làTS) là một "phong cách mới" để code Javascript (JS)
Browser chỉ có thể hiểu HTML/CSS và Javascript thuần, KHÔNG HIỂU typescript.
Vậy làm sao để chạy được 1 project typescript?

TS => TS Compiler => JS

- Typescript sử dụng "cú pháp của javascript", và bổ sung thêm các cú pháp mới để
hỗ trợ "type" (các kiểu dữ liệu).
=> Những kiến thức đã biết về JS đều có thể áp dụng trong TS.

- Để viết TS, chúng ta định nghĩa file cuối extension là .ts thay vì .js(javascript).
-> Có thể viết code js bên trong ts và có thể rename .js thành .ts để viết code typescript

1.2 TẠI SAO PHẢI DÙNG TYPESCRIPT

- Ép kiểu dữ liệu chặt chẽ hơn(giảm sự freedom so với javascript).
-> Sử dụng type để định nghĩa dữ liệu, tương tự Java, Csharp,...

- Gíup hạn chế bugs, đặc biệt trong các dự án có khối lượng codebase(dòng code) lớn.

// ví dụ lesson1 với JS và TS

```

## 2. Cài đặt Compiler Typescript

```
- CÀI TYPESCRIPT CHO DỰ ÁN:
  `npm install typescript@4.8.3 ts-node@10.9.1 --save-dev`: cài bản TS version 4.8.3 cho project đang code.

- Kiểm tra phiên bản TS đang có ở project:
  `npx tsc -v`
```

## 3. Typescript "Hello World"
