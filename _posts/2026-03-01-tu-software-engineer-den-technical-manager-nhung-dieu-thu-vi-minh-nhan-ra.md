---
layout: post
title: "Từ Software Engineer đến Technical Manager: Những điều thú vị mình nhận ra."
date: 2026-03-01
last_modified_at: 2026-03-28
categories: [Leadership, Engineering]
tags: [engineering-leadership, trade-offs, mindset, career-growth, delegation]
image: /assets/img/posts/2026-03-01/cover.jpg
---

Sau nhiều năm làm việc với những dòng code, kinh qua vài hệ thống từ lúc nó còn sơ khai đến khi phình to ra và hành trình từ một **Software Engineer** bước sang vai trò **Technical Manager** với mình là một chặng đường đầy những **"breaking changes"**. 

Nó không đơn thuần là việc thay đổi chức danh hay mở rộng phạm vi công việc. Đó là quá trình tái cấu trúc lại những thói quen và tư duy cốt lõi đã từng giúp mình thành công ở vai trò trước đây. 

Qua những lần tự loay hoay định vị lại bản thân ở vai trò mới, khi không còn dành nhiều giờ mỗi ngày để "cắm mặt" vào IDE mà lùi lại để nhìn bức tranh tổng thể về **kiến trúc**, **con người** và **quy trình**, mình nhận ra vài điều khá thú vị, thậm chí là trái ngược với những gì mình đã từng tin tưởng. 

## 1. Code là "tài sản" nhưng cũng là "tiêu sản"

Khi còn là một kỹ sư chuyên trách, niềm vui mỗi ngày của mình thường xoay quanh việc thiết kế ra những cấu trúc dữ liệu tối ưu, áp dụng  được nhiều design pattern hay hoàn thiện những tính năng lõi. Ở góc nhìn đó, mỗi dòng code được đẩy lên repository giống như một viên gạch xây nên **"tài sản"** của hệ thống và khẳng định năng lực của người viết.

Tuy nhiên, khi đứng ở vị trí quản lý vòng đời của một sản phẩm dài hạn, mình nhận ra code có một "nhân cách" kép: 

> **Mỗi dòng code là một tính năng hôm nay**    
> **và một chi phí bảo trì ngày mai.**

Mỗi một tính năng mới được merge vào nhánh chính đồng nghĩa với việc team sẽ có thêm một **"tiêu sản"**, tốn nguồn lực để duy trì: từ việc testing, giám sát hiệu năng, cập nhật thư viện bảo mật hoặc các edge case phát sinh trong tương lai. Hệ thống càng nhiều code, độ cồng kềnh về logic càng lớn, dẫn tới các rủi ro và sai sót càng dễ phát sinh.

Nhưng khi sản phẩm lớn lên, sự phức tạp của hệ thống là điều khó tránh khỏi. Việc tối ưu giá trị **tài sản** và tiết giảm gánh nặng **tiêu sản** cho code trước những áp lực về yêu cầu **tăng trưởng nóng** của nghiệp vụ luôn là một thử thách cực kỳ lớn và khó khăn cho bất kỳ một người quản lý nào. 

Đó là biết **khi nào nên dừng lại** thay vì tiếp tục đắp thêm logic vào hệ thống, là sự dũng cảm khi dám bước ra khỏi vùng an toàn để thay đổi những cấu trúc cũ kỹ lỗi thời, là bản lĩnh để thực hiện những cuộc "thanh lọc" hệ thống đầy đau đớn. Hay cả những cuộc tranh luận nảy lửa để phản biện lại những luồng nghiệp vụ phức tạp nhưng chưa đủ giá trị từ phía Product và Business.

Và sẽ có những giai đoạn cả team phải **“gồng mình”** vừa phát triển tính năng, vừa nâng cấp hệ thống. Nhưng những nỗ lực đó không hề lãng phí, mình tin rằng:

> **Hệ thống càng ít tiêu sản,**  
> **team càng có nhiều không gian để tạo ra tài sản.**

## 2. Giá trị của mình là phép "nhân", không còn là phép "cộng"

Ngày trước, để biết hôm nay làm việc có hiệu quả không, mình hay dùng phép cộng đơn giản là hoàn thành được 3 cái ticket, fix xong 2 con bug khét lẹt, support được 1 bạn junior. Cứ cộng dồn lại là thấy vui, thấy mình có giá trị với công ty.

Thời gian đầu chuyển sang làm quản lý, theo quán tính, mình vẫn giữ cách làm việc đó. Khi dự án gặp điểm nghẽn hoặc có một module quá khó, bản năng của một người làm kỹ thuật thôi thúc mình xắn tay vào code trực tiếp với suy nghĩ: *"Mình tự làm sẽ nhanh và kiểm soát rủi ro tốt hơn"*. Nhưng hậu quả là mình tự biến bản thân thành **nút thắt cổ chai** của luồng công việc, còn các thành viên trong team thì mất đi cơ hội cọ xát để nâng cao năng lực.

Rồi dần dần, mình phải học cách từ bỏ niềm vui tức thời của việc tự tay giải quyết xong một đoạn logic khó, để làm quen với niềm vui âm thầm hơn khi nhìn thấy member trong team tự mình vượt qua giới hạn của họ.

> **Software Engineer scale bằng kỹ năng.**  
> **Technical Manager scale bằng con người và hệ thống.**

Một hệ thống lớn không thể được gánh vác bởi một vài cá nhân xuất chúng. Và giá trị thực sự của một người quản lý là nằm ở **phép nhân**, thông qua việc tạo ra các **điểm tựa kỹ thuật** để nâng hiệu suất của cả đội ngũ lên một tầm cao mới:

* **Nhân bằng Kiến trúc**: Thay vì chỉ code xong tính năng, mình định hình một kiến trúc **"modular hóa"** tốt từ đầu, giảm phụ thuộc giúp tốc độ phát triển của team không bị chậm lại khi hệ thống phình to. Hay **"common hoá"**, team không còn tốn thời gian "xây lại bánh xe bò". Rủi ro giảm xuống vì logic chỉ nằm ở một chỗ (Single Source of Truth), dễ quản lý, dễ bảo trì và cập nhật đồng bộ cho toàn hệ thống chỉ với một lần thay đổi. Đây chính là cách nhân năng suất của n dự án mà không cần gấp n nhân sự.

* **Nhân bằng Con người**: Dành 1 giờ để code hộ một bạn Junior chỉ mang lại kết quả của 1 giờ lao động. Nhưng dành 1 giờ đó để hướng dẫn bạn ấy phương pháp tư duy và debug, bạn đã tạo ra một "máy giải quyết vấn đề" có thể chạy độc lập suốt nhiều giờ về sau. Khi mình tập trung vào việc khơi thông rào cản và nâng tầm đội ngũ, mình đang tạo ra một bộ máy có sức mạnh tổng thể vượt xa khả năng của bất kỳ cá nhân xuất chúng nào.

* **Nhân bằng Quy trình**: Nếu xem mỗi tính năng là một chiếc xe, thì quy trình chính là con đường. Thay vì với vai trò trước đây mình sẽ trực tiếp cầm lái từng chiếc, còn giờ thì mình tập trung vào việc "xây dựng xa lộ" với:

    * **Automation (Công nghệ an toàn)**: CI/CD không chỉ để nhanh, mà là thiết lập một bộ lọc rủi ro tự động ngay từ cửa ngõ. Khi việc kiểm thử và triển khai thoát khỏi sự phụ thuộc vào các thao tác thủ công và nhiều rủi ro từ con người, chúng ta có thể "nhấn ga" tăng tốc độ phát triển mà không phải đánh đổi bằng sự an toàn và ổn định của hệ thống.

    * **Observability (Hệ thống chỉ báo)**: Thay vì chờ "tai nạn" (User phàn nàn), mình xây dựng cơ chế để hệ thống tự kể chuyện qua Monitoring và Alerting. Điều này giúp team chuyển từ thế bị động sang chủ động xử lý sự cố ngay từ khi còn là mầm mống.

    * **Standardization (Luật giao thông)**: Khi coding convention, package structure, design patterns hay thậm chí tiêu chí lựa chọn công nghệ được chuẩn hóa rõ ràng, team sẽ giảm đáng kể "cognitive load". Kỹ sư không còn phải tốn năng lượng cho những tranh luận lặt vặt về cách tổ chức code, cách ra quyết định hay những yếu tố ngoại vi, mà có thể dồn toàn bộ sự tập trung vào việc giải quyết các bài toán chính.

## 3. Delegate: Nghe đơn giản nhưng buông tay không hề dễ

*"Để đó anh làm luôn cho nhanh"* có lẽ là cái bẫy kinh điển nhất và cũng là "liều thuốc độc" êm ái nhất đối với những người quản lý đi lên từ chuyên môn. Chúng ta thường thiếu kiên nhẫn khi phải giải thích một vấn đề mà mình đã nắm quá rõ.

Thời gian đầu, mình thường rơi vào trạng thái sốt ruột khi thấy một bạn member loay hoay cả buổi với một bug mà mình thấy nó cũng không phức tạp lắm. Bản năng "anh hùng" thôi thúc mình nhảy vào "giành lấy bàn phím". Nhưng sau vài lần như vậy, mình nhận ra một sự thật phũ phàng: 

> **Nếu manager luôn giải quyết bài toán khó nhất,**   
> **team sẽ mãi chỉ giải được bài toán dễ nhất.**

Tuy nhiên, delegation cũng không đơn giản chỉ là "giao việc", không phải là việc assign một ticket trên Jira rồi mặc định người nhận sẽ tự biết cách hoàn thành. 

Cái khó của delegation là việc: 

* **Chuyển giao ngữ cảnh**: Mình phải học cách truyền đạt cực kỳ rõ ràng về **"What"** - chúng ta cần giải quyết bài toán gì và **"Why"** - tại sao nó lại quan trọng đối với business... Nhưng đồng thời, mình phải học cách giữ im lặng và lùi lại để team tự quyết định chữ **"How"** - thực thi nó như thế nào.

* **Kiểm soát rủi ro**: Delegate mà không có sự kiểm soát là phó mặc, nhưng kiểm soát quá chặt lại là "micromanagement". Mình phải học cách xây dựng những "tấm lưới an toàn" hay thiết lập các "vùng an toàn". Đó là các buổi review, là bộ quy chuẩn chung hoặc các kịch bản cần phải tính trước... Trong phạm vi an toàn đó, mình chấp nhận có thể để team "đi đường vòng", thậm chí là vấp ngã. Vì mình hiểu rằng: 

    > **Sự trưởng thành của một kỹ sư luôn**  
    > **tỷ lệ thuận với số lỗi lầm mà họ từng**  
    > **tự quyết định và tự tay khắc phục.**

* Và cuối cùng, **vượt qua ngưỡng "ngứa mắt" của bản thân**: Đây là bài tập tâm lý khó nhất. Sẽ có những lúc nói mãi nhưng giải pháp của team chỉ đạt 80% so với kỳ vọng thẩm mỹ kỹ thuật của mình. Nhưng nếu 80% đó vẫn chạy tốt, dễ bảo trì và quan trọng là giúp member trưởng thành lên 20%, thì đó là một sự đánh đổi hoàn toàn xứng đáng cho những bước đi trong dài hạn.

---

Technical Manager không phải là ngừng làm kỹ thuật.

> **Đó là chuyển từ việc tối ưu một đoạn code  
> sang tối ưu cả một hệ thống gồm kiến trúc, con người và quy trình.**