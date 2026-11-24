# MADAR OSS | مَدار

[العربية](#العربية) · [English](#english)

## العربية

**مَدار** مساحة عمل للوكالات الإبداعية من **formmint**، تجمع إدارة العملاء والمشاريع والمهام والتسليمات والفواتير في مكان واحد. يدعم تصميم المنصة العربية باتجاه RTL والإنجليزية باتجاه LTR.

### كيف يشتغل مَدار؟

ينشئ فريق الوكالة مشروعًا للعميل ويوزّع مهامه، ثم يرفع نسخة من التصميم أو الفيديو للمراجعة الداخلية. بعد مشاركة النسخة في بوابة العميل، يقدر العميل يعتمدها أو يطلب تعديلًا. يحتفظ المشروع بسجل النسخ والقرارات، ويتابع الفريق الفواتير والدفعات من نفس مساحة العمل.

### نطاق النسخة الأولى

- إدارة العملاء والمشاريع والمهام ومواعيد التسليم.
- بوابة للعميل تعرض العناصر التي يشاركها الفريق معه.
- تسليمات بإصدارات متعددة مع سجل الاعتماد وطلبات التعديل.
- إرفاق الفواتير وتسجيل الدفعات ومتابعة الرصيد المتبقي.
- واجهة عربية وإنجليزية للوكالة والعميل.

### جرّب النسخة الحالية

نزّل المستودع من **Code → Download ZIP**، فك الضغط وافتح `index.html` في المتصفح. يمكنك أيضًا تشغيله من مجلد المشروع بالأمر `python3 -m http.server 8000` ثم فتح <http://localhost:8000>.

تدعم النسخة التجريبية إدارة العملاء والمشاريع والمهام وتبديل اللغة. جرّب إضافة عميل وهمي، ثم مشروع ومهمة مرتبطين به. حدّث الصفحة وتأكد من بقاء المهمة، ثم جرّب زر **English**. تُحفظ البيانات محليًا في المتصفح. بوابة العميل والاعتمادات والفواتير ضمن النطاق المخطط.

للمشاركة، اقرأ [دليل المساهمة](CONTRIBUTING.md#العربية).

## English

**MADAR OSS** is a workspace by **formmint** for creative agencies to manage clients, projects, tasks, deliverables, and invoices in one place. The interface is designed for Arabic (RTL) and English (LTR).

### How it works

An agency creates a client project, assigns tasks, and uploads a design or video for internal review. Once a version is shared in the client portal, the client can approve it or request changes. The project keeps a record of versions and decisions, and the agency tracks invoices and payments in the same workspace.

### First release scope

- Manage clients, projects, tasks, and deadlines.
- Give clients a portal for items the agency chooses to share.
- Track deliverable versions, approvals, and revision requests.
- Attach invoices, record payments, and track outstanding balances.
- Support Arabic and English across the agency workspace and client portal.

### Try the current prototype

Select **Code → Download ZIP**, extract it, and open `index.html` in a browser. Alternatively, run `python3 -m http.server 8000` from the project folder and open <http://localhost:8000>.

The prototype supports clients, projects, tasks, and language switching. Add a sample client, a project for that client, and a task for that project. Refresh to verify the task persists, then switch languages. Data is stored locally in your browser. The client portal, approvals, and invoicing are planned.

See the [contribution guide](CONTRIBUTING.md#english) to get involved.

## License

[MIT](LICENSE)
