[English](https://github.com/carlmasters02/carlmasters02/blob/main/README.md) · [日本語](https://github.com/carlmasters02/carlmasters02/blob/main/README.ja.md) · **Tiếng Việt** · [한국어](https://github.com/carlmasters02/carlmasters02/blob/main/README.ko.md) · [中文](https://github.com/carlmasters02/carlmasters02/blob/main/README.zh.md) · [ไทย](https://github.com/carlmasters02/carlmasters02/blob/main/README.th.md) · [Tagalog](https://github.com/carlmasters02/carlmasters02/blob/main/README.tl.md) · [Français](https://github.com/carlmasters02/carlmasters02/blob/main/README.fr.md)

## 👋 Xin chào, tôi là Carl Masters

Sinh viên an ninh mạng tại Temple University Japan (Đại học Temple, cơ sở Nhật Bản).

[![Trang web](https://img.shields.io/badge/carlmasters.com-000000?style=flat&logo=googlechrome&logoColor=white)](https://carlmasters.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/carl-masters-724951297)
![Vị trí](https://img.shields.io/badge/Tokyo,%20Nh%E1%BA%ADt%20B%E1%BA%A3n-informational?style=flat&logo=googlemaps&logoColor=white)

*Các kho mã nguồn, bài viết và website được liên kết đều bằng tiếng Anh.*

---

### Định hướng

Tôi là sinh viên an ninh mạng tại Temple University Japan, bị cuốn hút bởi khía cạnh tấn công của lĩnh vực này và bởi việc hiểu hệ thống thất bại ra sao trong thực tế chứ không phải trên lý thuyết. Phần lớn công việc của tôi là xây dựng công cụ bảo mật từ con số không. Tôi thà tự giải mã một giao thức từng byte một còn hơn dùng sẵn một thư viện phân tích cú pháp, và tôi học một kỹ thuật tấn công bằng cách tự cài đặt nó lên một mục tiêu được cố ý làm cho dễ bị khai thác, thay vì chỉ đọc về nó. Những tầng khiến tôi hứng thú nhất là nơi các giả định sụp đổ: cách hiện thực thuật toán mật mã, việc xử lý đầu vào và bộ nhớ, và lưu lượng mạng ở dạng thô. Tôi coi trọng việc giải thích vì sao một lỗ hổng tồn tại ngang với việc tìm ra nó, và đó là lý do hầu hết dự án của tôi đều đi kèm một bài viết phân tích bên cạnh mã nguồn.

---

### Ngôn ngữ chính

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)

---

### Dự án theo ngôn ngữ chính

Những công cụ nhỏ, độc lập, chứng minh các ngôn ngữ ở trên bằng mã nguồn chạy được. Mỗi công cụ lấy một ngôn ngữ và áp dụng vào một vấn đề thực tế, để mức độ thành thạo mà tôi nói đến luôn đi kèm thứ bạn có thể đọc được.

| Dự án | Mục đích | Công nghệ |
| --- | --- | --- |
| [secret-scanner](https://github.com/carlmasters02/secret-scanner) | Công cụ dòng lệnh quét mã nguồn để tìm những bí mật bị viết cứng trong code, kết hợp so khớp mẫu bằng biểu thức chính quy với phân tích entropy Shannon để bắt được những chuỗi ngẫu nhiên cao mà các mẫu cố định bỏ sót. Được viết để rèn phân tích tĩnh, thao tác I/O tệp và thiết kế CLI trong Python. | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) |
| [cryptfile](https://github.com/carlmasters02/cryptfile) | Công cụ dòng lệnh mã hóa tệp bằng AES-256-GCM dựa trên OpenSSL, sinh khóa từ cụm mật khẩu bằng PBKDF2. Được viết để rèn việc quản lý bộ nhớ ở mức thấp, I/O tệp nhị phân và tích hợp thư viện mật mã trong C. | ![C](https://img.shields.io/badge/-C-A8B9CC?style=flat&logo=c&logoColor=black) ![OpenSSL](https://img.shields.io/badge/-OpenSSL-721412?style=flat&logo=openssl&logoColor=white) |

---

### Dự án bảo mật & hệ thống

| Dự án | Mục đích | Công nghệ |
| --- | --- | --- |
| [network-protocol-analyzer](https://github.com/carlmasters02/network-protocol-analyzer) | Bộ phân tích gói tin trực tiếp, tự giải mã Ethernet, IPv4, TCP/UDP và DNS từ các byte thô bằng tay, không dùng bất kỳ thư viện phân tích cú pháp nào. Truyền dữ liệu ra giao diện terminal, xuất PCAP cho Wireshark, và phát hiện quét cổng, DNS tunneling cùng giả mạo ARP ngay khi chúng xảy ra. | ![Rust](https://img.shields.io/badge/-Rust-000000?style=flat&logo=rust&logoColor=white) |
| [python-static-analyzer](https://github.com/carlmasters02/python-static-analyzer) | Tìm lỗ hổng SQL injection và command injection trong mã nguồn Python mà không cần chạy chương trình, dùng phân tích AST cùng theo vết dữ liệu nhiễm bẩn từ nguồn đến đích để báo cáo tệp nào, dòng nào và vì sao có thể bị khai thác. Độ chính xác và độ bao phủ được đo đạc trên các mẫu lỗ hổng đã gán nhãn. | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white) |
| [coverage-guided-fuzzer](https://github.com/carlmasters02/coverage-guided-fuzzer) | Bộ fuzzer theo phong cách AFL, tìm lỗi sập chương trình bằng cách đột biến đầu vào dựa trên phản hồi về độ bao phủ mã thay vì đoán mò, rồi rút gọn mỗi lần sập về trường hợp tái hiện nhỏ nhất. | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![C](https://img.shields.io/badge/-C-A8B9CC?style=flat&logo=c&logoColor=black) |
| [Crypto-Attack-Lab](https://github.com/carlmasters02/Crypto-Attack-Lab) | Phòng lab thực hành các đòn tấn công mật mã kinh điển: padding oracle, hash length extension, ECB cut-and-paste, tấn công Wiener lên RSA, và một kênh kề thời gian. Mỗi phần đều có một hiện thực đơn giản cố ý để lộ lỗ hổng, một mã khai thác chạy được, và bài viết phân tích sai lầm ngoài đời thực đứng sau nó. | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white) |
| [python-cli-template](https://github.com/carlmasters02/python-cli-template) | Một khuôn mẫu dùng lại được cho nề nếp tổ chức kho mã chuyên nghiệp: bố cục `src/`, pytest kèm đo độ bao phủ, CI bằng GitHub Actions, huy hiệu trạng thái, Dockerfile, và các bản phát hành gắn thẻ theo semver. | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white) |

---

### Phát triển ứng dụng web

| Dự án | Mục đích | Công nghệ |
| --- | --- | --- |
| [FocusHear](https://focus-hear-app.vercel.app/) | Nền tảng hỗ trợ giao tiếp thời gian thực dành cho người khiếm thính. Mọi ứng dụng phụ đề đều ghi lại lời của tất cả mọi người cùng lúc, dội vào người dùng những giọng nói chồng chéo lên nhau; FocusHear cho phép bạn chọn nghe giọng của ai, với khả năng nghe chọn lọc, một cầu nối ngôn ngữ ký hiệu cho bảng chữ cái ngón tay ASL, và phân tách người nói dựa trên giọng đã đăng ký. Được xây trong 48 giờ và giành **giải nhất** tại SDGs to Startups 2026, sau đó dựng lại trên nền GPT-4o và ElevenLabs Scribe với tài khoản có xác thực, thanh toán, hồ sơ giọng nói và khuôn mặt được lưu lại, cùng một mô hình ngôn ngữ ký hiệu ONNX LSTM đã huấn luyện, rồi mang tới sự kiện Build with OpenAI theo lời mời riêng và lọt vào vòng đầu tiên. Xem tại [focus-hear-app.vercel.app](https://focus-hear-app.vercel.app/). | ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) ![OpenAI](https://img.shields.io/badge/-GPT--4o-412991?style=flat&logo=openai&logoColor=white) ![Supabase](https://img.shields.io/badge/-Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white) ![Stripe](https://img.shields.io/badge/-Stripe-635BFF?style=flat&logo=stripe&logoColor=white) ![Vercel](https://img.shields.io/badge/-Vercel-000000?style=flat&logo=vercel&logoColor=white) |

---

### Portfolio & Website

| Dự án | Mục đích | Công nghệ |
| --- | --- | --- |
| [Portfolio cá nhân của tôi](https://carlmasters.com) | Trang portfolio cá nhân nơi tôi giới thiệu kỹ năng, thành tích và nhiều thứ khác. Xem tại [carlmasters.com](https://carlmasters.com), mã nguồn tại [My-Personal-Portfolio](https://github.com/carlmasters02/My-Personal-Portfolio). | ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) |
| [Kady's English Classes](https://kadysenglish.com) | Website được thiết kế và xây dựng cho một giáo viên tiếng Anh tự do ở Việt Nam. Xem tại [kadysenglish.com](https://kadysenglish.com). | ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) |

---

### Sự kiện & Hackathon

| Thời gian | Sự kiện | Ghi chú |
| --- | --- | --- |
| Tháng 7, 2026 | Cursor Tokyo AI Meetup | Một buổi tối cùng đội ngũ Cursor tại Datadog Japan, xoay quanh Cloud Agents và cách tổ chức các quy trình lập trình tự hành. |
| Tháng 7, 2026 | Engineering Real World AI with Google and Google DeepMind | Bài phát biểu chính và một workshop Google AI Studio tại Google Japan về việc đưa hệ thống AI từ nguyên mẫu ra sản phẩm thật. |
| Tháng 7, 2026 | Agent Forge AI Hackathon | Hackathon một ngày về các AI agent sẵn sàng cho môi trường thật, lấy chủ đề Tokyo và văn hóa Nhật Bản. Tham gia một mình. |
| Tháng 7, 2026 | ai& × Moonshot Tokyo Hackathon Night | Hackathon gói gọn trong một buổi tối, xây quanh Kimi K2.7 Code chạy trên nền tảng suy luận của ai&. |
| Tháng 7, 2026 | Vibe Coders Tokyo: Local Models with Gemma 4 | Chạy các mô hình open-weight trên phần cứng cá nhân, và điều đó thay đổi những gì về chi phí, độ trễ và quyền kiểm soát dữ liệu của chính mình. |
| Tháng 6, 2026 | OpenAI × Tokyo AI: Build with OpenAI | Sự kiện xây dựng theo lời mời riêng. Mang tới bản FocusHear dựng lại với kiến trúc sẵn sàng cho sản phẩm thật và lọt vào vòng đầu tiên. |
| Tháng 6, 2026 | SDGs to Startups Hackathon 2026 | **Giải nhất.** Một cuộc thi xây dựng 48 giờ hướng tới Mục tiêu Phát triển Bền vững số 10 của Liên Hợp Quốc, với FocusHear tách riêng một giọng nói cho người khiếm thính. |
| Tháng 3, 2026 | Builders Weekend 2026 | Cùng nhóm năm người ở Temple University Japan hoàn thiện TabeTalk: ứng dụng AI cho việc đi ăn, nhận biết ai đã gọi món gì qua giọng nói và chia hóa đơn. |
| Tháng 3, 2026 | UI/UX Hackathon | **Giải nhất.** Nghiên cứu nhu cầu người dùng, dựng wireframe và làm nguyên mẫu giao diện, rồi bảo vệ từng quyết định thiết kế trước ban giám khảo. |

---

### 📚 Bài viết mới nhất

- [Cách viết một CV thực sự được đọc](https://carlmasters.com/article-resume.html)
- [Những thói quen an ninh mạng hằng ngày thực sự có ý nghĩa](https://carlmasters.com/article-cybersecurity.html)
- [Bộ công cụ riêng tư: lựa chọn thay thế mã nguồn mở và có mã hóa cho mọi ứng dụng bạn dùng](https://carlmasters.com/article-privacy.html)

---

### Liên kết

- 🌐 Website: [carlmasters.com](https://carlmasters.com)
- 💼 LinkedIn: [carl-masters](https://www.linkedin.com/in/carl-masters-724951297)
