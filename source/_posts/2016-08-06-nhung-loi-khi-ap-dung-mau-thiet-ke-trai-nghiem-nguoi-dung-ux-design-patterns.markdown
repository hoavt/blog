---
layout: post
title: "Những lỗi khi áp dụng mẫu thiết kế trải nghiệm người dùng (UX design patterns)"
author: phuonglm
date: 2016-08-06 04:40
comments: true
categories:
    - "vi"
    - "trans"
tags:
    - "ux"
    - "mobile"
    - "design"
cover: /images/2016/08/06/youtube-nav-change.png
description: Nhiều khi áp dụng rập khuôn theo những mẫu thiết kế không đem lại kết quả tốt như bạn nghĩ.
keywords: UX, mobile, design
published: true
---

Nếu bạn là một nhà thiết kế có kinh nghiệm, bạn nên hiểu rằng trong  thiết kế giao diện người dùng [^1] , việc lấy cảm hứng từ những sản phẩm của người khác không phải là ăn cắp ý tưởng mà là việc học hỏi những kinh nghiệm tốt nhất của những người đi trước, là sử dụng những mẫu thiết kế và làm theo các chỉ dẫn (guideline) nhằm đảm bảo sử dụng các kiểu mẫu quen thuộc và tạo nên các giao diện thực sự hữu ích cho người dùng.

Một số người nói rằng việc cứ bám theo các quy tắc cứng nhắc và bắt chước người khác thì sẽ giết chết sự sáng tạo và rồi cuối cùng mọi ứng dụng sẽ có thiết kế giống nhau. Theo quan điểm của người thiết kế UX (trải nghiệm người dùng) tôi lại thấy một vấn đề khác. Việc quen áp dụng các cách khuyên dùng tốt nhất có thể khiến bạn tin rằng Google/Facebook/Instagram hay các ứng dụng khác luôn đúng, mục tiêu thiết kế của họ cũng giống của bạn nên bạn sẽ không bao giờ tự hỏi “có gì sai ở đây?!”. Để chứng minh điều này dưới đây là một số mẫu thiết kế (hoặc đã từng) được coi là những mẫu thiết kế tốt nhất nhưng rút cuộc nó lại không thực sự tốt như bạn nghĩ.

<!-- more -->

### 1. Ẩn menu điều hướng [^2]

Ít nhất cũng có đến nửa triệu bài báo chủ yếu được viết bởi các designer tranh cãi về menu dạng hamburger (☰) Nếu bạn đã bỏ lỡ chúng thì hãy đọc [ở đây](http://techcrunch.com/2014/05/24/before-the-hamburger-button-kills-you/) và [ở đây](http://deep.design/the-hamburger-menu/). Các bài viết ấy thường không bàn cãi về việc sử dụng biểu tượng hamburger mà đó là về việc có nên ẩn các menu điều hướng và hiển thị nó khi người dùng nhấn vào biểu tượng hamburger.
Ban đầu thì việc ẩn hàng loạt menu điều hướng đằng sau nút hamburger này có vẻ như rất tiện lợi cho người thiết kế - bạn không phải lo lắng về việc màn hình bị chiếm diện tích bởi những menu cha con dài trên màn hình quá nhỏ của thiết bị di động, mọi thứ sẽ được ẩn một cách mặc định và chỉ hiện ra khi người dùng muốn.
Tuy nhiên các thực nghiệm lại chỉ ra rằng việc hiển thị menu điều hướng thường trực trên màn hình lại tăng khả năng tương tác giữa người dùng và ứng dụng, làm người dùng hài lòng hơn và thậm chí còn tăng doanh thu từ ứng dụng. Đó là lý do vì sao các ứng dụng lớn đang dần thay đồi bằng cách bỏ đi nút hamburger và quay lại hiển thị những tính năng hay được sử dụng ngay trên màn hình.

{% img center /images/2016/08/06/youtube-nav-change.png Menu điều hướng của Youtube %}

-> Sự thay đổi menu điều hướng của Youtube - Luke Wroblewski <-

### 2. Lạm dụng icon.

Khi thiết kế trên màn hình nhỏ đôi lúc bạn quá lạm dụng việc thay thế các nhãn bằng các icon. Bạn có thể có nhiều lý do để dùng icon như chúng chiếm ít không gian hơn, bạn không phải lo lắng về việc màn hình bị xô lệch khi được dịch sang ngôn ngữ khác hay với ý nghĩ rằng người dùng đã rất quen với icon này rồi.

Với kiểu suy nghĩ như vậy các bảng thiết kế nhiều khi vô tình giấu đi các tính năng của chương trình đằng sau những icon khó hiểu hoặc đôi lúc mình cũng chẳng biết là cái gì nữa và dưới đây là một ví dụ: 

{% img center /images/2016/08/06/instagram-bad-icon.png Icon khó hiểu của Instagram %}

-> Liệu bạn có đoán được icon này trong Instagram là để gửi tin nhắn không! <-

{% img center /images/2016/08/06/google-trans-bad-icon.png Icon Khó hiểu trên Google Translate %}

-> Hay icon này trong Google Translate dùng để làm gì? <-

Sẽ là sai lầm khi bạn nghĩ rằng người dùng đã quen với việc dùng những icon trừu tượng như thế này hay bá đạo hơn là nghĩ rằng họ sẽ tò mò mà bỏ thời gian ra tìm hiểu xem nó là cái gì.

{% img center /images/2016/08/06/bloom-fm-bad-icon.png Icon khó hiểu trong Bloom.fm %}

-> Một số icon của Bloom.fm mà thật mình cũng chẳng hiểu nó dùng để làm gì! <-

Nếu bạn là người thiết kế một icon và bạn cảm thấy sản phẩm của mình cần nhãn để người khác có thể hiểu được thì sản phẩm của bạn thật sự có vấn đề, kể cả khi người dùng sẵn sàng thử để hiểu về nó.

Điều này không có nghĩa là bạn không nên dùng icon, thật sự thì có rất nhiều icon mà người dùng đã quen thuộc và phần lớn những chức năng quen thuộc của một ứng dụng đều đã có icon tương ứng ( tìm kiếm, phát video, email, cài đặt... ). Tuy vậy vẫn có nhiều icon khá là mơ hồ đối với người dùng vì mỗi ứng dụng sẽ có hành vi khác nhau một chút trên cùng một chức năng (ví dụ như sẽ có chuyện gì xảy ra nếu ta nhấn vào nút trái tim nhỉ (yêu thích, đánh dấu) ??? ).

{% img center /images/2016/08/06/another-example-heart.png đôi lúc thật khó để biết icon quen thuộc thật sự sẽ làm gì %}

Với những tính năng không quen thuộc và phức tạp thì bạn nên sử dụng icon kèm theo nhãn đầy đủ, nhãn sẽ giúp tính năng của bạn rõ ràng hơn và icon sẽ giúp người dùng nhận dạng tính năng nhanh hơn và đem lại một chút cá tính cho ứng dụng của bạn.

{% img center /images/2016/08/06/complicate-action-should-have-label.png %}

-> Một ví dụ trong ứng dụng Pixelmator. <-

### 3. Chuyển hướng dựa vào cử chỉ [^3]

Khi Apple giới thiệu iPhone vào năm 2007, công nghệ cảm ứng đa điểm đã thu hút sự chú ý của ngưới dùng và họ thấy rằng không những có thể chạm và nhấn vào giao diện mà còn có thể phóng to, thu nhỏ và vuốt.

Tương tác dùng cảm ứng đã trở nên quen thuộc hơn với người thiết kế giao diện và đã có nhiều ứng dụng được thử nghiệm sử dụng nhận dạng cử chỉ đa điểm để tương tác.

{% img center /images/2016/08/06/clear-app-gestures.jpg %}

-> Chuyển hướng dựa vào cử chỉ trong ứng dụng Clear. <-

Cũng giống như trường hợp giấu điều hướng và lạm dụng các icon thay vì dùng nhãn văn bản, đôi khi các nhà thiết kế cũng bị cuốn vào việc sử dụng cử chỉ để tiết kiệm không gian màn hình ( Một khi không có biểu tượng nào thể hiện việc bạn có thể vuốt sang trái để xóa thì người dùng chẳng có cách nào để biết là nó tồn tại ). Và cũng như vấn đề về hamburger menu, tính năng nào bị giấu đi thì sẽ ít người dùng nó. Thêm nữa là phần lớn nhận dạng cử chỉ chưa được chuẩn hóa trên các ứng dụng khác nhau, đơn cử là ứng dụng email nổi tiếng cũng hành xử khá là khác nhau đối với việc bạn vuốt sang phải trên mỗi email.

{% img center /images/2016/08/06/apple-mail-gestures.png vuốt sang phải trên Apple mail %}

-> Với Apple mail vuốt sang phải sẽ hiện ra tùy chọn Đánh dấu chưa đọc. <-

{% img center /images/2016/08/06/gmail-gestures.png vuốt sang phải trên Gmail %}

-> Trong khi đó với ứng dụng Gmail thì vuốt sang phải sẽ là chuyển email sang mục lưu trữ. <-

Vậy nên hãy nhớ rằng những tính năng sử dụng nhận dạng cử chỉ là tính năng ẩn và điều đó khiến cho người dùng mất nhiều công sức để ghi nhớ - có may mắn lắm thì bạn mới có thể dạy cho cả thế giới biết vuốt sang phải có nghĩa là gì.

### 4. Giới thiệu tính năng mới trực quan trên màn hình cho người dùng mới

Onboarding, đang là chủ đề nóng trong việc thiết kế giao diện. Tính năng này tự động chạy chỉ dùng một lần khi người dùng lần đầu tiên mở dụng dụng. Phần lớn tính năng này được dùng để giới thiệu và giải thích các tính năng của chương trình một cách trực quan trên màn hình:

{% img center /images/2016/08/06/onboarding-overlay.png %}

-> Một ví dụ về Onboarding <-

Nhìn thì hay nhưng thật ra thì đây là một giải pháp khá tệ đấy. Bởi vì nhiều người đôi lúc sẽ bỏ qua phần giới thiệu của bạn, họ đang muốn sử dụng ứng dụng của bạn ngay cơ mà. Thậm chí nếu họ dành thời gian xem hướng dẫn của bạn thì họ cũng sẽ nhanh chóng quên mọi thứ ngay khi đóng cửa sổ hướng dẫn đó lại. (đặc biệt là với màn hình hướng dẫn có quá nhiều thông tin). Và cuối cùng là, nếu bạn phải giải thích giao diện của mình với người dùng thì điều đó đồng nghĩa rằng giao diện bạn đang có trên ứng dụng thật sự đang có vấn đề.

{% img center /images/2016/08/06/ux-design-like-make-a-joke.jpg Thiết kế giao diện giống như bạn đang kể truyện cười. Nếu bạn phải giải thích câu chuyện thì chẳng còn gì hay nữa. %}

-> Việc thiết kế giao diện giống như bạn đang kể truyện cười. Nếu bạn phải giải thích câu chuyện thì chẳng còn gì hay nữa. <-

Onboarding có thể được thiết kế theo nhiều cách khác nhau để trở nên hữu ích hơn đối với người dùng. Như với Slack, màn hình chào của họ tập trung việc giới thiệu khái quát về lợi ích mang lại hơn là giới thiệu chi tiết về các tính năng.

{% img center /images/2016/08/06/slack-onboarding.png Slack sử màn hình chào của họ tập trung việc giới thiệu khái quát về lợi ích mang lại hơn là giới thiệu chi tiết về các tính năng %}

Duolingo thì biến Onboarding thành các bài học và cổ vũ người dùng học các bài học đấy. Hướng tiếp cận này cũng giúp người dùng quen dần và hiểu hơn các tính năng/ giá trị của ứng dụng.

{% img center /images/2016/08/06/duolingo-onboarding.jpg Duolingo thì biến Onboarding thành các bài học và cổ vũ người dùng học các bài học đấy %}

Bạn còn nhớ vấn đề khác nhau giữa Mailbox và AppleMail khi dùng tính năng vuốt sang phải qua email? Đây là cách hướng dẫn người dùng mới về tính năng đó: Người dùng sẽ cần xem những cử chỉ đó được thực hiện như thế nào/ở đâu trước khi thực sự bắt đầu sử dụng ứng dụng:

{% img center /images/2016/08/06/apple-mail-onboarding-tutor.png %}

Trước khi áp dụng rập khuôn sử dụng Onboarding bằng cách tạo một lớp trong suốt trên chính ứng dụng của mình để giới thiệu các tính năng và hướng dẫn cho người dùng mới, hãy nên dừng lại và thử nghĩ xem liệu người dùng nên được chào đón như thế nào cho hợp lý và bạn sẽ thấy có nhiều cách giải quyết khác hay hơn việc rập khuôn lại từ ứng dụng khác.

### 5. Sử dụng màn hình trống

Màn hình trống đôi lúc là một thứ dễ bị bỏ sót bởi các nhân viên thiết kế thiếu kinh nghiệm, tuy nhiên nó là một phần quan trong trong thiết kế ứng dụng của bạn.

Đôi khi bạn nghĩ rằng trang báo lỗi hay màn mình trống là cơ hội tốt để thể hiện tính sáng tạo của mình nhưng thực ra lại không như vậy.

Hãy xem ví dụ dưới đây của Google photos:

{% img center /images/2016/08/06/gphoto-empty-state.png Màn hình trống trên GPhoto %}

Nhìn qua thì có vẻ ổn nhưng hãy thử nhìn lại màn hình bạn sẽ thấy có một số vấn đề ở đây:

* Tại sao lại có nút tìm kiếm trong khi người dùng chưa tạo cái gì cả?

* Tại sao hình ảnh chính trong màn hình này lại không có phản ứng gì khi tôi chạm vào?

* Gợi ý ở màn hình trên bảo rằng "bạn có thể tạo nội dung bằng cách sử dụng nút + ở phía trên màn hình" và điều đó thật là vụng về, bản thân cái gợi ý ở trên nên tự bao gồm nút để tạo nội dung luôn nhỉ?

Và như thế màn hình trống này không làm cho việc sử dụng ứng dụng dễ dàng hơn, nó không giúp người dùng hiểu rõ hơn về ứng dụng của bạn.

Màn hình trống sẽ làm mọi thứ dễ dàng hơn nếu nó thiết kế theo kiểu như dưới đây.

{% img center /images/2016/08/06/empty-state-good-example.png Một ví dụ về màn hình trống tốt %}

Đừng quên rằng màn hình trống (tương tự như các trang 404 trên web) không chỉ là nơi thể hiện khả năng sáng tạo và đặc tính thương hiệu mà còn có vai trò quan trọng hơn để thể hiện tính năng của chương trình. Vì vậy hãy làm cho màn hình trống trở nên trực quan hơn.

### 6. Hãy luôn tự hỏi mọi thứ

Những điều tôi chia sẽ ở đây không phải là để chỉ trích các mẫu thiết kế hay các thực nghiệm tốt nhất. Hãy nhớ rằng các mẫu thiết kế trên các ứng dụng nổi tiếng đôi lúc có đối tượng người dùng khác với ứng dụng mà bạn tạo và điều đó có nghĩa rằng không có chìa khóa vàng chung cho tất cả mọi thứ. Vì thế hay tự nghiên cứu để tạo nên một thiết kế riêng cho mình, mọi thứ cần phải được đo đếm và kiểm thử để rút ra cách giải quyết tốt nhất cho ứng dụng của mình.

[^1]: UI
[^2]: Navigation menu
[^3]: Gesture based navigation

Lược dịch từ [Misused mobile UX patterns](https://medium.com/@kollinz/misused-mobile-ux-patterns-84d2b6930570)

