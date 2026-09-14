# nhan-su-thiet-ke

**Vai Thiết kế trong đội nhân sự A.I** — của [Tô Hải Đoàn](https://www.facebook.com/tohaidoan/).

> **Phiên bản:** `1.0.0` · 2026-09-14 · giấy phép MIT

> 🟡 **Bản phát tạm.** Vai này nằm trong lời hứa *đội sáu vai*, nên phát đủ trước rồi tối ưu dần. Skill chạy được, nhưng **chưa qua đợt rà kỹ** như Content · Điều phối · Bán hàng. Gặp chỗ nói sai hay chạy hụt thì nhắn — bản sau sửa.

---

## Cài

```bash
claude plugin marketplace add creator-ceo/nhan-su-thiet-ke
```

```bash
claude plugin install thiet-ke
```

> ⚠️ **Lệnh đầu chỉ thêm nguồn, chưa cài gì.** Dừng ở đó rồi gõ lệnh là không thấy — đây là chỗ hay tưởng hỏng nhất.

## Hai lệnh

| Lệnh | Làm gì | Cần gì |
|---|---|---|
| `/anh-quote` | Ảnh chữ để đăng — đưa ảnh mẫu vào, ra tấm **cùng bố cục, màu và font của bạn** | **Chrome trên máy.** Không cần `npm install` |
| `/giai-thich-de-hieu` | Biến khái niệm khó thành **một trang có hình**, sơ đồ có cơ chế | trình duyệt · `python3` để xem thử |

⚠️ **Đọc CẤU TRÚC ảnh mẫu, không sao chép nhận diện.** Mượn bố cục của người ta, thay bằng màu và font của bạn.

## Đi kèm

| | |
|---|---|
| `anh-quote/dung.mjs` · `khung.html` | bộ máy render qua Chrome |
| `anh-quote/fonts/` | Be Vietnam Pro · Playpen Sans · Patrick Hand · Lora — đủ dấu tiếng Việt, giấy phép OFL |
| `anh-quote/kieu-mau/` | **sáu kiểu ảnh dựng sẵn** — chép vào `anh-quote/kieu/` của bạn rồi đổi màu, font |
| `giai-thich-de-hieu/xem.py` | server xem thử trang, ép `utf-8` để tiếng Việt không vỡ |

⚠️ **Sáu kiểu mẫu mang màu của mẫu gốc**, không phải màu của bạn. Chép ra rồi đổi trước khi đăng.

## ⚠️ Cần cái nền chạy trước

```bash
git clone https://github.com/creator-ceo/nhan-su-thu-thu.git
```

Vai này đọc **nhận diện màu và font** trong `systems-and-stack` — thứ `/phong-van-dinh-vi` của nền dựng ở chặng 5 — cùng `voice-profile` cho chữ trên ảnh. **Thiếu nhận diện là hỏng nặng nhất**: ảnh vẫn đẹp, nhưng không phải của thương hiệu bạn.

## Vai này nằm ở đâu trong đội

| Vai | Kho | |
|---|---|---|
| 🧑‍🏫 **Thủ thư** — cái nền, cài trước tiên | `creator-ceo/nhan-su-thu-thu` | ✅ |
| 🎛️ **Điều phối** *(Tổng giám đốc)* | `creator-ceo/nhan-su-dieu-phoi` | ✅ |
| ✍️ **Content** | `creator-ceo/nhan-su-content` | ✅ |
| 💰 **Bán hàng** | `creator-ceo/nhan-su-ban-hang` | ✅ |
| 🔍 **Nghiên cứu** | `creator-ceo/nhan-su-nghien-cuu` | 🟡 bản tạm |
| 🎨 **Thiết kế** | `creator-ceo/nhan-su-thiet-ke` | 🟡 bản tạm · **kho này** |
| 🤝 **Chăm sóc** | `creator-ceo/nhan-su-cham-soc` | 🟡 bản tạm |

📌 **Gọi vai bằng cách gõ tên lệnh.** Có `/dieu-hanh` *(vai Điều phối)* thì nó tự giao việc xuống vai này; không có thì gõ thẳng lệnh, vai đứng một mình được.

## Cập nhật

```bash
claude plugin update thiet-ke
```

Skill trong plugin bị ghi đè bằng bản mới; `wiki/` của bạn nằm ở thư mục khác nên **không bị đụng tới**.

---

## Ai làm cái này

**Tô Hải Đoàn** — người làm nội dung và xây thương hiệu cá nhân tại Việt Nam. Đây là quy trình tôi dùng cho công việc của chính mình, đóng gói lại để bạn chạy được trên dữ liệu của bạn.

**Kẹt ở đâu thì nhắn tôi:** [facebook.com/tohaidoan](https://www.facebook.com/tohaidoan/)
