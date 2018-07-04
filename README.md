# MetaDescription

## Làm thế nào để viết các thẻ Meta Descriptions trong 1 Thế Giới liên Tục Thay Đổi (AKA Google Giveth, Google Taketh Away)

Quay trở về thời điểm tháng 12 nằm 2017, Google đã có 1 sự thay đổi rất lớn về cách hiển thị các đoạn trích tìm kiếm (snippet), mà qua tìm hiểu của chúng tôi đã phát hiện ra rằng nó hiện thị rất nhiều đoạn trích hơn 300 kí tự. Nhưng vào cuối tuần, dường như họ lại roll back những thay đổi đó ( DannyDanny Sullivan đã phần nào xác nhận điều này trên Twitter vào ngày 14 tháng 5). Bên cạnh câu hỏi trước - Vậy đâu là giới hạn mới cho 1 snippet? - điều này có thể sẽ khiến bạn bối rối không biết phải làm thế nào khi mà luật thì luôn luôn thay đổi. Không ai trong chúng tôi có câu trả lời chính xác cả, nhưng tôiôi sẽ thử trả lời cả 2 câu hỏi dựa trên những gì tôi biết ngay bây giờ.

## Lies, dirty lies, and statistics...

Tôi đã lấy về tất cả các đoạn trích có thể tìm kiếm được từ MozCast(trang 1 kết qủa Google cho 10000 từ khóa), vì đây là 1 tập dữ liệu chúng tôi thu thập hàng ngày và có lịch sử lâu đời. Có 89383 đoạn trích được hiển thị trên tập dữ liệu lúc sáng ngày 15 tháng 5.

Có thể nói rằng, suốt toàn bộ tập dữ liệu, độ dài tối thiểu là 6 kí tự, độ dài tối đa là 386, và độ dài trung bình là 159. Điều này không được hữu dụng lắm, vì 2 lý do. Đầu tiên, việc khuyên bạn viết thẻ meta description trong khoảng 6*386 kí tự không thực sự là 1 lời khuyên có ích. Thứ hai,  chúng tôi đang giải quyết nhiều vấn đề cực điểm. Ví dụ, đây là 1 đoạn trích trong trang tìm kiếm từ khóa "USMC".

Marine Corps Community Services có thể là 1 tổ chức tuyệt vời, nhưng tôi rất xin lỗi phải thông báo rằng thẻ meta description của họ, sự thật là, 'apple' (mà tôi nghĩ rằng chính Google đã tự thêm đoạn này vào). Đây là 1 đoạn trích cho việc tìm kiểm của cửa h "Youngkers": .

Đặt trong những những bối rối của họ, tôi nghĩ rằng chúng ta có thể đều đồng ý rằng "BER META TAG1" là không tối ưu. Trường hợp này nếu có cũng chỉ dạy cho bạn những thứ không nên làm mà thôi. Vậy còn chiều ngược lại thì sao? Đây là đoạn trích với 386 kí tự, khi tìm kiếm từ khóa "non-compete agreement":

Để ý cụm từ "Jump to Excptions" và các liên kết ở đầu. Chúng được Google thêm vào, vì vậy rất khó để nói những thứ nào sẽ ảnh hưởng đến bộ đếm số lượng các kí tự. Đây là 1 ví dụ mà không tính các phần bổ sung thì có đúng 370 kí tự, khi tìm kiếm từ khóa "the Hunger Games books":

Vì vậy, chúng tôi biết rằng những đoạn trích dài hơn cũng vẫn tồn tại. Lưu ý rặng, mặc dù, cả 2 đoạn trích này từ Wikipedia, là 1 ngoại lệ với rất nhiều luật SEO. Có hay không những đoạn mô tả dài chỉ những trường hợp rìa? Xem xét những khoảng giữa ( hay thậm chí tính trung bình trong trường hợp này) cũng không cho ta biết điều gi cả.

## Tổng quan vấn đề, phần 1
Đôi khi, bạn phải để cho dữ liệu tự lên tiếng, với 1 chút dỗ dành. Hãy nhìn vào tất cả các đoạn trích được rút ngắn (kết thúc bằng dấu "...") và loại bỏ các kết quả video ( chúng ta đã biết từ nghiên cứu trước là những loại này có phần ngắn hơn). Nó bao gồm 42863 đoạn trích ( chỉ bằng 1 nửa tập dữ liệu của chúng tôi). Đây là biểu đồ của tất cả các chiều dài được rút ngắn, gom nhóm vào các khoảng 25 kí tự (0–25, 26–50, vân vân.):

Nó trông rất khác so với dữ liệu của chúng tôi vào tháng 12 năm ngoài, và tập trung trong khoảng 150-175. Chúng tôi thấy 1 ít đoạn trích hiển thị Google được rút ngắn sau khoảng 300, những chúng đều được làm ngắn bởi các công cụ rút gọn hơn nữa.

##  Tổng quan vấn đề, phần 2
Rõ ràng sẽ có rất nhiều thứ xả ra trong khoảng 125-175 kí tự, vật hãy tập trung và nhìn vào khoảng giữa của phân phối xác suất, rồi chia thành các phần nhỏ hơn, mỗi phần 5 kí tự:

Chúng ta có thể thấy rõ ràng là phần lớn rút gọn nằm trong khoảng 145-165 kí tự. Trước tháng 12, định hướng viết meta description của chúng tôi là để chúng trong khoảng dưới 155 kí tự,  do vậy dường như là Google hầu như đã quay về những luật cũ.

Hãy nhớ rằng google sử dụng các mức tương đối thôi, vì vậy sẽ không có những giới hạn kí tự cụ thể. 1 vài người giả định về 1 giới hạn độ rộng pixel, như với các tag tiêu đề, nhưng tôi nhận ra rằng sẽ khó khăn để in các đoạn trích nhiều dòng (thậm chí ở mobile thì còn khó khăn hơn). Thực tế thì cũng khó để viết 1 giới hạn pixel. Do vậy gợi ý dữ liệu 155 kí tự là xấp xỉ hợp lý.

## To the Wayback Machine... ?!
Chúng ta có nên rút gọn về 155 kí tự hay không? Nếu bạn đã viết những đoạn meta description dài hơn, bạn có nên bỏ nó và bắt đầu lại? Sự thật là không ai trong chúng ta có thể biết cái gì sẽ xảy ra tuần tới. Theo góc nhìn của tôi, có 4 tùy chọn có vẻ khả thi:

#### (1) Hãy đễ Google giải quyết nó
1 vài trang hoàn toàn không có meta description. Wikipedia là 1 trong số đó. Hiện giờ Google hiểu nội dụng của Wikipedia nhiều hơn hầu hết các trang khác ( nhờ 1 phần Wikidata), nhưng nhiều trang vẫn ổn mà không có tag. Nếu lựa chọn của bạn là viết các tag dở tệ, lặp đi lặp lại hay là để trống, thì tôi nghĩ nên để trống và để Google sắp xếp chúng

#### (2) Cứ để ... xuất hiện khi cần thiết
Bạn có thể chỉ cần viết đủ độ dài mà bạn nghĩ là lý tưởng cho bất kỳ trang nào (miễn là trong giới hạn), và nếu đoạn trích bị cắt ngắn, đừng lo lắng. Có thể dấu chẩm lửng (...)  được thêm vào vì lí do gì đó thôi. Đùa 1 chút, nhưng sự thật là việc rút gọn không phải là 1 sự thất bại. 1 mô tả tốt nên khiến mọi người muốn đọc thêm.

#### (3) Tách mọi thứ về 155 kí tự
Bạn có thể trở về mà chuyển mọi thứ của bạn về 155 kí tự. Tôi nghĩ rằng nhìn chung đây sẽ là  1 khoảng tời gian tồi tệ và kết quả có thể thậm chí còn là những đoạn trích dẫn tìm kiếm tệ hơn. Nếu bạn muốn viết Meta Descriptions ngắn hơn cho hầu hết những trang quan trọng của bạn, nó cực kỳ hợp lý, nhưng hãy nhớ rằng 1 vài kết quả vẫn sẽ hiển thị những đoạn trích dài hơn và những trường hợp này cẩn được tiếp tục cải thiện

#### (4) Viết các đoạn mô tả có chiều dài thích hợp.
Liệu chúng ta có thể viết 1 đoạn mô tả thể hiện tốt tại nhiều độ dài không?Tôi nghĩ hoàn toàn có thể, chỉ cần để ý và lên kế hoạch 1 chút. Tôi không gợi ý điều này cho mỗi trang, nhưng có thể có 1 cách để có chiếc bánh của chúng ta và chỉ ăn 1 nửa chúng thôi.

## hướng tới 150/150
Tôi đã bị ảm ảnh bởi cách viết "kim tự tháp ngược" gần đây. Đây là 1 cách viết mà bạn bắt đầu bằng việc dẫn dắt hay tổng kết các ý chính rồi sau đó đi sâu vào chi tiết, dữ liệu và hoàn cảnh. Khi mà mục tiêu này phù hợp với trang web, bản chất của nó là sự giới hạn bố cục khi in ra. Bạn không bao giờ biết khi nào trình soạn thảo sẽ cắt ngắn tiêu đề của bạn để khít với khoảng trống thích hợp, vì vậy phong cách kim tự tháp ngược giúp đảm bảo phần quan trọng nhất sẽ luôn không bị cắt.

Sẽ thế nào nếu chúng ta mang cách tiếp cận này cho meta descriptions? Nói cách khác, tại sao không viết 1 cụm 150 kí tự "dẫn dắt" để tóm tắt trang, và thêm 150 kí tự sau cần thiết nhưng ít chi tiết quan trọng hơn ( khi thêm các chi tiết đó có ý nghĩa và cung cấp giá trị)? Quy tắc 150/150 không phải 1 con số ma thuật nào - bạn có thể thậm chí thực hiện 100/100 hay 100/200. Quan trọng phải đảm bảo rằng chứ phía trước đoạn cắt có thể đứng độc lập.

Nghĩ về nó 1 chút như 1 đoạn viết tắt, với 2 dòng sao chép riêng biệt. Lấy ví dụ với bài post blog này:

#### Dòng 1 (145 chars.)
Vào tháng 12, chúng tôi đã báo cáo rằng Google tăng các đoạn trích dẫn tìm kiếm lên hơn 300 kí tự. Không may, dường như luật lại thay đổi 1 lần nữa.

#### Dòng 2 (122 chars.)

Dựa theo nghiên cứu mới của chúng tôi gần đây ( tháng 5 2018), giới hạn lại trở về 155-160 kí tự. Vậy những người làm SEO phải thích ứng thế nào với những thay đổi này?

Dòng 1 là 1 phiên bản ngắn hơn của câu chuyện và hi vọng những người tìm kiếm biết rằng họ đang tìm thấy đúng nơi họ cần. Dòng 2 đưa thêm 1 vài chi tiết và đưa ra vừa dủ dữ liệu (hi vọng là thế) để hấp dẫn hơ. Nếu Google sử dụng đoạn mô tả dài hơn, sẽ rất tốt, nhưng nếu không, thì cũng sẽ không tệ hơn là mấy.

## bạn có nên cảm thấy khó chịu?
Những nỗ lực này có đáng không? tôi nghĩ rằng việc viết 1 đoạn mô tả hiệu quả cho khách hàng tìm kiếm vẫn rất quan trọng, theo lý thuyết à vậy ( và điều này gián tiếp ảnh hưởng đến thứ hạng nữa), những bạn có thể thấy rằng bạn có thể viết cực tốt trong giới hạn 155 kí tự. Chúng tôi cũng đã đối mặt với thực tế là Google dường như đang ngày càng viết lại nhiều mô tả hơn. Điều này rất khó để đo đếm, vì đa số chỉ 1 phần được viết lại thôi, nhưng không có gì đảm bảo meta description sẽ không được sử dụng để viết lại.

Có cách nào để biết khi 1 đoạn trích dài hơn (>300 kí tự) sẽ được sử dụng không? 1 vài nhà làm SEO đã giả định 1 đường dẫn trong các đoạn trích dài hơn và các đoạn trích tính năng tại đầu trang. Trong toàn bộ tập dữ liệu của chúng tôi, 13.3% các SERPs có các đoạn trích tính năng. Nếu chúng tôi chỉ nhìn vào các SERP với độ dài đoạn trích tối đa 160 kí tự ( ví dụ không có kết quả nào lớn hơn 160 kí tự), các đoạn trích tính năng  xuất hiện khoảng 11.4%. Nếu chúng tôi xem các SERP với ít nhất 1 đoạn trích hiển thị trên 300 kí tự, các đoạn trích tính năng xuất hiện với tỉ lệ 41.8%. Khi tập dữ liệu thứ 2 nhỏ hơn 1 chút, lại có sự khác biệt nổi bật. Dường như không có sự liên hệ nào giữa khả năng trích xuất các câu trả lời trong form của các trích dẫn tính năng và khả năng sẵn sàng hiển thị các đoạn trích dài của Google. Trong nhiều trường hợp, mặc dù các đoạn trích dài được viết lại  hay lấy trực tiế từ trang đi nữa, không có gì đảm bảo sau đó google sẽ sử dụng các đoạn meta description dài của bản cả.

Bấy giờ, dường như là viết nội dung trong 155 kí tự là phù hợp. Nếu bạn đã tăng độ dài 1 vài  meta descriptions của bạn, tôi không nghĩ có bất cứ lý do nào để phải hoảng loạn cả. Có thể sẽ có vấn đề khi viết lại những đoạn mô tả quá dài trên các trang quan trọng, đặc biệt nếu đoạn cắt ngắn dấn đến các kết quả không tốt. Nếu bạn lựa chọn viết lại 1 vài đoạn mô tả, cân nhắc luật 150/150 - ít nhất sau đó bạn sẽ có 1 tương lai ổn hơn .  
