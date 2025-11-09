# Drag-Drob

---

## ⚙️ How to Run | طريقة التشغيل

1. Download or copy the file **`index.html`**.  
   قم بتحميل أو نسخ ملف **`index.html`**.
2. Open it directly in your web browser (Chrome, Edge, Firefox).  
   افتحه مباشرة في متصفحك.
3. Start adding, editing, or dragging tasks instantly.  
   يمكنك البدء فوراً بإضافة وتعديل المهام وسحبها.

---

## 💡 How to Use | كيفية الاستخدام

### ➕ Add a Task | إضافة مهمة
- Type your task in the input field under the "To Do" column.  
  اكتب نص المهمة في خانة الإدخال أسفل عمود "للتنفيذ".
- Click the **"Add Task"** button.  
  اضغط على زر **"أضف مهمة"**.

### ✏️ Edit a Task | تعديل مهمة
- Double-click the task text to edit it.  
  انقر مرتين على نص المهمة لتعديله.
- Or click the edit (✏️) button.  
  أو استخدم زر ✏️.

### 🗑️ Delete a Task | حذف مهمة
- Click the delete (🗑️) button and confirm.  
  اضغط على زر 🗑️ لتأكيد الحذف.

### 🔄 Move a Task | نقل مهمة
- Drag and drop tasks between columns.  
  اسحب وأفلت المهمة بين الأعمدة الثلاثة.

---

## 🧠 Technical Notes | ملاحظات تقنية

- Drag and drop is handled with `dragstart`, `dragenter`, `drop` events.  
  يعتمد السحب والإفلات على أحداث JavaScript: `dragstart`, `dragenter`, `drop`.
- Each task has a unique ID generated using `Date.now()`.  
  كل مهمة تُنشأ بمعرّف فريد باستخدام `Date.now()`.
- When editing, the task element refreshes to re-render buttons.  
  عند التعديل يتم إعادة بناء العنصر لتحديث الأزرار.
- Data is **not saved** after refresh (no LocalStorage yet).  
  البيانات لا تُحفظ بعد التحديث (لم يتم إضافة LocalStorage بعد).

---

## 🔮 Future Improvements | تحسينات مستقبلية

- 💾 Save tasks to **LocalStorage**.  
  حفظ المهام في **LocalStorage**.
- 🗓️ Add **creation date** and **priority levels**.  
  إضافة تاريخ الإنشاء ومستوى الأهمية.
- 🌙 Add **Dark Mode**.  
  دعم الوضع الداكن.
- 🔍 Add **search and filtering**.  
  إضافة خاصية البحث والتصفية.

---

## 👨‍💻 Author | المؤلف

**Youssef Ettaaj**  
📍 Morocco - المغرب  
💬 Educational project to practice JavaScript and TailwindCSS UI.  
مشروع تعليمي لتعلم واجهات JavaScript و TailwindCSS.

---

## 🪪 License | الترخيص

This project is open source and free to use or modify for personal or educational purposes.  
المشروع مفتوح المصدر ومجاني للاستخدام أو التعديل لأغراض تعليمية أو شخصية.

---

## 🌐 Optional: Deploy on GitHub Pages | نشر المشروع على GitHub Pages (اختياري)

1. Create a GitHub repository.  
   أنشئ مستودع GitHub جديد.
2. Upload `index.html` and `README.md`.  
   ارفع الملفين `index.html` و `README.md`.
3. Go to **Settings → Pages → Branch: main → / (root)**.  
   انتقل إلى الإعدادات → الصفحات → اختر الفرع الرئيسي.
4. Open your live project at  
   🌍 `https://your-username.github.io/your-repo-name/`

---

