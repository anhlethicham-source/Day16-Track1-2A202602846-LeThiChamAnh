# Memo Teardown — Grammarly

**Họ tên:** …

**Vì sao chọn sản phẩm này:** (1–2 câu)

**§1. Timeline các cập nhật lớn**

| Thời điểm | Cập nhật | Context lúc đó | Nguyên lý |
|---|---|---|---|
| ~2015 | **Browser extension miễn phí cho Chrome**: Grammarly chạy ngay trong mọi ô nhập liệu (Gmail, Google Docs, LinkedIn…). [Nguồn](https://www.grammarly.com/blog/company/grammarly-12-year-history/) | Grammarly ra đời năm 2009 dưới dạng web editor, phục vụ sinh viên và người viết tiếng Anh như ngôn ngữ thứ hai. Muốn dùng thì phải copy-paste văn bản sang. Word đã có chính tả miễn phí, nên sửa lỗi giỏi hơn một chút không đủ để người dùng đổi thói quen. | **x10 (độ phủ)**: chất lượng sửa lỗi không hơn Word gấp 10 lần, nhưng sản phẩm có mặt ở đúng nơi người dùng đang viết, nên không còn ma sát chuyển công cụ. |
| 09/2019 | **Tone Detector (beta)** trên extension Chrome cho Gmail/Yahoo, nhận diện khoảng 40 giọng điệu. [Nguồn](https://techcrunch.com/2019/09/24/grammarly-gets-a-tone-detector-to-keep-you-out-of-email-trouble) | Extension đã chạy khoảng 4 năm và tích lũy hàng triệu lượt chấp nhận/bỏ qua gợi ý mỗi ngày. Ngữ pháp dần thành hàng phổ thông, nên Grammarly chuyển định vị từ "sửa lỗi" sang "giao tiếp hiệu quả", và email công việc là mặt trận chính. | **Vòng lặp học**: dữ liệu phản hồi tích lũy cho phép giải bài toán khó hơn ngữ pháp là giọng điệu, thứ đối thủ mới vào nghề khó sao chép ngay. |
| 06/2020 | **Style Guides cho Grammarly Business**: doanh nghiệp tự đặt quy tắc riêng (tên sản phẩm, thuật ngữ, brand voice). Atlassian và Zapier được dùng sớm. [Nguồn](https://www.destinationcrm.com/Articles/CRM-News/CRM-Across-the-Wire/Grammarly-Launches-Style-Guides-141192.aspx) | COVID đẩy làm việc từ xa lên, giao tiếp bằng văn bản tăng vọt. Doanh nghiệp cần thống nhất giọng thương hiệu trên hàng nghìn nhân viên. Grammarly cần nguồn doanh thu B2B ổn định hơn gói cá nhân. | **Moat**: quy tắc riêng của từng công ty nằm trong Grammarly, gắn sản phẩm vào quy trình nên chi phí rời bỏ tăng theo thời gian dùng. |
| 03/2023 | **GrammarlyGO**: viết mới, viết lại, trả lời email bằng generative AI, chạy ngay trong ứng dụng người dùng đang dùng. Beta từ 04/2023. [Nguồn](https://www.techrepublic.com/article/grammarlygo-ai-writing-emails/) | ChatGPT ra mắt 11/2022, biến "viết lại cho hay" thành năng lực ai cũng có miễn phí. Đây là đe dọa trực tiếp vào giá trị cốt lõi của Grammarly. | **Wrapper đứng trên moat**: lớp LLM ai cũng làm được, nhưng GrammarlyGO sống nhờ kênh phân phối có sẵn (extension trong mọi ô nhập liệu), nên người dùng không phải mở tab ChatGPT. |
| 08/2024 | **Grammarly Authorship**: tô màu từng đoạn là người gõ, AI tạo, AI chỉnh hay dán từ nguồn ngoài, kèm replay quá trình viết. Beta trên Google Docs từ 09/2024. [Nguồn](https://www.grammarly.com/blog/company/grammarly-launches-grammarly-authorship/) | Giáo dục rơi vào khủng hoảng niềm tin vì AI: AI detector thiếu chính xác, sinh viên bị buộc tội oan, còn Grammarly cũng bị nhìn như công cụ "gian lận". | **Vertical AI**: quay về vertical gốc là giáo dục, giải nỗi đau mới do chính AI tổng quát gây ra. Đây là bài toán chatbot không giải được vì nó cần dữ liệu về *quá trình* gõ, không chỉ văn bản cuối. |
| 12/2024 và 07/2025 | **Mua Coda** (CEO Coda là Shishir Mehrotra lên làm CEO Grammarly) và **mua Superhuman Mail**. [Nguồn Coda](https://www.bloomberg.com/news/articles/2024-12-17/grammarly-acquires-startup-coda-bringing-mehrotra-as-new-ceo), [Nguồn Superhuman](https://siliconangle.com/2025/07/01/grammarly-acquires-email-client-developer-superhuman/) | LLM nào cũng sửa văn được, nên con hào "sửa văn" cạn dần. Muốn giữ vị trí, Grammarly cần sở hữu chính bề mặt nơi công việc diễn ra: tài liệu (Coda) và email (Superhuman, khoảng 35 triệu USD doanh thu năm). | **Moat**: mua thêm bề mặt và kênh phân phối thay vì chỉ là lớp phủ trên sản phẩm của người khác. |
| 08/2025 | **8 agent chuyên biệt trong Grammarly Docs**: AI Grader (chấm theo rubric), Reader Reactions (dự đoán phản ứng người đọc), Citation Finder, Expert Review, AI Detector… [Nguồn](https://www.plagiarismtoday.com/2025/08/19/grammarly-launches-new-ai-powered-editor) | Chatbot tổng quát rất mạnh, nhưng người dùng phải tự viết prompt công phu. Mùa tựu trường là lúc sinh viên dùng AI nhiều nhất. | **Vertical AI**: đóng gói các tác vụ hẹp và sâu thành nút bấm sẵn, có ngữ cảnh (rubric, đối tượng người đọc), thay cho prompt tự viết. |
| 10/2025 | **Đổi tên công ty thành Superhuman**, ra **Superhuman Go** (trợ lý điều phối agent bên thứ nhất và bên thứ ba, kết nối hơn 100 app) và **Superhuman SDK** (closed beta) cho nhà phát triển tự làm agent. [Nguồn](https://siliconangle.com/2025/10/29/grammarly-transforms-ai-enabled-productivity-suite-superhuman-rebrand/) | Cuộc đua "AI agent" của Big Tech và startup. Grammarly đã có đủ bộ bề mặt (viết, doc, email) và cần một lớp gắn kết chúng thành nền tảng. | **Vòng lặp (dạng hệ sinh thái)**: nhiều agent hơn thì người dùng có thêm lý do giữ extension, nhiều người dùng hơn thì nhà phát triển muốn làm agent hơn. Vòng lặp chuyển từ dữ liệu sang hiệu ứng mạng. *Lưu ý: SDK mới ở closed beta, vòng lặp này mới là kỳ vọng, chưa được kiểm chứng.* |

**Vì sao chọn những mốc này:** Mỗi mốc được giữ lại vì nó thay đổi ít nhất một trong ba thứ: Grammarly *có mặt ở đâu* (extension, Coda, Superhuman), *phục vụ ai* (sinh viên, doanh nghiệp, giáo dục thời AI), hoặc *lấy gì để phòng thủ* (dữ liệu, quy trình, phân phối, hệ sinh thái). Tôi loại ba mốc:
- **Thành lập năm 2009:** đây là điểm xuất phát chứ không phải bản cập nhật, nên được đưa vào phần context của mốc 2015.
- **Grammarly Text Editor SDK (2021):** bị khai tử ngày 10/01/2024 để dồn lực cho sản phẩm lõi và AI ([nguồn](https://alternativeto.net/news/2023/7/grammarly-to-discontinue-text-editor-sdk-shifts-focus-to-core-product-and-ai-integration/)). Đây là phản ví dụ đáng chú ý: lần đầu Grammarly thử xây moat bằng SDK thì thất bại, và lần thử thứ hai (Superhuman SDK 2025) vẫn chưa có kết quả.
- **Các tính năng lẻ như plagiarism checker hay bản desktop/mobile:** chúng tăng độ phủ nhưng lặp lại đúng nguyên lý của mốc extension, không thêm insight mới.

**§2. Tệp user & JTBD**

| | Early adopters (2009 đến khoảng 2015) | Tệp hiện tại (2025–2026) |
|---|---|---|
| Đặc điểm | Sinh viên đại học, người viết tiếng Anh như ngôn ngữ thứ hai, giới học thuật. Dùng cá nhân, tự trả tiền hoặc dùng bản miễn phí. Tần suất theo mùa (mùa nộp bài). | Người làm việc tri thức viết cả ngày qua email, chat, tài liệu. Hơn 40 triệu người dùng hằng ngày và hơn 50.000 tổ chức trang bị cho nhân viên ([nguồn](https://www.businesswire.com/news/home/20250529436291/en/Grammarly-Announces-%241-Billion-Growth-Financing-With-General-Catalyst)). Người mua thường là công ty (IT, L&D, marketing), còn người dùng là nhân viên. Tệp giáo dục vẫn còn nhưng giờ chỉ là một segment. |
| JTBD chính | "Khi nộp bài hoặc gửi văn bản tiếng Anh quan trọng, giúp tôi không mắc lỗi, để không bị đánh giá thấp vì ngôn ngữ." | "Khi viết trong bất kỳ ứng dụng nào, giúp tôi truyền đạt đúng ý, đúng giọng, nhanh, và bớt việc vặt quanh nó (trả lời email, tìm thông tin, xếp lịch)." Với tệp giáo dục, có thêm JTBD mới: "chứng minh bài này là do tôi viết." |
| Trước đó họ làm bằng cách nào | Nhờ bạn bè, giáo viên hoặc writing center đọc hộ. Dùng spell check của Word. Tự tra từ điển và sách ngữ pháp. | Tự đọc lại, nhờ đồng nghiệp duyệt, tra style guide nội bộ dạng PDF. Gần đây thì copy-paste sang ChatGPT rồi dán lại. |

**Dịch chuyển tệp:** Không có một cú chuyển duy nhất. Tệp dịch dần qua ba mốc ở §1:
- **Extension (~2015)** là mốc quyết định. Khi Grammarly rời web editor để vào Gmail, LinkedIn, Google Docs, nó bắt đầu chạm đến dân đi làm viết email hằng ngày, không chỉ sinh viên viết luận theo mùa. Tần suất dùng chuyển từ "theo bài nộp" sang "mỗi ngày".
- **Tone Detector (2019)** đổi lời hứa từ "viết *đúng*" sang "viết *hiệu quả*". Ngữ pháp chủ yếu là nỗi lo của người viết ngôn ngữ thứ hai, còn giọng điệu trong email công việc là nỗi lo của *mọi* người, kể cả người bản xứ. Thị trường mở rộng từ ESL ra toàn bộ người viết tiếng Anh.
- **Style Guides cho Business (2020)** đổi *người trả tiền* từ cá nhân sang tổ chức. Đây là dịch chuyển về mô hình kinh doanh, không chỉ về người dùng.

Các mốc sau (Coda, Superhuman, Go) tiếp tục mở rộng từ "người viết" sang "người làm việc tri thức" nói chung. Ngược lại, Authorship (2024) và các agent cho sinh viên (2025) là nỗ lực *giữ* tệp gốc khi AI tổng quát đe dọa nó trực tiếp nhất.

**Switching cost (map 4 forces):**

| Lực | Hướng | Biểu hiện |
|---|---|---|
| **Push** (bất mãn với hiện tại) | Kéo đi | Gói Pro trả phí trong khi ChatGPT, Gemini, Copilot sửa văn miễn phí hoặc đã có sẵn trong gói công ty. Gợi ý "quá tay" làm văn bản mất giọng riêng. Sinh viên dùng Grammarly có thể bị giáo viên nghi là dùng AI. |
| **Pull** (sức hút của giải pháp mới) | Kéo đi | Copilot nằm sẵn trong Word/Outlook, Gemini nằm sẵn trong Gmail/Docs: cùng chỗ viết, không cần cài thêm, công ty đã trả tiền. Chatbot tổng quát làm được nhiều việc hơn sửa văn. |
| **Habit** (thói quen) | Giữ lại | Extension chạy ngầm ở mọi ô nhập liệu, gạch chân đỏ và bấm chấp nhận đã thành phản xạ sau nhiều năm. Không phải mở công cụ khác hay viết prompt. |
| **Anxiety** (lo ngại khi đổi) | Giữ lại | Với doanh nghiệp: style guide, brand voice, danh sách thuật ngữ đã nằm trong Grammarly; đổi công cụ phải dựng lại, đào tạo lại, qua lại quy trình bảo mật và mua sắm. Với sinh viên: lịch sử Authorship là bằng chứng chống bị buộc tội oan, và chưa chắc công cụ khác cho được bằng chứng tương đương. |

**Đánh giá:** Switching cost *không đều* giữa hai tệp. Tệp doanh nghiệp bị giữ chặt bởi Anxiety (quy trình, cấu hình, hợp đồng). Tệp cá nhân chỉ được giữ bởi Habit, trong khi Push và Pull ngày càng mạnh vì AI tổng quát miễn phí và Big Tech nhúng AI ngay vào Word/Gmail. Đây là lý do chiến lược 2024–2025 dồn vào việc sở hữu bề mặt (Coda, Superhuman Mail) và hệ sinh thái agent: biến Habit cá nhân thành phụ thuộc ở cấp tổ chức.

**§3. Ba dự đoán hướng đi (6–12 tháng tới)**

> *Lưu ý: §1 dừng ở 10/2025. Trước khi nộp, cần đối chiếu tin tức 2026 để chắc các dự đoán dưới đây chưa xảy ra.*

**Dự đoán 1** *(loại: mô hình kiếm tiền)*
- **Dự đoán:** Superhuman sẽ dồn doanh thu về gói bundle cấp tổ chức (Business/Enterprise). Các tính năng agent mạnh nhất, như Go kết nối nhiều app, agent bên thứ ba và agent tùy chỉnh, chỉ có ở gói cao. Gói Free và Pro cá nhân lùi về vai trò phễu: giữ extension sửa ngữ pháp để duy trì độ phủ, ít đầu tư tính năng mới.
- **Lập luận:** (1) Ở §2, tệp cá nhân có switching cost thấp và đang bị AI miễn phí kéo đi, còn tệp doanh nghiệp bị giữ bởi Anxiety, nên doanh thu bền phải đến từ tổ chức. (2) Khoản tài trợ 1 tỷ USD (05/2025) của General Catalyst là vốn dành riêng cho sales và marketing, hoàn trả dần từ doanh thu khách hàng mới, nên Superhuman chịu áp lực tăng doanh thu B2B nhanh ([nguồn](https://www.businesswire.com/news/home/20250529436291/en/Grammarly-Announces-%241-Billion-Growth-Financing-With-General-Catalyst)). (3) Ở §1, Superhuman Go miễn phí đến 01/02/2026 rồi phải kiếm tiền, và Superhuman Mail đã chỉ có trong gói Business. Tiền lệ "tính năng mới chỉ ở gói cao" đã có sẵn.

**Dự đoán 2** *(loại: segment)*
- **Dự đoán:** Grammarly sẽ bán giải pháp giáo dục ở cấp trường, không chỉ cho từng sinh viên. Sản phẩm sẽ gói Authorship, AI Grader và AI Detector thành một bộ tích hợp vào hệ thống quản lý học tập (LMS) như Canvas, Moodle, Google Classroom, để giáo viên xem báo cáo quá trình viết ngay trong nơi chấm bài.
- **Lập luận:** (1) Ở §1, Authorship (2024) và 8 agent (2025) cho thấy Grammarly liên tục quay về vertical gốc là giáo dục bằng các tác vụ hẹp mà chatbot không làm được. (2) Ở §2, JTBD mới của sinh viên ("chứng minh bài là của tôi") chỉ có giá trị khi *giáo viên* tin và dùng báo cáo, nên khách hàng thật của Authorship là nhà trường. (3) Điều này lặp lại đúng bài học Style Guides 2020: chuyển người trả tiền từ cá nhân sang tổ chức để tăng switching cost. Grammarly đã cập nhật Authorship để ghi nhận riêng phần do từng agent tạo ([nguồn](https://www.grammarly.com/blog/company/superhuman-authorship-docs/)), một bước chuẩn bị cho việc giải trình với nhà trường.

**Dự đoán 3** *(loại: đe dọa Big Tech)*
- **Dự đoán:** Microsoft (Copilot trong Word/Outlook) và Google (Gemini trong Gmail/Docs) sẽ tiếp tục ăn vào tệp cá nhân, khiến số người dùng Pro cá nhân chững lại. Superhuman sẽ phản ứng bằng cách định vị mình là *lớp AI trung lập chạy xuyên mọi ứng dụng*: Google, Microsoft, Slack, Salesforce, Jira, nghĩa là những việc mà Big Tech nào cũng không làm được vì chỉ tối ưu cho hệ sinh thái của mình. Kèm theo đó, Superhuman sẽ mở rộng Agents SDK ra ngoài closed beta để tăng nguồn cung agent bên thứ ba.
- **Lập luận:** (1) Ở §2, Pull từ Big Tech mạnh nhất đúng ở chỗ Grammarly từng thắng: "có mặt ở nơi người dùng đang viết". Khi AI đã nằm sẵn trong Word/Gmail, lợi thế x10 về độ phủ (mốc 2015) bị san phẳng. (2) Ở §1, cách duy nhất Grammarly còn x10 hơn Big Tech là tính *xuyên ứng dụng*. Go đã kết nối hơn 100 app, và vòng lặp hệ sinh thái (mốc 10/2025) chỉ chạy được khi có đủ agent bên thứ ba, nên SDK phải mở. (3) Rủi ro: lần thử SDK trước đã bị khai tử năm 2024, và Big Tech kiểm soát nền tảng mà extension phụ thuộc vào, nên Grammarly luôn đứng trên đất của người khác.

**§4. AI Log**

| Việc | AI làm hay bạn làm? | Bạn kiểm chứng/phán đoán lại thế nào? |
|---|---|---|
| | | |
| | | |
