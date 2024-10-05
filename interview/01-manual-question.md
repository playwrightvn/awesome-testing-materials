| **STT** | **Câu hỏi**                                                                                                                                                                                                                               | **Câu trả lời gợi ý**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
|---------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1       | **Bạn có thể kể tên các phương pháp để thử phần mềm không?**                                                                                                                                                                                 | Hiện tại có hai phương pháp để thử phần mềm bao gồm **kiểm thử hộp trắng** và **kiểm thử hộp đen**, trong đó:<br>**Kiểm thử hộp trắng**: Là quá trình mà các tester sẽ thực hiện kiểm tra mã code, thuật toán, cấu trúc chương trình được đưa ra thông qua yêu cầu. <br>**Kiểm thử hộp đen**: Công việc không yêu cầu tester phải biết kiến thức lập trình. Khi thực hiện quá trình kiểm thử tester chỉ cần xây dựng các trường hợp test dựa trên nhu cầu của khách hàng đưa ra về chức năng của hệ thống dựa trên bản đặc tả yêu cầu |
| 2       | **Black box testing là gì? White box testing là gì?**                                                                                                                                                                                        | Black Box: chỉ biết được giá trị input, output. Áp dụng cho người không biết technical mindset EX: Test login nếu success thì login thành công, ngược lại thì show ra message thông báo lỗi<br>White Box: biết được thiết kế cấu trúc giải thuật bên trong và thực hiện các công việc. Áp dụng cho developer, technical mindset EX: khi developer viết unit test                                                                                                                                                   |
| 3       | **Khác nhau giữa functional-testing và non-functional testing?**                                                                                                                                                                             | functional-testing: Kiểm tra chức năng của một phần mềm, thực hiện bằng tay. Ví dụ khi đăng nhập thì cần có textbox để nhập thông tin vào<br> non-functional testing: Liên quan đến các vấn đề hiệu suất, bảo mật, giao diện,... Thực hiện bằng tool. Ví dụ khi login thì sau 5 giây có login thành công hay không                                                                                                                                                                                              |
| 4       | **Kiểm thử hệ thống là gì?**                                                                                                                                                                                                                 | Là một phương pháp theo dõi và đánh giá hành vi của sản phẩm hoặc hệ thống phần mềm hoàn chỉnh đã được tích hợp đầy đủ, dựa vào đặc tả và các yêu cầu chức năng được xác định trước                                                                                                                                                                                                                                                                                                                                 |
| 5       | **Nêu các thành phần cơ bản của 1 Test case? (Câu này hỏi cho các UV junior, fresher ở bước đầu pv)**                                                                                                                                         | Tc ID, Tc Items, Priority, Assignee, Step by Step, Precondition,<br>Test Data, Expected results, Actual result,: pass/fail, Comments                                                                                                                                                                                                                                                                                                                                                                                  |
| 6       | **Test scenario là gì? Khác gì so với testcase?**                                                                                                                                                                                            | Test Scenario là tập hợp các testcase để test 1 form hoặc function, chỉ nêu mục đích, không chỉ ra các step cụ thể                                                                                                                                                                                                                                                                                                                                                                                                   |
| 7       | **Bạn sẽ làm gì khi developer nói là không thể tái tạo được lỗi của bạn?**                                                                                                                                                                   | Trao đổi với developer, ngồi lại với nhau liệt kê lại từng step một, xem có sai sót gì không, quên clear cache chẳng hạn,...                                                                                                                                                                                                                                                                                                                                                                                         |
| 8       | **Khi nào thì nên dừng quá trình kiểm thử?**                                                                                                                                                                                                 | Dựa vào điều kiện dừng của dự án để biết chính xác lúc nào tester nên dừng kiểm thử. Tùy vào từng dự án mà điều kiện dừng sẽ có sự khác nhau, tuy nhiên thường sẽ bao gồm các điều như:<br>Quá thời gian kiểm thử<br>Hết ngân sách chi trả<br>Đã đạt được yêu cầu về test case và tỷ lệ bug <br>Các lỗi phát hiện khi kiểm thử đã được fix<br>Sản phẩm ít bug, hoạt động ổn định, tốt<br>Kiểm thử đã hoàn thiện, tài liệu đã được cập nhật đầy đủ<br>Quản lý dự án quyết định dừng                     |
| 9       | **Em đã bao giờ viết test case mà không có requirement chưa, trong trường hợp đó thì em đưa ra những solution nào để giải quyết?**                                                                                                            | Trao đổi với khách hàng, nếu không có khách hàng thì trao đổi Project Manager (PM), Business Analyst (BA)                                                                                                                                                                                                                                                                                                                                                                                                              |
| 10      | **Bạn sẽ làm gì nếu phải thực hiện test chức năng, sản phẩm mà không có đặc tả yêu cầu của chức năng, hoặc bất kỳ tài liệu nào liên quan đến sản phẩm chức năng đó, trong khi dev, pm phát triển chức năng đó không còn làm tại công ty nữa?** | Với tình huống này, bạn sẽ cần phải làm thử nghiệm thăm dò (Exploratory testing) sản phẩm. Trong thử nghiệm này, bạn sẽ hiểu hơn về hệ thống và quy trình làm việc cơ bản của nó. Trong thử nghiệm thăm dò, bạn cũng có thể tìm thấy một số lỗi 'chặn' gây ra sự cố cho hệ thống                                                                                                                                                                                                                                 |
| 11      | **Trong một ứng dụng đang trong quá trình sản xuất, có 1 module đang được sửa đổi, có cần thiết phải kiểm tra toàn bộ ứng dụng đó hay không? Hay chỉ kiểm thử các chức năng liên quan đến module đó?**                                       | Module được thay đổi, cần thiết phải kiểm tra lại cả 2. Phải kiểm tra chức năng của Module đó cũng như các mô-đun khác. Nhưng chú trọng đến mô-đun được thay đổi nhiều hơn. <br>- Ví dụ: Module A thay đổi, module B phụ thuộc vào Module A, Module C độc lập với Module A thì<br>Ta cần kiểm thử chi tiết cho module A, thực hiện stress test module B<br>Ngoài ra cần kiểm tra các module nào sẽ bị ảnh hưởng để thực hiện kiểm thử hồi quy (Regression testing)                                               |
| 12      | **Tình huống khó khăn nhất mà bạn có trong quá trình kiểm thử là gì? Khi gặp tình huống đó bạn giải quyết như thế nào?**                                                                                                                     | Tùy vào kinh nghiệm của ứng viên                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| 13      | **Theo bạn, một tester cần đến các kỹ năng nào?**                                                                                                                                                                                            | - Cẩn thận, chăm chỉ, tỉ mỉ và có trách nhiệm đối với đầu việc được giao <br>- Có khả năng phân tích dự án, biết xử lý và giải quyết vấn đề phát sinh trong quá trình làm việc. <br>- Luôn biết lắng nghe, học hỏi và tiếp thu các kiến thức cần thiết trong quá trình làm việc. <br>- Phải là người có tinh thần cầu tiến trong công việc, sẵn sàng làm thêm ngoài giờ khi được cấp trên yêu cầu.                                                                                                                |
