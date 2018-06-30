# MetaDescription

## Làm thế nào để viết các thẻ Metaeta Descriptions trong 1 Thế Giới liên Tục Thay Đổi (AKA Google Giveth, Google Taketh Away)

Quay trở về thời điểm tháng 12 nằm 2017, Google đã có 1 sự thay đổi rất lớn về cách hiển thị các đoạn trích tìm kiếm (snippet), mà qua tìm hiểu của chúng tôi đã phát hiện ra rằng nó hiện thị rất nhiều đoạn trích hơn 300 kí tự. Nhưng vào cuối tuần, dường như họ lại roll back những thay đổi đó ( DannyDanny Sullivan đã phần nào xác nhận điều này trên Twitter vào ngày 14 tháng 5). Bên cạnh câu hỏi trước - Vậy đâu là giới hạn mới cho 1 snippet? - điều này có thể sẽ khiến bạn bối rối không biết phải làm thế nào khi mà luật thì luôn luôn thay đổi. Không ai trong chúng tôi có câu trả lời chính xác cả, nhưng tôiôi sẽ thử trả lời cả 2 câu hỏi dựa trên những gì tôi biết ngay bây giờ.

## Lies, dirty lies, and statistics...

Tôi đã lấy về tất cả các đoạn trích có thể tìm kiếm được từ MozCast(trang 1 kết qủa Google cho 10000 từ khóa), vì đây là 1 tập dữ liệu chúng tôi thu thập hàng ngày và có lịch sử lâu đời. Có 89383 đoạn trích được hiển thị trên tập dữ liệu lúc sáng ngày 15 tháng 5.

Có thể nói rằng, suốt toàn bộ tập dữ liệu, độ dài tối thiểu là 6 kí tự, độ dài tối đa là 386, và độ dài trung bình là 159. Điều này không được hữu dụng lắm, vì 2 lý do. Đầu tiên, việc khuyên bạn viết thẻ meta description trong khoảng 6*386 kí tự không thực sự là 1 lời khuyên có ích. Thứ hai,  chúng tôi đang giải quyết nhiều vấn đề cực điểm. Ví dụ, đây là 1 đoạn trích trong trang tìm kiếm từ khóa "USMC".

Marine Corps Community Services có thể là 1 tổ chức tuyệt vời, nhưng tôi rất xin lỗi phải thông báo rằng thẻ meta description của họ, sự thật là, 'apple' (mà tôi nghĩ rằng chính Google đã tự thêm đoạn này vào). Đây là 1 đoạn trích cho việc tìm kiểm của cửa hiệu chúng cứ "Youngkers": .

Đặt trong những những bối rối của họ, tôi nghĩ rằng chúng ta có thể đều đồng ý rằng "BER META TAG1" là không tối ưu. Trường hợp này nếu có cũng chỉ dạy cho bạn những thứ không nên làm mà thôi. Vậy còn chiều ngược lại thì sao? Đây là đoạn trích với 386 kí tự, khi tìm kiếm từ khóa "non-compete agreement":

Để ý cụm từ "Jump to Excptions" và các liên kết ở đầu. Chúng được Google thêm vào, vì vậy rất khó để nói những thứ nào sẽ ảnh hưởng đến bộ đếm số lượng các kí tự. Đây là 1 ví dụ mà không tính các phần bổ sung thì có đúng 370 kí tự, khi tìm kiếm từ khóa "the Hunger Games books":

Vì vậy, chúng tôi biết rằng những đoạn trích dài hơn cũng vẫn tồn tại. Lưu ý rặng, mặc dù, cả 2 đoạn trích này từ Wikipedia, là 1 ngoại lệ với rất nhiều luật SEO. Có hay không những đoạn mô tả dài chỉ những trường hợp rìa? Xem xét những khoảng giữa ( hay thậm chí tính trung bình trong trường hợp này) cũng không cho ta biết điều gi cả.

## Tổng quan vấn đề, phần 1
Đôi khi, bạn phải để cho dữ liệu tự lên tiếng, với 1 chút dỗ dành. Hãy nhìn vào tất cả các đoạn trích được rút ngắn (kết thúc bằng dấu "...") và loại bỏ các kết quả video ( chúng ta đã biết từ nghiên cứu trước là những loại này có phần ngắn hơn). Nó bao gồm 42863 đoạn trích ( chỉ bằng 1 nửa tập dữ liệu của chúng tôi). Đây là biểu đồ của tất cả các chiều dài được rút ngắn, gom nhóm vào các khoảng 25 kí tự (0–25, 26–50, vân vân.):

Nó trông rất khác so với dữ liệu của chúng tôi vào tháng 12 năm ngoài, và tập trung trong khoảng 150-175. Chúng tôi thấy 1 ít đoạn trích hiển thị Google được rút ngắn sau khoảng 300, những chúng đều được làm ngắn bởi các công cụ rút gọn hơn nữa.

## The big picture, part 2
Obviously, there's a lot happening in that 125–175 character range, so let's zoom in and look at just the middle portion of the frequency distribution, broken up into smaller, 5-character buckets:

We can see pretty clearly that the bulk of cut-offs are happening in the 145–165 character range. Before December, our previous guidelines for meta descriptions were to keep them below 155 characters, so it appears that Google has more-or-less reverted to the old rules.

Keep in mind that Google uses proportional fonts, so there is no exact character limit. Some people have hypothesized a pixel-width limit, like with title tags, but I've found that more difficult to pin down with multi-line snippets (the situation gets even weirder on mobile results). Practically, it's also difficult to write to a pixel limit. The data suggests that 155 characters is a reasonable approximation.

## To the Wayback Machine... ?!
Should we just go back to a 155 character cut-off? If you've already written longer meta descriptions, should you scrap that work and start over? The simple truth is that none of us know what's going to happen next week. The way I see it, we have four viable options:

#### (1) Let Google handle it
Some sites don't have meta descriptions at all. Wikipedia happens to be one of them. Now, Google's understanding of Wikipedia's content is much deeper than most sites (thanks, in part, to Wikidata), but many sites do fare fine without the tag. If your choice is to either write bad, repetitive tags or leave them blank, then I'd say leave them blank and let Google sort it out.

#### (2) Let the ... fall where it may
You could just write to the length you think is ideal for any given page (within reason), and if the snippets get cut off, don't worry about it. Maybe the ellipsis (...) adds intrigue. I'm half-joking, but the reality is that a cut-off isn't the kiss of death. A good description should entice people to want to read more.

#### (3) Chop everything at 155 characters
You could go back and mercilessly hack all of your hard work back to 155 characters. I think this is generally going to be time badly spent and may result in even worse search snippets. If you want to rewrite shorter Meta Descriptions for your most important pages, that's perfectly reasonable, but keep in mind that some results are still showing longer snippets and this situation will continue to evolve.

#### (4) Write length-adaptive descriptions
Is it possible to write a description that works well at both lengths? I think it is, with some care and planning. I wouldn't necessarily recommend this for every single page, but maybe there is a way to have our cake and eat at least half of it, too...

## The 150/150 approach
I've been a bit obsessed with the "inverted pyramid" style of writing lately. This is a journalistic style where you start with the lead or summary of your main point and then break that down into the details, data, and context. While this approach is well suited to the web, its origins come from layout limitations in print. You never knew when your editor would have to cut your article short to fit the available space, so the inverted pyramid style helped guarantee that the most important part would usually be spared.

What if we took this approach to meta descriptions? In other words, why not write a 150-character "lead" that summarizes the page, and then add 150 characters of useful but less essential detail (when adding that detail makes sense and provides value)? The 150/150 isn't a magic number — you could even do 100/100 or 100/200. The key is to make sure that the text before the cut can stand on its own.

Think of it a bit like an ad, with two separate lines of copy. Let's take this blog post:

#### Line 1 (145 chars.)
In December, we reported that Google increased search snippets to over 300 characters. Unfortunately, it looks like the rules have changed again.

#### Line 2 (122 chars.)
According to our new research (May 2018), the limit is back to 155-160 characters. How should SEOs adapt to these changes?
Line 1 has the short version of the story and hopefully lets searchers know they're heading down the right path. Line 2 dives into a few details and gives away just enough data (hopefully) to be intriguing. If Google uses the longer description, it should work nicely, but if they don't, we shouldn't be any worse for wear.

## Should you even bother?
Is this worth the effort? I think writing effective descriptions that engage search visitors is still very important, in theory (and that this indirectly impacts even ranking), but you may find you can write perfectly well within a 155-character limit. We also have to face the reality that Google seems to be rewriting more and more descriptions. This is difficult to measure, as many rewrites are partial, but there's no guarantee that your meta description will be used as written.

Is there any way to tell when a longer snippet (>300 characters) will still be used? Some SEOs have hypothesized a link between longer snippets and featured snippets at the top of the page. In our overall data set, 13.3% of all SERPs had featured snippets. If we look at just SERPs with a maximum display snippet length of 160 characters (i.e. no result was longer than 160 characters), the featured snippet occurrence was 11.4%. If we look at SERPs with at least one display snippet over 300 characters, featured snippets occurred at a rate of 41.8%. While that second data set is fairly small, it is a striking difference. There does seem to be some connection between Google's ability to extract answers in the form of featured snippets and their ability or willingness to display longer search snippets. In many cases, though, these longer snippets are rewrites or taken directly from the page, so even then there's no guarantee that Google will use your longer meta description.

For now, it appears that the 155-character guideline is back in play. If you've already increased some of your meta descriptions, I don't think there's any reason to panic. It might make sense to rewrite overly-long descriptions on critical pages, especially if the cut-offs are leading to bad results. If you do choose to rewrite some of them, consider the 150/150 approach — at least then you'll be a bit more future-proofed.
