# Phương Án Xây Dựng Hệ Thống Quản Lý Điều Hành — Công Ty Cổ Phần Thời Trang Đồng Phục Hoa Tay (`1 Sổ Gốc Duy Nhất · 4 Chặng Đường · 7 Chốt Chặn Tự Động` — Bộ Tài Liệu Archify Tương Tác)

Bộ hồ sơ trực quan hóa **100% Tiếng Việt** chuyển thể toàn bộ bản thiết kế vận hành chi tiết (**Operating Blueprint & Báo giá `QT-2026-HOATAY-03`**) của **Công ty Cổ phần Thời trang Đồng phục Hoa Tay** (`MST: 0314883250` · Văn phòng `99 Nguyễn Thái Sơn, Gò Vấp` & Xưởng sản xuất `Hóc Môn, TP.HCM`) thành trang tương tác trực quan, dễ nhìn, dễ hiểu cho Ban Giám Đốc, Kế toán trưởng, Quản lý sản xuất và toàn bộ đội ngũ.

Toàn bộ các trang HTML đều đạt chuẩn **Standalone Interactive Archify Showcase (`0 errors, 0 warnings, 0 route crossings`)**, hoạt động độc lập (offline-first, không cần cài đặt thêm thư viện), hỗ trợ chuyển đổi **Giao diện Sáng / Tối (`Sáng / Tối`)**, chế độ **Đọc nhanh / Đầy đủ (`Đọc nhanh / Đầy đủ`)**, **Chạy từng bước (`▶ Chạy từng bước` / `▶ Chạy từng thông điệp`)**, lọc theo **Góc nhìn (`Views`)**, tìm kiếm nút trực tiếp và **Xuất ảnh PNG / SVG / WebM**.

---

## 🌐 Link Xem Trực Tiếp Trên Web (GitHub Pages)

- **Trang Chủ Tổng Hợp (Master One-Page Interactive Explainer):** **[https://tipovuhoa26-sudo.github.io/dong-phuc-hoa-tay-mini-erp/](https://tipovuhoa26-sudo.github.io/dong-phuc-hoa-tay-mini-erp/)**
- **Kho Mã Nguồn GitHub (`tipovuhoa26-sudo`):** **[https://github.com/tipovuhoa26-sudo/dong-phuc-hoa-tay-mini-erp](https://github.com/tipovuhoa26-sudo/dong-phuc-hoa-tay-mini-erp)**

---

## 🌟 1. Trang Cẩm Nang Tổng Hợp Duy Nhất (Master One-Page Interactive Explainer)

Mở trực tiếp một trong hai file dưới đây trên trình duyệt (`Chrome` / `Safari` / `Edge`) để xem **trọn bộ khung vận hành 1 Sổ gốc – 4 Chặng – 7 Chốt chặn, 10 sơ đồ tương tác, 3 biểu đồ dữ liệu, câu chuyện xuyên suốt 20 bước của đơn hàng 400 bộ Bệnh viện Đa khoa Tâm An (`@steps` bấm tới đâu sáng đèn sơ đồ tới đó), danh mục 12 hợp phần – 52 tính năng, lộ trình 34 tuần – 9 đợt nghiệm thu và checklist vận hành có ô tích chọn trực tiếp (`✓`)**:

- **[`index.html`](./index.html)** *(Trang chủ mặc định — tích hợp toàn bộ 10 sơ đồ tương tác + 3 biểu đồ + 20 bước mẫu + Checklist trên 1 trang duy nhất)*
- **[`00-hoa-tay-mini-erp-operating-blueprint-explainer.html`](./00-hoa-tay-mini-erp-operating-blueprint-explainer.html)** *(Bản sao đồng bộ của `index.html`)*
- Tài liệu gốc Markdown: [`dong-phuc-hoa-tay-mini-erp-operating-blueprint-proposal.md`](./dong-phuc-hoa-tay-mini-erp-operating-blueprint-proposal.md)

---

## 🗺️ 2. Danh Mục 10 Sơ Đồ Archify Độc Lập (`01` -> `10`)

Mỗi sơ đồ dưới đây giải phẫu một góc nhìn cụ thể trong **Hệ Thống Quản Lý Điều Hành Đồng Phục Hoa Tay** và đều đã được nhúng trực tiếp vào trang tổng hợp [`index.html`](./index.html):

| STT | File Sơ Đồ Tương Tác (HTML) | Loại Sơ Đồ (`Archify Type`) | Nội Dung & Cơ Chế Giải Thích Trong Sơ Đồ | File Nguồn Đặc Tả (`sources/`) |
| :--- | :--- | :--- | :--- | :--- |
| **01** | **[`01-hoa-tay-mini-erp-1-so-goc-architecture.html`](./01-hoa-tay-mini-erp-1-so-goc-architecture.html)** | `architecture` | **Bức Tranh Toàn Cảnh "Từ 5 Nơi Rời Rạc Sang 1 Sổ Gốc Duy Nhất":** Thay thế hoàn toàn `GetFly CRM`, `2 file Excel TĐSX/QLĐHSX`, `Google Drive`, `FAST` và `Nhóm Zalo` bằng 1 hệ thống liên thông cho 9 vị trí (`Gò Vấp` ↔ `Hóc Môn`) | [`01-hoa-tay-mini-erp-1-so-goc-architecture.json`](./sources/01-hoa-tay-mini-erp-1-so-goc-architecture.json) |
| **02** | **[`02-hoa-tay-4-chang-7-chot-chan-workflow.html`](./02-hoa-tay-4-chang-7-chot-chan-workflow.html)** | `workflow` | **Khung Vận Hành 4 Chặng Đường & 7 Chốt Chặn Tự Động (`SCOR` + `Stage-Gate`):** Swimlane 3 làn (`Văn Phòng Gò Vấp`, `Xưởng Hóc Môn & Kế Toán`, `Luồng Ngoại Lệ & Phê Duyệt`) khóa chặt 7 rủi ro đứt gãy | [`02-hoa-tay-4-chang-7-chot-chan-workflow.json`](./sources/02-hoa-tay-4-chang-7-chot-chan-workflow.json) |
| **03** | **[`03-hoa-tay-20-buoc-benh-vien-tam-an-sequence.html`](./03-hoa-tay-20-buoc-benh-vien-tam-an-sequence.html)** | `sequence` | **Câu Chuyện Xuyên Suốt 20 Bước (`B01`–`B20`) — Đơn Hàng 400 Bộ Bệnh Viện Đa Khoa Tâm An:** Từ lúc chị Lan hỏi mua, quét QR mẫu áo, tra ngày giao `< 5 phút`, khóa sửa đơn khi cọc 30% đến giao 2 cơ sở (`Quận 3` & `Thủ Đức`) và tính lãi ròng `30,9%` | [`03-hoa-tay-20-buoc-benh-vien-tam-an-sequence.json`](./sources/03-hoa-tay-20-buoc-benh-vien-tam-an-sequence.json) |
| **04** | **[`04-hoa-tay-vong-doi-don-hang-7-trang-thai-lifecycle.html`](./04-hoa-tay-vong-doi-don-hang-7-trang-thai-lifecycle.html)** | `lifecycle` | **Vòng Đời Đơn Hàng & Cơ Chế Khóa Sửa Đơn + Kiểm Hàng 9 Bước (`SV-15`, `SV-34`):** Máy trạng thái kiểm soát báo giá đa phiên bản (`v1, v2, v3`), khóa tự ý sửa đơn sau khi thu cọc và chặn phiếu giao hàng nếu thiếu bước QC | [`04-hoa-tay-vong-doi-don-hang-7-trang-thai-lifecycle.json`](./sources/04-hoa-tay-vong-doi-don-hang-7-trang-thai-lifecycle.json) |
| **05** | **[`05-hoa-tay-xep-lich-3-nhom-tho-5-phut-waterfall.html`](./05-hoa-tay-xep-lich-3-nhom-tho-5-phut-waterfall.html)** | `waterfall` | **Giải Phẫu 4 Phút 30 Giây (`270 Giây`) Tra Ngày Giao & Xếp Lịch 3 Nhóm Thợ (`M6`):** Thay thế 1–4 giờ hỏi qua lại bằng thuật toán đối chiếu công suất hữu hạn (`1. Thợ nhà` -> `2. Thợ thời vụ` -> `3. Thợ gia công ngoài`) | [`05-hoa-tay-xep-lich-3-nhom-tho-5-phut-waterfall.json`](./sources/05-hoa-tay-xep-lich-3-nhom-tho-5-phut-waterfall.json) |
| **06** | **[`06-hoa-tay-gop-mua-vai-tinh-gia-thanh-lo-dataflow.html`](./06-hoa-tay-gop-mua-vai-tinh-gia-thanh-lo-dataflow.html)** | `dataflow` | **Luồng Dữ Liệu Gộp Mua Vải, Xuất Kho Theo Lệnh & Tính Giá Thành Từng Lô (`M9`, `M10`):** Tự động gộp nhu cầu vải nhiều đơn đặt 1 lần để được giá sỉ và tự gom 3 khoản chi phí thực tế (`Vải + Công + Chi phí khác`) so với báo giá | [`06-hoa-tay-gop-mua-vai-tinh-gia-thanh-lo-dataflow.json`](./sources/06-hoa-tay-gop-mua-vai-tinh-gia-thanh-lo-dataflow.json) |
| **07** | **[`07-hoa-tay-9-vi-tri-phan-quyen-mobile-tree.html`](./07-hoa-tay-9-vi-tri-phan-quyen-mobile-tree.html)** | `tree` | **Sơ Đồ Cây Phân Quyền 9 Vị Trí Trên Điện Thoại & Máy Tính (`SV-01`, `SV-02`):** Ai vào hệ thống chỉ thấy đúng phần việc của mình; Tổ trưởng và QC chỉ cần 3 nút bấm to, rõ chữ trên điện thoại tại xưởng Hóc Môn | [`07-hoa-tay-9-vi-tri-phan-quyen-mobile-tree.json`](./sources/07-hoa-tay-9-vi-tri-phan-quyen-mobile-tree.json) |
| **08** | **[`08-hoa-tay-so-goc-lien-thong-erd.html`](./08-hoa-tay-so-goc-lien-thong-erd.html)** | `erd` | **Sơ Đồ 6 Ngăn Tủ Dữ Liệu Liên Thông Trong Sổ Gốc Duy Nhất (`ERD`):** Kết nối xuyên suốt `customers_crm`, `quotations_orders`, `production_orders_7teams`, `fabric_inventory_po`, `qc_9steps_delivery` và `lot_costing_accounting` | [`08-hoa-tay-so-goc-lien-thong-erd.json`](./sources/08-hoa-tay-so-goc-lien-thong-erd.json) |
| **09** | **[`09-hoa-tay-lo-trinh-34-tuan-9-dot-timeline.html`](./09-hoa-tay-lo-trinh-34-tuan-9-dot-timeline.html)** | `timeline` | **Lộ Trình 34 Tuần (`50,2 Ngày Công`) & 9 Đợt Thanh Toán Theo Kết Quả Nghiệm Thu:** Cuốn chiếu từng hợp phần từ `M0` đến `M11`; làm xong phần nào, chạy đúng mới thanh toán phần đó (`121.451.000 VNĐ` sau thuế) | [`09-hoa-tay-lo-trinh-34-tuan-9-dot-timeline.json`](./sources/09-hoa-tay-lo-trinh-34-tuan-9-dot-timeline.json) |
| **10** | **[`10-hoa-tay-12-hop-phan-52-tinh-nang-workflow.html`](./10-hoa-tay-12-hop-phan-52-tinh-nang-workflow.html)** | `workflow` | **Bản Đồ Tổng Thể 12 Hợp Phần (`M0`–`M11`) & 52 Tính Năng (`SV-01`–`SV-52`):** Từ buổi khảo sát M0 chốt biểu mẫu in ấn & công thức giá thành với chị Liên đến bàn giao, chuyển dữ liệu GetFly và bảo hành 3 tháng | [`10-hoa-tay-12-hop-phan-52-tinh-nang-workflow.json`](./sources/10-hoa-tay-12-hop-phan-52-tinh-nang-workflow.json) |

---

## 📊 3. Dữ Liệu Nguồn & Đặc Tả (`sources/`)

- Đặc tả Master Explainer: [`sources/hoa-tay-mini-erp-operating-blueprint.archify.md`](./sources/hoa-tay-mini-erp-operating-blueprint.archify.md)
- Dữ liệu biểu đồ 1 (So sánh thời gian xử lý 6 nghiệp vụ cốt lõi Trước vs Sau): [`sources/hoa-tay-time-saved-comparison.csv`](./sources/hoa-tay-time-saved-comparison.csv)
- Dữ liệu biểu đồ 2 (Phân bổ ngân sách trước thuế 12 hợp phần `M0`–`M11` = `110,41 Triệu VNĐ`): [`sources/hoa-tay-12-modules-cost-breakdown.csv`](./sources/hoa-tay-12-modules-cost-breakdown.csv)
- Dữ liệu biểu đồ 3 (Lộ trình 9 đợt thanh toán theo kết quả nghiệm thu = `121,451 Triệu VNĐ` gồm VAT): [`sources/hoa-tay-9-payment-milestones.csv`](./sources/hoa-tay-9-payment-milestones.csv)
