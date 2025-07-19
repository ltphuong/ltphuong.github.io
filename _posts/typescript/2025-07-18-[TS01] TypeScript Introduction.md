---
layout: post
title: "TS01 - TypeScript là gì? Tại sao nên học?"
categories: typescript
permalink: /lap-trinh-typescript/ts01-typescript-la-gi/
image: assets/images/typescript/1.What-is-TypeScript.png
---

## 🎯 Mục tiêu bài học

Giúp bạn hiểu:

* TypeScript là gì?
* Vì sao tester nên học TypeScript?
* TypeScript giúp ích gì khi viết test automation với Playwright?

---

## 🟡 TypeScript là gì?

- Hiểu đơn giản, TypeScript là phiên bản "nâng cấp" của JavaScript – nó giúp bạn **code rõ ràng hơn, ít lỗi vặt hơn** nhờ có kiểm tra kiểu dữ liệu.

- TypeScript do Microsoft phát triển, và hiện đang được dùng rất nhiều trong các dự án automation test, đặc biệt là với Playwright.

### 🔍 Nói cách dễ hiểu:

TypeScript = JavaScript + kiểm tra kiểu dữ liệu (types)

Ví dụ:

```ts
let age: number = 30;     // đúng kiểu
let name: string = true;  // ❌ TypeScript sẽ la lên vì kiểu sai
```

Khi bạn dùng JavaScript thì nó vẫn chạy bình thương, sai cũng không biết. Nhưng TypeScript thì sẽ "bắt lỗi sớm", tránh bug vặt về sau.

---

## 💡 Vì sao tester nên học TypeScript?

| Lý do                | Giải thích dễ hiểu                                      |
| -------------------- | ------------------------------------------------------- |
| ✅ Hợp với Playwright | Playwright "thân thiết" với TypeScript nhất        |
| ✅ Gợi ý thông minh   | Bạn gõ đến đâu, VS Code gợi ý tới đó, đỡ phải nhớ nhiều |
| ✅ Báo lỗi sớm        | Viết sai tên hàm, sai kiểu biến – biết liền!            |
| ✅ Code sạch, dễ đọc  | Nhìn vào là hiểu liền, teamwork cũng dễ hơn             |

👉 Bạn không cần làm developer mới học được, chỉ cần biết phần nào phục vụ cho việc viết automation test là đủ dùng.

---

## 💻 Ví dụ

```ts
let name: string = "Jackey";
let age: number = 38;

console.log(`Tên tôi là ${name}, năm nay ${age} tuổi.`);
```

Nếu viết sai kiểu:

```ts
let age: number = "ba mươi tám"; // ❌ TypeScript sẽ cảnh báo
```

---

## ✅ Tóm lại:

* TypeScript = JavaScript + "kiểu dữ liệu rõ ràng"
* Tester nên học vì nó phù hợp với Playwright và giúp code sạch, ít lỗi hơn
* Không cần học nâng cao – chỉ cần đủ dùng để viết test là ổn rồi

👉 Hẹn gặp bạn ở bài tiếp theo: **\[TS02] Hướng dẫn cài đặt môi trường TypeScript**!
