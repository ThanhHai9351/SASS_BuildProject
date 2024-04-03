# Hướng dẫn cài đặt và sử dụng Sass - Build by ThanhHai

## Cài đặt Sass

### Trên Windows hoặc macOS:

1. Đầu tiên, bạn cần cài đặt Node.js nếu chưa có. Bạn có thể tải xuống và cài đặt từ trang web chính thức của Node.js: [https://nodejs.org/](https://nodejs.org/)

2. Mở Command Prompt trên Windows hoặc Terminal trên macOS.

3. Sử dụng npm (trình quản lý gói của Node.js) để cài đặt Sass global bằng cách chạy lệnh sau:

```bash
npm install -g sass
```

### Trên Linux (sử dụng Ubuntu làm ví dụ):

1. Mở Terminal.

2. Chạy các lệnh sau để cài đặt Node.js và npm:

```bash
sudo apt update
sudo apt install nodejs npm
```

3. Sau đó, cài đặt Sass bằng npm:

```bash
sudo npm install -g sass
```

## Sử dụng Sass

1. Tạo một tệp Sass với phần mở rộng `.scss`, chẳng hạn `styles.scss`.

2. Viết mã Sass trong tệp này.

3. Sau đó, bạn có thể biên dịch tệp Sass này thành CSS bằng cách sử dụng câu lệnh sau trong Command Prompt (Windows) hoặc Terminal (macOS/Linux):

```bash
sass input.scss output.css
```

Trong đó, `input.scss` là tệp Sass bạn đã viết và `output.css` là tên bạn muốn đặt cho tệp CSS được tạo ra.

Ví dụ, nếu bạn có tệp `styles.scss` chứa mã Sass và bạn muốn biên dịch nó thành `styles.css`, bạn có thể chạy lệnh:

```bash
sass styles.scss styles.css
```

Sass sẽ biên dịch tệp `styles.scss` thành `styles.css` và lưu trong cùng thư mục.

4. Lưu ý rằng bạn cũng có thể sử dụng các tuỳ chọn bổ sung với trình biên dịch Sass để tối ưu hóa quy trình làm việc của mình, như `--watch` để theo dõi sự thay đổi và tự động biên dịch khi có sự thay đổi trong tệp.

# Build project For SASS

1.Step 1

```bash
npm init
```

2.Step 2

```bash
npm install node-sass --save-dev
```

3.Step 3

```bash
npm install browser-sync --save-dev
```

4.Step 4

```bash
npm install onchange --save-dev
```

5.Step 5

```bash
npm install npm-run-all --save-dev
```

6.Configs Script run compiler SASS to CSS
