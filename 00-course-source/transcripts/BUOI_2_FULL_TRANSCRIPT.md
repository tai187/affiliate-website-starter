BUỔI 2 - FULL TRANSCRIPT
Build to Own
Tổng hợp 6 transcript
Tổng thời lượng: 2 giờ 14 phút 17 giây

Ghi chú: Nội dung các transcript được giữ theo từng file nguồn; không tự ý bổ sung kiến thức ngoài nội dung đã chép.

BẢN CHÉP LỜI - BẢN 2 ĐÃ HIỆU ĐÍNH
1 - Tư duy nền tảng & Mục tiêu làm việc với AI Agent
Thời lượng video: 22 phút 23 giây

# Nội dung bản chép lời đã hiệu đính
[0:00] Đây là một trong những buổi quan trọng nhất. Và khi mà anh chị
[0:07] đi qua được cái buổi này xong ấy thì dường như cái khả năng của anh chị có
[0:11] thể mở rộng ra và cái việc á mình có thể làm việc với cả AI, cộng tác với cả AI,
[0:16] làm việc chéo với cả con người thì nó nhân lên khoảng mấy lần. Ờ,
[0:23] thì buổi hôm nay, để Sơn share cái màn hình cho anh chị em để bắt
[0:28] đầu cái buổi hôm nay. Cái mục tiêu của chúng ta á trong cái
[0:32] buổi hôm nay đó là mình sẽ setup được cái môi trường mà các bạn ở đây
[0:37] có thể hợp tác được với cả AI Agent, hoặc
[0:41] là bạn với cả team của các bạn, đội ngũ của các bạn ví dụ như trong công ty của
[0:46] các bạn trên hai người, 5 người, 10 người thì các bạn có thể dễ dàng hợp tác
[0:50] đối với cả đội AI Agent hơn. Cái mục tiêu thứ hai đó là bạn có thể
[0:56] đồng bộ được công việc với cả team của các bạn. Sơn nghĩ rằng đây cũng sẽ là một
[1:00] cái chủ đề thêm ờ trong cái quá trình á mà bạn xây sản phẩm, bạn làm phần mềm ờ
[1:06] hoặc thậm chí rằng bạn vận hành với cả đội ngũ con người thì bạn có thể học
[1:09] được cái cách á mà một đội khi mà họ làm việc trong cái software phần mềm họ sẽ
[1:14] làm như thế nào. Và đây cũng là cái kinh nghiệm không phải là sách vở mà đây là
[1:20] cái kinh nghiệm thực tế mà Sơn nó trả tiền. Trong cái lĩnh vực này, Sơn bỏ
[1:24] tiền ra, Sơn thuê đội phần mềm, đội sản phẩm, đội thiết kế ờ để làm ra được
[1:31] những cái sản phẩm. Thì đây Sơn đã chia sẻ lại cho các bạn á là cái cách làm thế
[1:35] nào để mình có thể đồng bộ được công việc với cả team của mình hiện tại đang
[1:39] có và làm thế nào để mình có thể ứng dụng được vào kết hợp để làm được với cả
[1:43] đội AI Agent. Cái thứ ba đó là các bạn có thể nối được
[1:48] AI vào cái hệ thống của các bạn qua API. Thì cái số ba này là một trong những cái
[1:53] mà rất quan trọng bởi khi mà các bạn đã biết API là gì, sử dụng nó như thế nào
[1:58] thì nó là cái cánh tay để nó mở rộng ra cái năng lực của AI của các bạn. Bởi vì
[2:04] AI á thì nó rất là cần ngữ cảnh mà khi mà các bạn đã biết sử dụng API, biết sử
[2:09] dụng MCP thì nó sẽ tạo ra ngữ cảnh cho các bạn á và các bạn đã làm việc rất là
[2:13] nhàn, rất là đơn giản, rất là dễ. các bạn cũng sẽ thấy được rằng cái cách làm
[2:17] thế nào mà Sơn á có thể á dễ dàng quản lý được á nhiều phòng ban trong công ty
[2:22] mà đôi khi mà mình không cần phải hỏi trực tiếp bất kỳ ai ờ mà nó đã có đầy đủ
[2:27] cái ngữ cảnh rồi đó thì tí nữa Sơn sẽ demo cho các bạn nhìn thấy.
[2:31] Tiếp theo cái đầu ra của cái buổi thứ hai này và sau đó bạn cũng sẽ có cái bài
[2:35] tập để các bạn làm từ thực tế trong buổi thứ hai. Sơn nghĩ rằng qua buổi
[2:40] số hai này thì sẽ có nhiều bài tập hơn đấy nhá. Nhiều bài tập hơn. Và các bạn
[2:44] hãy nhớ cái công thức á mà Sơn đã từng nói á là học một nhưng mà mình sẽ cần nó
[2:48] phải thực hành và làm bài tập á là ít nhất á phải gấp đôi cái thời gian nó
[2:53] lên. Và cái thứ ba đó là các bạn sẽ xây được một cái spec như thế nào hoàn chỉnh
[2:59] để các bạn cộng tác được với cả đội AI Agent. Cái thứ ba đó là kiến trúc, đó là
[3:05] architecture. Cái thứ tư đó là bạn nó sẽ có được cái môi trường để bạn đưa lên
[3:10] đẩy lên những cái ticket về sản phẩm như thế nào. Được chưa? Thì đây
[3:16] là mục tiêu của buổi số 2 ngày hôm nay.
[3:19] Nếu như nói á buổi số một á để chúng ta trả lời á đó là chúng ta sẽ build cái
[3:23] gì, chúng ta sẽ đi tới đâu thì cái buổi số hai này á thì chúng ta sẽ trả lời cái
[3:28] câu hỏi á là cái môi trường làm việc ở đâu và chúng ta làm với cả ai. Được
[3:33] chưa? Các bạn đã sẵn sàng cho buổi số hai của chúng ta chưa ạ?
[3:37] Ờ trước khi đi sâu á vào phần kỹ thuật ấy thì Sơn muốn nói với các bạn á là hãy
[3:42] coi tất cả ờ coi cái quá trình mà các bạn làm việc ấy. Ờ và đặc biệt nhất khi
[3:48] mà chúng ta học một cái môn gì mới đúng không? Ví dụ như là AI nó là cái môn
[3:51] mới. Những ai nhanh thì có thể các bạn biết nó từ năm 2022 khi mà ChatGPT
[3:56] mới ra. Còn một số thì có thể giống như Sơn, bắt đầu sớm nhưng
[4:02] mà đến khoảng 2024 thì thực sự mình mới dành thời gian vào cho nó. Mình mới
[4:07] để ý tới nó, mình mới thực sự mình làm việc với nó nhiều hàng ngày. Thì khi mà
[4:11] mình bắt đầu bất kỳ mấy cái công việc gì hoặc là ví dụ như bây giờ các bạn đang
[4:15] sử dụng AI cho việc á là coding, làm phần mềm, làm những cái thứ phức tạp, độ
[4:21] khó cao thì ờ cái khi mà các bạn á ứng dụng vào một cái công việc mới á thì hãy
[4:26] cứ xem mọi thứ giống như một cái cây trí thức ấy. Cái cây trí thức này là như thế
[4:31] nào? Sơn lấy ví dụ là công việc coding, làm phần mềm, thì
[4:36] thường á mọi người sẽ hay tập trung vào cái phần là phần lá cây và cái phần ngọn
[4:41] tức là cái phần code ấy những cái dòng code những cái mã những cái dòng lập
[4:45] trình các bạn á hay bị soi vào cái phần chi tiết thì cái cách làm của Sơn á là
[4:49] Sơn hay lật ngược lại Sơn đi vào cái bản chất của nó cái gốc rễ đó và sau đó thì
[4:55] mình mới đi lên trên là cái thân cây, cái cành cây và cuối cùng mới là cái lá
[4:59] cây. Sơn có từng, cách đây khoảng 1 năm gì đấy, đăng một vài
[5:04] những cái bài viết Sơn nó chia sẻ về cái cách cái kinh nghiệm của Sơn á là làm
[5:08] thế nào để Sơn có thể làm ra được những phần mềm theo kiểu solo, mình
[5:14] có thể tự build được vào những ngày cuối tuần. Thì khi mà mình đăng lên và
[5:18] mình tin rằng đây sẽ là xu hướng trong tương lai, rằng
[5:22] á mọi người á sẽ không còn đọc code nữa, không còn đọc những cái dòng code nữa.
[5:27] Thì khi mà Sơn đăng lên, rất nhiều người vào comment; sẽ có 50%
[5:32] á là ủng hộ ồ tôi thấy cái này hay quá, tôi cũng là người làm kinh doanh, tôi
[5:37] thấy cái này rất là tuyệt và tôi có nhiều ý tưởng nhưng mà tôi không biết
[5:40] cách để làm như thế nào cả nên cái chia sẻ của bạn rất giá trị. Nhưng bên cạnh
[5:44] đó thì một nửa, 50% còn lại, sẽ không đồng ý, bảo rằng: à, bạn coding
[5:50] nhưng bạn lại không đọc dòng code thì như vậy chỉ tạo ra bug, tạo ra lỗ hổng
[5:54] bảo mật vân vân thì sẽ Sơn nghĩ rằng á sẽ luôn luôn á là hai cái chiều đó thì
[6:00] đều đúng và đó là những cái góc nhìn của những người mà họ đang làm trong lĩnh
[6:05] vực chuyên sâu, cái sự hiểu biết chuyên sâu của họ. Thì cái cách mà Sơn đối diện
[6:10] với cả cái vấn đề đấy á thì Sơn nghĩ rằng như này đó là nếu như bây giờ mà
[6:14] mình đi học á phần mềm á lại từ đầu giống như cái cách truyền thống thì á 4
[6:20] năm trong trường đại học cộng với cả 6 tới 7 năm á làm việc thực tế thì mình á
[6:23] mới thực sự có được kinh nghiệm và sự hiểu biết sâu của nó. Thì ở đây
[6:29] Sơn không đi từ cành, lá, ngọn mà Sơn sẽ đi từ bản chất, từ gốc
[6:34] thì gốc của đây là cái gì? Ví dụ như là cái vấn đề ở đây là gì? chúng ta đã học
[6:37] được buổi một rồi chúng ta xác định được những cái vấn đề những cái cái khó chịu
[6:43] mà chúng ta đã gặp hằng ngày. Những nỗi đau mà chúng ta cảm thấy rất
[6:47] day dứt. Sơn lấy ví dụ như trước đây, mỗi khi họp hành thì mình
[6:53] rất là muốn rằng á là có một cái phiên bản để nó có thể lưu được lại những cái
[6:57] nội dung họp meeting như thế này. Như các bạn nhìn thấy bên màn hình bên tay
[7:00] phải của Sơn, các bạn nhìn thấy chưa? Thì Sơn muốn rằng nó sẽ lưu ra
[7:04] được những cái phiên bản meeting như thế. để đến cuối cái phiên họp thì ngay
[7:10] lập tức nó sẽ có một cái tổng hợp tóm tắt lại đó để biết được rằng cái cuộc
[7:15] họp này đã nói những cái gì, đã có những cái quyết định nào và cái action sau cái
[7:19] cuộc họp là cái gì. Đấy thì Sơn rất là cần cái công cụ như thế này nhưng á Sơn
[7:25] không bao giờ dám giao cái việc này cho đội ngũ của mình. Thì thứ nhất á là để
[7:30] làm ra cái này á thì cần nhiều thời gian để xây và thứ hai á là cần phải có sự
[7:35] hiểu biết về chuyên môn. Bởi nó là một kiến thức
[7:38] mới rồi nên á là mà trong khi đấy á là cứ mỗi một lần họp thì mình lại có nỗi
[7:44] đau là mình thấy ước gì á là có một cái phần mềm nó hỗ trợ cho mình á để nó tóm
[7:48] tắt lại mọi cuộc họp như thế này để ngay khi cuộc họp kết thúc là mình đã có
[7:52] quyết định và thậm chí là action luôn. Ví dụ nhé, họp xong buổi sáng
[7:57] thì nó cần là action luôn nhưng đúng không? Thì bây giờ là mình đã có cả một
[8:01] cái phiên bản là à tôi sẽ có cái raw transcript đó là full đầy đủ hết tất cả
[8:05] những nội dung đã họp và sau đó tôi đưa vào trong ngữ cảnh cho AI, rồi sau
[8:09] đó đẩy lên ticket và cho mọi người thậm chí nó ra được cái mô tả những cái
[8:12] requirement những cái yêu cầu trong công việc đầy đủ. Đấy thì đó là cái cách mà
[8:17] Sơn đi, đó là đi từ vấn đề của chính bản thân mình. Xong mình
[8:22] tìm cái hướng đó là build lúc đó thì mình muốn xác định là mình build cái gì.
[8:27] À tôi muốn build một cái ứng dụng về meeting note
[8:31] và tiếp theo nữa là hệ thống này sẽ được ghép ra sao, nó sẽ có kiến
[8:39] trúc như thế nào chúng ta sẽ sử dụng á những cái công cụ nào để chúng ta build
[8:44] nó và cuối cùng á thì mới đi vào những cái dòng code. Thì thường mọi người đi
[8:48] đi vào những dòng code trước, mọi người đi vào chi tiết trước. Nhưng không, ở
[8:53] đây á chúng ta hãy đi từ những cái từ gốc cây, thân cây, cành cây và lá cây.
[8:57] Thì bất kỳ công việc gì, khi các bạn học một lĩnh vực mới, đây cũng
[9:01] chính là nền tảng gốc. Các bạn hãy đi từ cái cây tri thức trước
[9:06] đó và hãy bám chặt vào cái gốc rễ. Được chưa ạ?
[9:12] Trong cái thời kỳ của AI như thế này và đặc biệt nhất á cái module của hôm nay á
[9:16] Sơn đánh giá rằng á nó rất là nặng, nó thuần về kỹ thuật. Ờ nếu như mà cách đây
[9:23] á một vài năm trước mà học cái này thì có thể rằng là khi mà Sơn show cho các
[9:28] bạn thì các bạn sẽ đóng não, các bạn sẽ nghe không hiểu và bởi vì các bạn đã có
[9:33] một cái cơ chế phản hồi rằng là ồ tôi nghe cái này xong tôi cũng không có làm
[9:36] được. Nhưng bây giờ trở đi á thì khi mà các bạn đã nghe hết trong cái chương
[9:40] trình này khoảng 2 tiếng đồng hồ mặc dù á Sơn show cho các bạn nói cho các bạn
[9:45] những cái gì ở đây á nó rất là nặng về kiến thức, rất là nặng về chuyên môn và
[9:48] kỹ thuật cực kỳ cao. Nhưng các bạn hãy yên tâm là các bạn đã có cái công cụ để
[9:53] các bạn làm việc rồi. Thì thứ nhất là trong cái buổi này các bạn sẽ được
[9:56] record (ghi hình) lại. Cái thứ hai sẽ có phiên bản text, tức là phiên
[10:00] bản văn bản trong campus; các bạn lên trên đó sẽ nhìn thấy và các
[10:05] bạn có thể truy xuất ngược trở lại với cả AI rằng là à trong chương trình này
[10:09] Sơn ơ chia sẻ cái điều gì? Sơn đã có những hướng dẫn như thế nào hoặc là cái
[10:13] công cụ này cài đặt ra sao các bạn có thể xem lại hoặc các bạn hỏi được với cả
[10:16] AI trực tiếp như thế. Nên á là một cái buổi nói rất là sâu về kỹ thuật và rất
[10:21] là nặng về chuyên môn như thế này thì các bạn có thể dễ dàng hiểu được nó. Và
[10:25] hãy học một cách á đầu tiên các bạn hãy học theo kiểu á là đi từ cái gốc và cái
[10:30] thân trước. Đừng quá đi vào chi tiết vội. Nên khi nào bạn sẽ thấy rằng ồ sơ
[10:35] nói cái này mình chưa kịp thao tác, đúng không ạ? Thì đừng lo, bởi vì
[10:41] bạn trong cái việc này á thì bạn chính là người CEO còn AI á nó chính là cái
[10:47] đội thực thi cho bạn. Ờ đấy thì nói ra như vậy để các bạn sẽ
[10:52] thấy được rằng mọi thứ nó dễ dàng hơn, nó đơn giản hơn trong cái quá trình mà
[10:55] chúng ta học chương trình này. Và CEO ở đây á là các bạn sẽ duyệt được á là
[11:00] những bản mô tả, những kế hoạch mà AI đưa ra. Cái này Sơn đã đề xuất với
[11:06] các bạn á khi mà các bạn làm á ờ một cái sản phẩm á thì các bạn phải chính là
[11:10] những người mà duyệt rất là kỹ từng dòng một để các bạn đọc nó. Các bạn không cần
[11:14] phải đọc code nhưng các bạn đã phải duyệt được cái plan mà nó viết ra.
[11:18] Cái này nó phải là cái ý của các bạn, nó phải là cái mà các bạn thực sự muốn. Các
[11:23] bạn cần phải feedback lại cho nó. Sơn lấy ví dụ như á là Sơn đã lên cái kịch
[11:30] bản để quay ờ nội dung trong cái chương trình ngày số 2 này thì á những cái nội
[11:36] dung á mà Sơn muốn nói á là Sơn đã phải duyệt trước hết rồi. Sơn đã phải đưa ra
[11:41] cái ý tưởng từ tám cái buổi đầu tiên cho cái chương trình này và sau đó Sơn xác
[11:45] định là buổi một sẽ là cái gì, buổi hai là gì, buổi ba là gì, buổi bốn là gì,
[11:49] buổi tám là gì và buổi 9 demo là gì. Xong sau đấy á là như buổi tối ngày hôm
[11:53] qua trước khi đi ngủ thì Sơn phải ngồi lên kế hoạch là: à, hôm nay là
[11:58] buổi số hai thế vậy chi tiết trong buổi số hai thì có những module nào và sau
[12:02] đấy á nó sẽ tạo ra cho Sơn một cái kế hoạch thì thứ nhất á là Sơn phải là
[12:06] người duyệt cái ý tưởng trước cái thứ hai là cái kế hoạch Sơn phải là người
[12:09] duyệt cái kế hoạch đấy. Thì ở đây bạn chính là một người CEO và bạn là người
[12:13] duyệt kế hoạch đó của AI Agent, còn AI Agent sẽ là đội
[12:18] thực thi cho mình được chưa các bạn? Đấy, cái này các bạn viết lại nhá, chụp
[12:24] lại nhé. Ok. Thì ở đây, Sơn chia sẻ cho các bạn
[12:29] này. Ờ đây là cái quá trình á mà Sơn làm thực tế đó là sáu phòng ban nhưng á một
[12:36] mình mình có thể quản lý được nó. Nên các bạn sẽ thấy
[12:41] rằng là trong team của Sơn ấy là đội ngũ rất là mỏng.
[12:44] Ờ Sơn theo cái phong cách á là không cần nó phải theo một cái phong cách như hồi
[12:48] trước đây á là công ty phải là một vài trăm người hoặc là một vài nghìn người.
[12:53] Nghe thì rất lớn nhưng nó sẽ rất là nặng về vận hành. Còn ở bây giờ thời điểm bây
[12:58] giờ ấy thì team rất là mỏng. có thể chỉ cần thôi rất gọn thôi khoảng năm người
[13:03] hoặc là team lớn hơn một chút thì khoảng 20 người nhưng những cái team á khoảng
[13:08] 10 tới 20 người như vậy á thì lại có giá trị lớn hơn rất nhiều so với những cái
[13:12] team 2000 người 3000 người ở giai đoạn truyền thống
[13:16] nên trong cái team của Sơn á ví dụ như là có khoảng sáu người đi thì sáu người
[13:21] mỗi một người sẽ theo một cái vị trí khác nhau. Ví dụ như là một bạn làm
[13:24] thiết kế, một bạn chuyên về quản lý sản phẩm, một bạn chuyên làm lập trình. phần
[13:30] mềm. Một bạn chuyên về marketing, một bạn chuyên về khách hàng. Như
[13:34] hôm bữa Sơn nói là go-to-market ấy; một bạn chuyên về kế toán, sổ sách thì
[13:39] nó sẽ có sáu cái phòng ban như thế này. Và cái mỗi một phòng ban á sẽ sở hữu
[13:43] những công cụ khác nhau để có thể thúc đẩy
[13:48] công việc của các bạn tốt hơn. Thì ví dụ nhá, thiết kế là sẽ sử dụng Figma hay là
[13:53] v0. Hoặc là một ứng dụng mà Sơn mới khám phá ra tên là PL.ai.
[14:00] Về sản phẩm thì quản lý ở trên Notion với cả Linear; và phần mềm thì ở
[14:06] trên GitHub, Vercel, Supabase và Cloudflare. Lấy ví dụ như thế thì cái
[14:11] điều hay ở đây là gì? Ví dụ như các bạn đây là các bạn đã là người quản lý trong
[14:15] cái trong một cái team của mình, một cái team cũng khoảng năm người sáu người như
[14:18] thế này. Thì trước đây á là các bạn á sẽ cần phải yêu cầu á đội ngũ của mình á
[14:23] phải làm report. hoặc là các bạn phải vào trực tiếp những
[14:26] cái phần mềm như thế này để các bạn á xem những cái báo cáo của từng sản phẩm
[14:30] một. Thì bây giờ rất là hay đó là các bạn thực ra các bạn không cần phải làm
[14:34] như thế rằng á là mỗi khi á mà Sơn á làm một cái phần mềm nào ấy, một cái ứng
[14:39] dụng nào ấy thì Sơn đều vào trong cái phần developer thử xem rằng á là nó có
[14:45] tính năng API hay không thì Sơn sẽ lấy cái API đấy. Sơn đưa cho
[14:51] con AI Agent của mình. Và lúc này á là nó đã giữ được hết tất cả những cái công
[14:55] cụ rồi. Thì khi nào Sơn đặt cho nó một câu hỏi rằng: ê, trong
[15:00] cái tháng vừa qua cái bạn á làm go to market gtm ấy, bạn GTM thì bạn ấy đã
[15:08] tiếp cận khách hàng của mình đến giai đoạn nào rồi và hiện tại đang có bao
[15:12] nhiêu sale để follow up. Và trong cái tháng vừa qua ấy thì bạn ấy đã a đã
[15:19] email marketing được tới bao nhiêu người, thì cùng với một câu hỏi như thế, con
[15:24] AI của Sơn sẽ vào hai công cụ khác nhau và lấy được thông tin
[15:28] xong nó trả ra cái kết quả để nó tạo ra cho mình một cái report. Và sau đấy Sơn
[15:33] nó hỏi nó thêm rằng á là à thế trong cái tuần đấy thì cái bạn GTM này bạn ấy có
[15:39] cái vấn đề hay là gọi là cái blocker nào hay không? thì bạn ấy bảo rằng là à bên
[15:43] đối tác của bên bên khách hàng của mình á đang yêu cầu rằng cần phải bảo mật
[15:49] được dữ liệu khách hàng và cần phải có terms (điều khoản/thỏa thuận) ở trên
[15:53] website của mình. [Có đoạn trao đổi ngắn về mic.]
[16:02] Rồi, nói tiếp nhé. Và cộng thêm một cái là
[16:08] họ sẽ yêu cầu vấn đề A, B, ví dụ như thế. Thì mình sẽ biết được đây
[16:13] là những blocker và bạn ấy ghi chú ở trong phần mềm HubSpot. Thì
[16:19] lúc này mình sẽ không có hỏi trực tiếp cái bạn GTM này mà bởi vì á cái múi giờ
[16:23] của bạn ấy lại trái với cái múi giờ của Sơn. Bạn ấy là múi giờ cộng 1 còn Sơn là
[16:28] múi giờ cộng 7 là chênh nhau á 6 tiếng đồng hồ thì lúc đôi khi á là bạn ấy
[16:32] không online nhưng mà Sơn muốn cái thông tin nó ngay thì Sơn nó chỉ cần nó chọc
[16:36] vào cái cơ sở dữ liệu ở đây và nó trả cho Sơn cái kết quả đầu ra xong á cùng
[16:40] cái thời điểm đầu ra như vậy thì Sơn viết ra một cái bản mô tả đặc tả về sản
[16:44] phẩm, yêu cầu về sản phẩm. Sơn gửi nó lên Linear cho cô
[16:50] quản lý sản phẩm. Sau khi cô quản lý sản phẩm
[16:56] duyệt xong rồi thì anh làm phần mềm sẽ đẩy lên
[17:00] GitHub. Thì mọi thứ á là là có thể cùng một cái lúc như vậy mình quản lý được
[17:05] rất là nhiều cái phòng ban khác nhau và trả lời được những cái câu hỏi cực kỳ
[17:09] nhanh chóng. Hay lấy một ví dụ khác như ở đây:
[17:13] á không biết rằng á là có anh chị nào á mà mình á phải thường xuyên á làm sổ
[17:17] sổ sách, kế toán hoặc chi tiêu thì điều này Sơn nghĩ
[17:22] rằng á là nó mất rất nhiều thời gian và con số này phức tạp này vất vả này đúng
[17:26] không ạ thì cái lợi ở đây á khi mà Sơn đã sử dụng á là cái công cụ á ở bên quốc
[17:32] tế, ví dụ như Sơn đã sử dụng hai cái là Mercury và Stripe thì
[17:37] mình sẽ biết được dòng tiền đầu vào là bao nhiêu và cái
[17:41] chi đầu ra là bao nhiêu tiền. Và sau đấy á mình còn yêu cầu nó ấy là nó sẽ nó sẽ
[17:47] filter ra cho mình, nó sẽ nó sẽ sắp xếp, nó sẽ lọc ra cho mình xem rằng á là mình
[17:51] đang chi vào đâu đó và doanh thu của mình đến từ đâu nhưng mình lại không cần
[17:56] trực tiếp vào trong cái ứng dụng đấy. Đó đây là một cái điều rất là hay các bạn
[18:00] ạ. Và dường như đây sẽ là một cái gọi là cái user interface ờ của chúng ta đó và
[18:07] của bọn AI Agent luôn. Tức là mình không cần phải vào trực tiếp ứng dụng đấy
[18:10] để chúng ta biết được mọi thông tin mà chúng ta sẽ chỉ cần quản lý từ xa thôi
[18:14] và chúng ta hỏi nó thôi trên một cái khung chat thôi là nó có thể ra được mọi
[18:17] thứ. Đấy thì tí nữa Sơn sẽ demo cho các bạn á để các bạn đã nhìn thấy những cái
[18:22] điều mà Sơn đang làm thực tế ở đây. Thì cái thứ thay thế á cho những cái phòng
[18:27] ban thì nó không phải là AI mà đó chính là những cái API. Thì đối với Sơn ấy là
[18:32] API nó chính là cái cái mở rộng ra cái ngữ cảnh cho bọn AI. Bởi vì bọn AI nó
[18:37] rất là cần ngữ cảnh đúng không ạ? Nó luôn luôn cần thông tin. Thì ờ API á nó
[18:42] chính là cái nơi nó sẽ mở rộng cái thông tin cho cái bọn AI này. Thì Sơn sẽ chỉ
[18:48] cho các bạn ở đây á là cái sự khác biệt giữa MCP và API là gì. Thì nếu như mà
[18:54] các bạn á là có nhu cầu á là các bạn á vào một cái website các bạn thao tác có
[18:58] một lần thôi thì các bạn làm trực tiếp bằng tay. Nhưng nếu như khi nào các bạn
[19:02] cần lặp lại công việc này, ví dụ như Sơn làm nó hằng ngày
[19:06] thì Sơn sẽ cần phải làm setup cái lần đầu tiên ấy. Tức là Sơn sẽ chui vào để
[19:11] Sơn xem rằng á là lấy được API như thế nào. Đó, ở bên đối tác này á, bên nhà
[19:15] cung cấp này á họ có API hay không, có cái cổng API hay không. Để lấy một cái
[19:19] ví dụ cho các bạn dễ hiểu nhé. là ở trong cái phần á là sổ sách về kế toán
[19:24] như thế này là khi mà mình có một cái nhóm sản phẩm mới đi và giả sử như trong
[19:29] cái chương trình này đi trong cái chương trình này thì các bạn á sẽ chuyển khoản
[19:33] cho Sơn vào cái tài khoản á là Techcombank hoặc là Vietin Bank thì lúc
[19:38] này á Sơn sẽ phải làm một cái động tác á là Sơn đã vào Sơn chụp lại những cái đơn
[19:42] hàng trong khoảng 100 đơn hàng đi chẳng hạn là lúc này là ai đã là người chuyển
[19:46] tiền tên là gì số điện thoại ờ email là gì và đã chuyển tiền hay chưa thì Sơn sẽ
[19:52] phải chụp lại từng cái thì mà cũng không phải là chụp á trong một buổi là xong mà
[19:57] đôi khi hết một buổi sáng thì lại có người chuyển khoản tiếp, rồi xong
[20:01] hết buổi chiều lại có người chuyển khoản tiếp thì lúc này mình phải làm thủ công
[20:04] rất là mất thời gian thì bây giờ á cái cách làm rất đơn giản thôi đó là Sơn đã
[20:08] cho người dùng của mình thanh toán qua Stripe và Sơn nhận về tài khoản banking của
[20:12] mình là Mercury thì Sơn chỉ cần hỏi bọn AI rằng: hãy
[20:18] trích xuất ra cho tôi dữ liệu rằng hiện tại đã có bao nhiêu người chuyển
[20:21] khoản, họ chuyển khoản á với cả hạng vé nào và cái số tiền bao nhiêu đó cho tới
[20:27] thời điểm real-time hiện tại thì nó sẽ vào trên này, lấy được
[20:30] thông tin thì mình sẽ không cần phải làm việc bằng tay nữa.
[20:34] Ờ và cái sự khác biệt ở đây á một chút thôi nha đó là về API với cả MCP. MCP
[20:40] thì bây giờ các bạn cũng đã nghe nhiều về MCP rồi đúng không ạ? Ờ cho Sơn hỏi
[20:44] một câu ở đây để các bạn có thể tương tác cùng với cả Sơn nhá. Thì ở trong ở
[20:50] trong cái Zoom của mình thì các bạn ở đây á là ai đã sử dụng API hoặc là MCP
[20:56] đó mình có thể comment được theo cái từ khóa đó để cho Sơn biết được rằng là là
[21:00] các bạn đang dùng được tới đâu hoặc là ai mà chưa dùng thì các bạn cứ comment
[21:04] số 0 đi xem nào. Ok
[21:08] các bạn nhớ comment nhé. Rồi, Sơn thấy rồi thì tỉ lệ các
[21:13] bạn biết về API khá nhiều rồi. Được rồi. Thế Sơn sẽ đi nhanh phần này.
[21:16] Thế tốt rồi. Các bạn biết thì Sơn sẽ đi nhanh. Còn nếu như các bạn comment
[21:20] số 0 nhiều á thì Sơn sẽ đi chậm một chút. Bởi vì Sơn nghĩ rằng á là cái phần
[21:23] API này nó rất là quan trọng. Ờ nó là một cái cái cánh cổng để nó mở ra để cho
[21:28] các bạn đi tới một thế giới mà các bạn làm việc cực kỳ hiệu suất. Sơn lấy ví
[21:32] dụ như ở đây: đây là trong tài khoản Claude của Sơn, hoặc là các bạn sử dụng OpenAI
[21:37] thì ChatGPT cũng sẽ có phần connector hoặc integration,
[21:44] hoặc phần kết nối. Thì các bạn chỉ cần vào trong phần kết nối này,
[21:49] connect trực tiếp với những ứng dụng mà các bạn đang sử dụng hiện tại
[21:52] thì cái này gọi là MCP. Còn nếu như các bạn vào trong phần
[21:58] giao diện developer, các bạn đã lấy ra một cái private key thì đó là cái API.
[22:04] Thì cái API á là thời của trước đây, còn thời của bây giờ á đó là MCP. Nhưng hiểu
[22:09] đơn giản rằng á là cái MCP nó chỉ là cái bọc lại của cái API và nó tạo ra cùng
[22:14] một cổng kết nối để đơn giản hơn cho AI Agent sử dụng thôi. Nhưng
[22:18] còn bản chất thì lõi bên trong vẫn là API.
[22:22] cái API. Được chưa ạ? Yeah.

BUỔI 2 - TRANSCRIPT 02 - BẢN GỐC
Thời lượng video: 19:21
Giữ nguyên bản chép lời tự động và mốc thời gian; chưa hiệu đính nội dung.
[0:00] Thì đây là những cái mà Sơ đã connect được vào với cả nó.
[0:05] Bây giờ nhá khi mà các bạn á sử dụng ấy thì các bạn có thể sử dụng ở trên
[0:10] terminal đây xong nó phóng to lên các bạn dễ nhìn này. Ở trên terminal thì đối
[0:16] với những cái sản phẩm nào á mà các bạn đã connect rồi á các bạn ờ slash nó một
[0:20] cái, cái ngang nó một cái, cái chéo nó một cái và các bạn gõ vào MCP thì các
[0:25] bạn sẽ nhìn thấy được rằng á là những cái ờ công cụ nào nó đã kết nối. Như các
[0:31] bạn thấy này, ở đây Sơn đã kết nối phần mềm á là marketing AHAP Clay đó là phần
[0:37] mềm để giúp cho Enrich kiểu làm đầy được danh sách khách hàng. Sơ gửi cho nó 100
[0:43] danh sách khách hàng tiềm năng và mô tả nó về những danh sách này là ai, chân
[0:47] dung khách hàng tiềm năng của mình như thế nào, những cái đặc điểm của họ và nó
[0:51] sẽ ra cho mình á thành danh sách 5000 hay là 10.000 cái danh sách tương đồng
[0:56] như thế. Đấy, rồi Gamma này, Gmail này, vân vân. Thì các bạn có thể check nó ở
[1:01] đây để các bạn biết được rằng á là nó đã kết nối được MCP với những cái công cụ
[1:05] gì và nó có những cái quyền hạn như thế nào thì trước đây á là chúng ta chỉ sử
[1:10] dụng được trên clots.ai là phiên bản website. Còn bây giờ á nó đồng bộ luôn ở
[1:15] trên cái terminal này. Bạn chỉ cần nó connect một bên thôi thì nó sẽ tự động
[1:19] chui vào đây. Và mỗi một khi nó cần cái gì, ví dụ như Sơn bảo rằng á là hãy cho
[1:25] tôi biết ờ thu về trong á tuần này trong chương
[1:33] trình trong chương trình P to own có bao nhiêu
[1:40] người đã đăng ký từ trên Zuma và doanh thu nhận về tương ứng.
[1:51] trên strive
[1:54] hoặc Mercury đi để biết được á là chi
[2:01] cái phần fe đó của nền tảng á là bao nhiêu trên thực nhận về cho tôi nhìn
[2:13] thấy á số phần trăm đấy Sơ lấy ví dụ như vậy thì nó thì Sơn đã kết nối cái thằng
[2:20] thằng Luma về API của nó rồi và thằng Stry cũng vậy là API. Còn cái thằng
[2:25] Mercury á thì nó đã có cái cổng là MCP. Thì tức là ở đây không phải là lúc nào
[2:30] chúng ta cũng là MCP hết mà đôi khi á sẽ có lúc á là API, có lúc là MCP. Nhưng
[2:36] dần dần nó người ta đang xây một cái chuẩn chung đó là MCP. Các bạn nhớ thấy
[2:39] như thế nhá. Đấy thì nó sẽ làm việc và nó chui vào. Thứ nhất là nó chui vào
[2:42] trên Luma này để nó lấy cái thông tin về.
[2:47] Đấy thì trong cái lúc mà nó làm thì đây Sơ sẽ giải thích cho các bạn sơ qua để
[2:50] các bạn hình dung á là API ở đây á đó là một cái cửa một cái phần mềm á để cho
[2:56] các phần mềm khác á là nó có thể gọi được.
[3:01] Và cái MCP á nó là một cái chuẩn để agent có thể gắn vào những cái cửa đấy.
[3:07] Đâu rồi xem là nó làm tới đâu rồi thì nó sẽ chui vào từ bên trong này nó list ra
[3:11] các thông tin mà sơ nó đề xuất các bạn nha. Khi mà các bạn làm ấy thì các bạn
[3:15] nên sử dụng trên terminal. Ban đầu có thể các bạn đã làm chưa có quen, các bạn
[3:20] nhìn chưa nó quen nhưng về sau các bạn sẽ thấy cái terminal nó cực kỳ mạnh và
[3:24] các bạn đã sử dụng rồi á thì các bạn dường như các bạn lại không có muốn sử
[3:27] dụng phiên bản web trở lại nữa. Và dường như cách đây 6 tháng nửa năm trở lại đây
[3:31] á thì Sơn rất hiếm khi nào á sử dụng cái phiên bản là website. Cũng không có bao
[3:36] giờ sử dụng phiên bản desktop mà chỉ sử dụng trên cái terminal này thôi. Và cùng
[3:41] một lúc như vậy á thì sử dụng nhiều cái terminal trên nhiều dự án khác nhau. Thì
[3:45] nếu như mà các bạn đã thường theo trong cái chương trình mà Start One mà Sơn
[3:49] chia sẻ trên YouTube ấy thì các bạn sẽ nhìn thấy được rằng ồ Sơn bật những cái
[3:53] terminal cái cái cái project của mình á là dường như Sơn không có bao giờ tắt nó
[3:57] đi. Sơ có thể treo nó trong khoảng 1 tháng đồng hồ. Cứ mỗi một khi đi ngủ thì
[4:01] Sơ cứ để nó thôi. Xong sau đó thì quay trở lại á thì nó vẫn đang hoạt động như
[4:05] thế. Hoặc đôi khi á mà mình có thể đi ra bên ngoài á ờ thể dục thể thao đi ăn
[4:11] sáng và Sơn đã giao cho nó ấy là cái mô tả công việc. Sau đó thì Sơn đồng ý rằng
[4:16] là bây giờ bạn hãy làm nó đi. Thì á Sơn nó quay trở lại á thì nó thì nó đã hoàn
[4:20] thành và Sơn đã tắt đi á cái tính năng á là permission.
[4:25] Permission ở đây tức là mỗi một lần làm á các bạn sẽ cảm thấy rằng là à nó cứ
[4:28] hỏi mình liên tục đúng không? thì tắt luôn cái tính năng đấy. Nhưng mà các bạn
[4:32] ở đây á là các bạn đã sử dụng một thời gian với nó, bạn hiểu được rằng á nó sẽ
[4:36] làm gì trên cái máy của mình, nó sẽ có những cái thao tác gì, nó sẽ xin những
[4:39] cái quyền gì thì thời gian đầu á là các bạn hãy cứ chấp nhận theo kiểu hình thức
[4:43] thủ công. Nhưng á về sau á thì các bạn sẽ để cho nó để nó tự truy cập vào để nó
[4:48] làm mọi thứ. Đấy thì thì hiện tại như sơ là như thế. Thì khi nên cùng một lúc á
[4:53] mình có thể chạy được nhiều cái project khác nhau. Đó
[4:57] thì cứ lấy cái thông tin này nó lấy từ nhiều nơi á nên sẽ hơi chậm một chút.
[5:00] Nên là bây giờ chúng ta cứ đi tiếp nhá. Được không ạ?
[5:03] nó đang gọi trên API admin của Luma này. Tí nữa Sơn sẽ show cho các bạn thấy được
[5:09] rằng là Sơn sẽ lấy cái cái API nó như thế nào trên những cái nền tảng này.
[5:14] Ờ thì ở đây á đó là cái chỗ nào á mà các bạn á không có mở được API á thì cái chỗ
[5:19] đó là các bạn cứ coi như các bạn phải làm tay. Bởi vậy khi mà các bạn đã sử
[5:23] dụng bất kỳ cái phần mềm nào thì các bạn phải check luôn rằng xem rằng á là cái
[5:27] phần mềm này họ có ít nhất là phải có cổng API hay không. Còn nữ bên nào mà họ
[5:33] không có thì có thể rằng á là phần mề họ kiểu như họ cũng không phải là công ty
[5:36] công nghệ cho lắm hoặc á là họ không có tập trung vào đối tượng á là giới lập
[5:42] trình viên cho lắm. Hoặc là bây giờ là giai đoạn của AI agent rồi nhưng mà họ
[5:46] vẫn không có cổng API thì chứng tỏ rằng công nghệ của họ hơi bị outd, hơi bị
[5:49] chậm so với thị trường rồi. Nên chúng ta phải cân nhắc xem rằng chúng ta có nên
[5:52] chọn cái phần mềm đó hay không. Ờ thì API á nó sẽ có hai cái. Thứ nhất á
[5:58] là public key và thứ hai là cái secret key. Cái hình dung á là cái public key ở
[6:04] trên này này thì nó giống như một cái địa chỉ ngân hàng của các bạn ấy thì ai
[6:08] cũng có quyền biết cái địa chỉ ngân hàng này để họ chuyển tiền vào trong cái tài
[6:12] khoản của các bạn. Ờ cái public key này các bạn show ra ok được. Nhưng cái
[6:17] private key, cái secret key ở đây á thì các bạn cần phải bảo mật nó. Thì Sơn sẽ
[6:23] hướng dẫn cho các bạn cái cách để các bạn có thể bỏ mật nó trên nào. Thì cho
[6:27] Sơn hỏi một câu nhá. Sơn hỏi một câu nha. Như hiện tại đi thì mọi người đang
[6:31] bảo mật cái API key của mình như thế nào? Hoặc là những cái private key hoặc
[6:35] là những cái mã khóa mật khẩu. Mọi người bảo mật nó ở đâu? Cái cách gì mọi người
[6:40] có thể lưu được? Đó trên notepad này chấm file inv
[6:51] trên Google Sheet. Ok rồi trên ờ trên paper. Ok viết ra giấy đúng
[7:00] không? Rồi thì Sơn nó nhìn thấy là các bạn đã
[7:04] comment rồi. Các bạn cũng giống như Sơn trước đây á
[7:09] là Sơn sử dụng ở trên Google Keep này. Đây là Google Keep này là cái ứng dụng
[7:14] note của Google hoặc là trên note đó là ứng dụng ghi chú của Apple thì sao nó
[7:20] đôi khi á mình á ném ở trên đấy. Nhưng thực chất ra nha, những cái ứng
[7:26] dụng đấy thì khi mà các bạn lưu á là các bị đẩy lên cloud rồi. Chỉ cho nó không
[7:32] bị khó chịu nhá. các bạn sẽ bị đẩy nó lên trên cloud rồi.
[7:37] Và nếu như á mà cái cái cái tài khoản note đấy á các bạn bị nick, các bạn bị
[7:43] lộ dữ liệu á là các bạn bị mất đi những cái key này. Nếu như mà đó chỉ là tài
[7:48] khoản social media thì có thể rằng các bạn khôi phục được lại bằng số điện
[7:51] thoại hoặc là bằng chứng minh nhân dân các bạn, bằng danh tính thật của các
[7:55] bạn. Nhưng nếu như mà đó là dữ liệu của công ty, đó là tài khoản ngân hàng, đó
[7:59] là những cái dữ liệu rất là bả mật cao thì các bạn bị lộ chỉ là một lộ một lần
[8:04] thôi là coi như là các bạn bị mất hết. Nên á là chúng ta cần phải có cách, có
[8:09] phương thức để chúng ta lưu nó lại chuẩn. Rồi và nhất là bọn agent nữa bởi
[8:13] vì đôi khi á nó sử dụng á nó sẽ chép chép ra nó sẽ in ra. Thì nếu như mà nó
[8:19] khi nó in ra á là nó bị lộ ở trên cái system prom rồi. Thì ai đó developer của
[8:24] một cái công ty mà mình đang sử dụng họ query được cái dữ kiện đấy thì chúng ta
[8:30] bị lộ đi cái mã khoa bảo mật. Được chưa ạ?
[8:35] Ờ thì đây á là Sơ lấy ví dụ nhá là của thằng trên Luma này thì nó sẽ không có
[8:40] cái public key. Tức là nó cũng không cần cái public key để đầu nhận vào thì nó
[8:45] chỉ có một cái private key thôi. Thì đây trên thằng Luma thì cái mã khóa bảo mật
[8:51] như thế này thì thường là chúng ta sẽ vào ở trong cái mục là developer để
[8:54] chúng ta lấy nó và chúng ta tạo nó ra một cái mã khóa bảo mật mới. Thì thường
[8:59] á là khi mà Sơn nó vào bất kỳ một cái phần mềm gì, bất kỳ một công cụ gì mà
[9:02] Sơn có ý định Sơn sử dụng nó lâu dài là Sơn sẽ giữ nó và Sơn sẽ lưu nó lại tại
[9:07] một nơi. Được chưa? Thì bây giờ cái câu hỏi á là
[9:10] chúng ta sẽ lưu nó ở đâu và lưu nó bằng cách nào? Thì nếu như mà chúng ta đây là
[9:15] dữ liệu trên máy tính của mình thì thường á là AI nó sẽ đề xuất cho mình á
[9:19] là mình sẽ lưu ở trên cái file chenv. Thì cái này đúng. Cái này mình sẽ lưu ở
[9:24] trên file.inv nhưng có những cái lớp bảo mật nó cao
[9:28] hơn. là ở đây á là Sơn sẽ lưu nó ở trên á là
[9:32] one password và mỗi một khi á mà con AI nó sử dụng á thì nó khác biệt gì so với
[9:38] cả ENV này? Cái ENV á là nó có quyền á sử dụng bất cứ lúc nào nó muốn. Còn cái
[9:44] one password này á là khi nào nó cần dùng thì nó sẽ hỏi lệnh của Sơn và Sơn
[9:49] nó sẽ di cái vân tay của mình vào và Sơn sẽ cung cấp cho nó cái lệnh là ok bạn
[9:53] được sử dụng nó trong cái quyền hạn này bạn thì nó sẽ được sử dụng. Thì ở đây á
[9:58] đó là sân sử dụng một cái bờ mật cao bởi vì mình cũng sẽ tránh cái trường hợp á
[10:02] là giả sử như cái máy của mình nhỡ có ai đó truy cập vào hoặc là có agent nó sử
[10:10] dụng mà nó bị ai đó tấn công và nó hỏi con agent mình
[10:15] để nó in ra được á là những cái mã khoa bả mật đấy thì có thể rằng á là nó nó bị
[10:21] lừa và nó trả lời tới cho cái người đối diện kia cái mã khóa bả mật nên ở đây á
[10:26] đó là Sơn nó sử sử dụng ít nhất á là Sơn sử dụng trên one password hoặc á là đẩy
[10:31] lên trên cloud để làm việc với cả team với cả đội ngũ của mình thì Sơn đã đẩy
[10:34] lên trên Vale hoặc là trên GitHub Sơn hiện tại Sơn hay thường ở trên dùng ở
[10:38] trên Vale đó còn doanh nghiệp lớn thì các bạn có thể sử dụng ở trên Amazon
[10:43] Service thì họ sẽ cũng có cái tính năng như thế này để họ bảo mật được những cái
[10:48] mã khóa và nó sẽ không có hiển thị cái mã đó ra và nó chỉ cần á là khi nào Aent
[10:54] nó cần dùng thì nó sẽ vào trong đó nó lấy nhưng mà nó không nhìn thấy được cái
[10:57] mã đó nó cũng không có đọc nó ra được. Được chưa? Thì cái này các bạn nên chụp
[11:02] nó lại hoặc các bạn nên lưu nó lại. Và Sơn đề xuất cho các bạn á là nếu như các
[11:05] bạn đã sử dụng mãi cá nhân thì các bạn sử dụng ở trên One Password. Còn nếu như
[11:09] các bạn đẩy lên trên iCloud cho nhiều người sử dụng là sử dụng ở trên Vcell,
[11:13] GitHub hoặc là AWS. Rồi sẽ lấy ví dụ như ở trên One Password
[11:18] này thì khi mở nó lên này thì cái đầu tiên nó sẽ luôn luôn nó hỏi quyền truy
[11:22] cập của mình. thì mình ờ cho nó cái quyền thì mình sẽ vào mình
[11:27] trong bên trong á là mình sẽ nhìn được hết tất cả những cái mã khóa bảo mật của
[11:30] mình hiện tại. Thì những cái mã khóa bả mật như thế này này nó có một cái hay đó
[11:35] là cái ngày đầu tiên khi mà Sơn setup cái thằng One Passw này á thì Sơn nó sẽ
[11:39] vào bên trong để Sơn nó xem cái security của mình ở phần developer này
[11:47] thì Sơn nó sẽ cho nó cái quyền á để nó làm việc ở trên cái CLI.
[11:52] CLI ở đây tức là cái terminal ở đây này. Đây chính là cái terminal hay còn gọi là
[11:57] cái CLI. Thì sao nó bảo nó rằng á là à bây giờ
[12:02] tôi muốn cho bạn á vào trong cái One Password này của tôi để bạn cài đặt cho
[12:07] tôi thì làm như thế nào? À thì nếu như các bạn chưa biết á thì các bạn sẽ đặt
[12:10] câu hỏi như thế. Thì nó sẽ bảo rằng à bạn hãy vào trong mục setup, bạn vào
[12:14] trong mục developer và sau đó bạn click chọn CLI. Thì chỉ cần như thế thôi là nó
[12:20] sẽ có quyền á để nó chui vào đây. Thì khi mà nó chui vào đây rồi á thì Sơn bảo
[12:24] rằng là à thế bây giờ bạn hãy lấy hết tất cả những cái mã khoa bỏo mật của tôi
[12:27] trên EVN EN ENV sau đó bạn đẩy lên trên OneP này đi và bạn sắp xếp cho tôi á
[12:33] theo từng từng cái từng cái dự án một nó để làm sao nó không có bị trùng chéo với
[12:39] nhau thì nó sắp xếp này là ví dụ như là cá nhân này những cái mã khóa bở mật của
[12:42] cá nhân mã khóa bảo mật á của công ty Afiter mã khóa bảo mật của một cái size
[12:48] project mà trước đây Sơn Bill đó là Ei mã khóa bảo mật của ứng dụng Hãy nói Kim
[12:54] đó thì nó sẽ chia ra theo từng cái từng cái a từng cái project của mình. Và
[13:00] trong cái những cái project này á thì đây là những cái mã khoa bả mật bên
[13:03] trong được chưa? Thì nó tự sắp xếp, nó tự tổ hợp lại và đến khi nào á mà nó cần
[13:09] thì nó sẽ biết cách để nó lấy ra và khi mà nó lấy thì nó sẽ họ quyển mình. Được
[13:13] chưa các bạn? Thì các bạn đã sau cái buổi này á là các bạn đã cần cài ít nhất
[13:17] á là cái thằng on password này đi và cái chi phí của nó thì những rất là rẻ chỉ
[13:21] có vài đô la một tháng thôi nhưng mà nó sẽ giúp được cho các bạn bảo mật được á
[13:26] trong quá trình mà các bạn làm việc thì Xuân thấy rằng á đây là một trong những
[13:30] cái kiến thức rất là quan trọng để các bạn á làm việc lâu dài
[13:35] đó các bạn đã viết lại trong cái phần cần phải làm nhá.
[13:39] Đấy thì cái này là Sơn nó demo cho các bạn này. Sơ chụp lại.
[13:43] Thì cái bốn luật á để các bạn á làm việc với cả Asian ấy thì bạn á không có bao
[13:49] giờ đưa cho nó cái giá trị. Cái giá trị ở đây á tức là cái private key á. Thì
[13:54] cái cách làm của Sơn là như này nhá. Sơn lấy ví dụ cho các bạn này là Sơn lên
[13:59] trên cái thằng Luma cho nó vào trong phần calendar. Thì đây
[14:05] là cái phần á là sự kiện ờ của Afiter đi. Thì khi mà Sơn đã tạo ra một cái
[14:12] secret key ở đây sơ tạo ra thì nó sẽ tự động nó copy cho mình rồi nhá. Các bạn
[14:19] đã nhìn thấy vừa nó copy cho mình rồi cái secret key đó và tạo ra ngày hôm nay
[14:24] này thì thì đôi khi á rằng á là bạn bảo rằng
[14:28] là à đây là secret key của tôi. Xong sau đó thì cái việc tiếp theo của
[14:33] các bạn là gì? Có phải là các bạn dán vào cho nó đúng
[14:36] không? Hoặc á là nếu như mà các bạn kỹ hơn các bạn làm thủ công thì các bạn
[14:42] phải vào trong đúng cái project đấy để các bạn thêm cái ENV vào đúng không ạ?
[14:47] Thường là chúng ta sẽ cần phải làm như thế thì có sẽ có hai cái nhược điểm. một
[14:51] nếu như bạn dán nó vào ví dụ như đây sơ nó dán nó vào cái này s pass nó vào đây
[14:57] thì nó sẽ bị lộ cái mã key của mình á khi mà sơ pass nó vào ở trên cái khung
[15:02] chat này thì nó đẩy lên cái system prom và nó đẩy lên trên cái cloud của bên
[15:06] Antropic hoặc nếu như bây giờ các bạn vào các bạn
[15:09] làm thủ công á thì nó mất rất nhiều thời gian nên nó Sơn mới chỉ copy nó vào trên
[15:14] cái clip botard thôi. Sơ lấy ví dụ như là Sơn đây S có cái
[15:17] phần mềm Sơ quản lý tất cả những cái sao chép của mình và nó tố đa được 200 cái
[15:22] sao chép thì đến 2011 á thì nó sẽ xóa cuốn chiếu đi. Ờ Sơ lấy tạo lại một cái
[15:29] một cái key khác nhá. Sơ lấy ví dụ như đây nó bị xô ra luôn nhá. Tí nữa Sơ sẽ
[15:33] xóa cái đó đi. Đây thì đây là cái key của mình. Thì thường là các bạn không
[15:37] biết các bạn enter bảo là à đây là key của tôi. Sau đó bạn hãy làm cái gì đó đi
[15:40] đúng không ạ? Đấy thì nó sẽ bị lộ ở trên cái system prom. Đấy thì nó sẽ lộ ở trên
[15:46] cái system prom. Nếu như các bạn enter xong thì cái câu trả lời ở đây á là các
[15:50] bạn sẽ không bao giờ được làm cái này nhá.
[15:53] X back nó lại rồi nhá. X back nó lại rồi. Thì cái câu trả lời ở đây á là các
[15:58] bạn sẽ không được làm cái này. Đấy là đừng làm cái này. Là khi mà các
[16:05] bạn đã chat với nó bạn bảo đây là key của tôi xong bạn enter cho nó là ngay
[16:08] lập tức là cái key này nó đã bị lộ. Còn ở đây là Sơ demo cho các bạn Sơ xóa
[16:13] ngay đi lập tức này thì bản chất là sẽ không có bị lộ ra.
[16:18] Được chưa? Và cái thứ hai á là mình sẽ không có in
[16:23] cái key nó ra trên cái màn hình thì vừa nãy sân xô rồi. Cái thứ ba là trước khi
[16:27] mà các bạn đẩy nó lên trên GitHub, bạn đẩy lên trên GitHub thì các bạn cũng
[16:31] phải yêu cầu nó phải bảo rằng á là mày phải check cho tao xem rằng á là mày có
[16:34] đẩy lên á là những cái mã khoa bảo mật của tao lên trên cái môi trường làm việc
[16:38] chung hay không. Bởi môi trường làm việc chung á có thể đôi khi mình sẽ để cái
[16:42] public cái repo đó cho mọi người. Mình để open source cho mọi người để mọi
[16:46] người vào sử dụng thì nếu như mình không chú ý nó sẽ bị lộ ở trên đấy. Hoặc có
[16:51] một cái trường hợp hữu như thế này nhá là ban đầu cái repo trên kithub của mình
[16:55] á là mình để chế độ private cơ và mình cũng không có ý định gì mình sẽ open
[16:59] shot nó. Nhưng tới một ngày đẹp trời nào đấy thì mình lại bảo rằng à thôi tôi
[17:04] muốn open shot cho mọi người. Tôi muốn contribute, tôi muốn đóng góp tới cho
[17:08] mọi người sử dụng nó. Thêm mọi người open mọi người mở cái mã nguồn này ra
[17:11] đúng không? Mọi người mở nó ra cho tất cả mọi người nhìn thấy thì nó mới bắt
[17:15] đầu nó hiển thị ra những cái key này. Nên khi mà chúng ta làm ấy thì hãy nhớ
[17:19] rằng á ngay cả khi đó là private repo ở trên GitHub thì các bạn cũng cần phải
[17:25] quét trước khi mà các bạn đã đẩy lên trên bạn đã hỏi nó hoặc các bạn đã giao
[17:29] cho nó một lần để nó nhớ để đến sau này khi mà nó làm á thì nó sẽ biết rằng à
[17:33] tôi sẽ cần phải kiểm tra cho xem rằng á là mình có đẩy lên những cái mã khoả mật
[17:37] lên trên hay không. Rồi và cái cuối cùng đó là khi mà các
[17:43] bạn đã bị lộ cái key rồi á thì các bạn phải xoay ki đi hoặc là bạn xóa cái ky
[17:47] đi. Thì như vừa nãy Sơn Sơn nó làm á Sơn xóa cái ky đó đi. Đó trường hợp vừa nãy
[17:52] là gọi là bị lộ thì S xóa cái key đi. Đây nó có nói này một cái lưu ý á là
[17:58] mình dán key vào á cái khung chat này á nên nó hãy xoay đi này. Thì thường là
[18:02] bây giờ nó sẽ dặn cho mình hết rồi. Nó dặn cho mình rồi. nó nó bảo cho mình rồi
[18:08] cái API key này á là sơ nó lưu nó ở trên cái One Pass nên á là khi nào mà nó cần
[18:13] á thì nó phải hỏi cái này để xem là vừa nó đang làm gì. À nó thực ra nó check ra
[18:17] rồi nó check ra là 2496 cái hàng á mà danh sách người đ được invite thì ra nó
[18:22] đã check rồi. Đấy các bạn nhìn thấy này. Khi mà nó hỏi quyền á thì Sơn nó cài cái
[18:27] chế độ vào mật nên nó sẽ nó sẽ hỏi cái vân tay của mình thì mình quét cái vân
[18:31] tay thì nó mới được truy cập vào trong cái phần one password của Sơn. để nó lấy
[18:35] cái dữ dữ liệu ra. Vừa nãy Sơn làm hơi nhanh, sorry các
[18:39] bạn. Nhưng mà trong cái buổi này á, Sơn sẽ demo cho các bạn nhìn thấy rất nhiều
[18:43] lần như thế thì các bạn sẽ sẽ thấy rằng mỗi lần Sơn nó cung cấp cho nó quyền á
[18:47] thì nó sẽ phải hỏi. Ở đoạn này á, Sơn đang demo cho các bạn
[18:52] á đó là cái cách á mà Sơn nó quét dữ liệu trên Luma và Sơn đối chiếu với nó ở
[18:56] trên Sy và đấy nó đang hủy khỏi quyền Sơn nhá. thì Sơn nó sẽ cấp quyền cho nó
[19:01] bằng vân tay này. Nên á hầu như khi mà chúng ta làm việc á
[19:05] từ bây giờ về sau á thì chúng ta chính là người duyệt ra cái kế hoạch làm việc.
[19:11] Và bọn AI thì nó là bọn thực thi rất là tốt rồi. Nó thực thi rất là nhanh nên
[19:16] cái thời gian mà các bạn đã đầu tư vô nhiều ấy, đó là các bạn đã cần phải
[19:20] duyệt cái kế hoạch làm việc đó của bọn nó. M.

BUỔI 2 - TRANSCRIPT 03 - BẢN GỐC
Thời lượng video: 15:51
Giữ nguyên bản chép lời tự động và mốc thời gian; chưa hiệu đính nội dung.
[0:00] nó sẽ hỏi khoảng hai ba lần gì đấy. Xong đó vào bên trong. Cái này nếu mà mình
[0:05] muốn nhanh ấy thì mình sẽ share cho nó một lần trong một cái dự án thôi thì nó
[0:10] sẽ nó sẽ vào được nhanh và luột. Còn ở đây nếu như mình muốn kỹ thì mình có thể
[0:16] để chế độ mặc định. Như Sơn hiện tại là Sơn đang để chế độ mặc định. Ok nhá. Như
[0:20] Sơn đã nói á là cần phải làm plan và ờ đặc tả sản phẩm trước xong sau đó mình
[0:26] mới code sau. Thì trong cái quá trình mình làm ấy thì đâu đó nó sẽ có bảy cái
[0:31] mục ở trong một cái bản đăng tải sản phẩm. Thứ nhất ấy đó là chúng ta sẽ xác
[0:37] định được cái vấn đề của mình, cái vấn đề gặp phải. Cái này trong buổi một đã
[0:40] nói rất là kỹ và các bạn nếu như các bạn đã làm bài tập thì các bạn đã có cả một
[0:45] cái khung về vấn đề của mình. Những cái thường gặp trong cả một cái workflow làm
[0:50] việc. Ờ và mình á viết ra được á là từ từ 10 3 và 1 đúng không ạ? 10 vấn đề
[0:57] xong đó chọn thành ba và sau đó chọn thành một cái cuối cùng. Thì ở đây là
[1:01] các bạn đã làm bài tập hết chưa? Tuần này á thì chúng ta sẽ xem bài tập một
[1:06] cách hơi thủ công. Nhưng từ ngày hôm nay trở đi là Sơn đã build xong á cái nền
[1:12] tảng để các bạn có thể vào học được rồi. Nên trong cái nền tảng vào học đấy á thì
[1:16] các bạn á sẽ thứ nhất là xem được lại bài giảng hôm trước này. Ví dụ như các
[1:20] bạn muốn xem kỹ hơn từ những gì mà Sơn nói hoặc là bạn vào muộn một chút thì
[1:26] các bạn vẫn có thể xem lại được. Và cái thứ hai đó là các bạn sẽ bấm vào cái
[1:30] phần tiến trình ấy, các bạn sẽ nhìn thấy là bài tập và các bạn đã đọc được cái
[1:34] bài tập đó chi tiết này. Các bạn đã nộp bài tập xong thì các bạn sẽ nhìn thấy
[1:38] được bài tập của những người khác đã nộp. Đó thì thì tuần này thì các bạn sẽ
[1:42] nộp bài tập thủ công. Và dường như là Sơn á giả sử góc độ của Sơn đi Sơn check
[1:46] thì Sơn cũng không biết rằng có bao nhiêu phần trăm đã nộp bài rồi. Nhưng
[1:50] nếu như mà các bạn đã nộp được vào trên đó thì thứ nhất á là các bạn cũng nhìn
[1:53] thấy được nhau và Sơn cũng nhìn thấy được trên tổng số.
[1:56] Cái đó là cái thức rất là hay. Xong cái ờ thứ hai trong cái phần tí nữa đi sâu
[2:03] vào thì cái này Sơ sẽ lướt qua thôi nhá. Quan trọng là cái phần demo ấy thì nó sẽ
[2:07] có bảy cái phần đó mà Sơn thường sẽ làm ấy. Đ thứ nhất á là phải xác định được
[2:11] vấn đề. Cái việc xác định được vấn đề á và chọn được vấn đề để mình giải quyết á
[2:16] cực kỳ cần thiết. Nên nó không phải là vấn đề gì chúng ta
[2:20] cũng đi giải quyết mà chúng ta sẽ phải sắp xếp theo á là những vấn đề nào á là
[2:25] cấp bách, khẩn cấp, quan trọng, có impact cao thì chúng ta tập trung vào
[2:32] giải quyết vấn đề đó. Và đôi khi chúng ta sẽ không cần đi giải quyết vấn đề nào
[2:35] cả nếu như vấn đề đó không đáng để giải quyết.
[2:38] Đ thì chỉ nên ở đây á là S nó yêu cầu các bạn á là hãy viết ra những 10 thứ
[2:45] sau đó mới chọn ba xong cuối cùng mới chọn một thì lúc đó bạn sẽ thấy được
[2:48] rằng à trong 10 cái thì đây mới chính là một cái mình cần phải đi giải quyết chỉ
[2:53] có một duy nhất một cái thôi không cần phải nhiều giải quyết đúng một cái lõi
[2:57] và thứ hai ai là người sẽ sử dụng cái sản phẩm này và cái cách nó hoạt động
[3:01] như thế nào trong cái cách nó hoạt động á đôi khi Sơn sẽ mô tả ra ra cái một cái
[3:05] luồng của người dùng ví dụ như là Sơn sẽ đóng vai là một người dùng Sơn sẽ Sơn sẽ
[3:09] trải nghiệm nó từ những cái bước đăng nhập, đăng ký tài khoản, onboarding cái
[3:13] tài khoản này sử dụng nó như thế nào. Và cái trải nghiệm của mình á khi mình sử
[3:17] dụng cái sản phẩm nó giống như một cái user flow ấy thì mình sẽ cần nó phải xác
[3:22] định được là cái cách hoạt động của sản phẩm vẽ ra được cái user flow. Và cái
[3:28] thứ tư, cái điều này có rất quan trọng này. Thường khi mà mình đã làm sản phẩm
[3:32] ấy mình bị kiểu mình á cảm thấy rằng là mình cần phải hoàn hảo đúng không? mình
[3:37] có cần phải build thêm tính năng nữa nên á là mình phải định nghĩa nó được là cái
[3:42] định nghĩa của hoàn thành là cái điều số sáu nhưng bên cạnh đó mình cũng cần phải
[3:46] định nghĩa ra những cái điều mà mình sẽ không có làm trong cái kỳ này, trong cái
[3:51] chu kỳ này hoặc là trong cái MVP này thì đâu là những cái điều mình không làm. Tí
[3:55] nữa Sơn nữa show ra cho các bạn nhìn thấy được rằng á là cái sự khác biệt là
[3:59] cái tuần số buổi số một ấy Sơn á chị Sơn á có làm ra một cái phiên bản thử ở trên
[4:04] cái máy của Sơn. rằng á về cái về cái về cái nền tảng để
[4:09] các bạn vào học ấy so với cái biển hiện tại thì cái bản MVP này á là Sơn đã xóa
[4:14] đi rất nhiều thứ là Sơn sẽ quyết định rằng á đâu là những thứ mà mình sẽ không
[4:18] có làm trong cái ngày hôm nay và mình sẽ chỉ đưa lên những thứ cần thiết nhất còn
[4:25] những cái nào mà không cần mình sẽ bỏ nó đi, xóa đi hoặc là mình lưu nó lại. Và
[4:30] cái thứ năm đó là những cái dữ liệu hoặc là những cái công cụ gì mình sẽ sử dụng
[4:36] nó. Rồi thì tí nữa Sơn sẽ đẩy nó lên trên cái môi trường làm việc để các bạn
[4:41] sẽ nhìn thấy được Sơn sẽ quản lý nó ở đâu và Sơn sẽ đẩy nó lên như thế nào.
[4:46] Đây là cái mà Sơn đã buill này. Thì Sơn điều mà Sơn nói á là những cái mà Sơn
[4:52] không làm á thì các bạn sẽ thấy sự khác biệt không? Hôm trước á là cái menu
[4:55] thanh menu bên tay trái này này nó có rất là nhiều cột đúng không? Nó có rất
[5:00] nhiều cột. Nó có cả mục sắp đắ cá nhân. Nó có mục
[5:05] ờ thông tin. Nó có mục inbox in email. Ờ đâu đó có khoảng sáu bảy mục đó ở đây.
[5:13] Nhưng sau đấy Sơn bỏ nó ra đi hết và Sơn nó chỉ chọn nó lại á hai mục quan trọng
[5:17] nhất. Bởi vì Sơn đặt ra câu hỏi rằng á là định nghĩa hoàn thành của cái sản
[5:23] phẩm này trong tuần một là gì? Trong buổi số hai là gì? cái định nghĩa hoàn
[5:28] thành của nó là gì và cái điều gì mình sẽ không có làm. Thì Sơn nó đặt ra hai
[5:32] câu hỏi ở đây. Cái số 4 và số 6 là hai cái quan trọng. Và sau đó là những cái
[5:36] gì không làm sơ bỏ nó đi và những cái gì mà bắt buộc phải có. Bởi vì bây giờ các
[5:40] bạn á vào thì đầu tiên á là các bạn phải nhìn thấy được cái nội dung bài giảng
[5:44] đúng không? Các bạn á cần phải khi mà các bạn bấm
[5:47] vào bài tiếp theo hoặc là các bạn đánh dấu hoàn thành
[5:51] thì nó sẽ cho mọi người biết rằng là à cái nội dung này á là chúng ta đã hoàn
[5:55] thành nó rồi, chúng ta đã xem xong rồi, chúng ta đã học xong rồi thì nó sẽ đánh
[5:59] dấu tích xanh vào. T đó là cái tính năng thứ hai nó cần. Và tiếp theo nữa ấy đó
[6:06] là nó sẽ phải đẩy lên cái video của mình lên trên này được. Mọi người có thể bấm
[6:10] được vào xem. Nó có thể kết catch lại á là cái đoạn mà người dùng đã xem được
[6:15] tới đâu. Lấy ví dụ như Sơn xem cái video này được 2 phút 19 giây thì nó đã kết
[6:19] lại á nó đã lưu lại để sau này khi mà Sơn quay lại cái video này thì nó sẽ
[6:24] chiếu tiếp tục chứ nó không có phải là quay lại từ đầu mà Sơn cũng không cần
[6:27] phải nhớ là à mình đã xem từ đâu nhỉ. Và có nội dung bài học phía bên dưới
[6:33] có hình ảnh có text. Thì cái text và cái hình ảnh này á là Sơn cũng cần nó phải
[6:38] làm thế nào á để sau này á là không phải là chỉ một mình Sơn build nó mà cần nó
[6:43] phải có đội của mình à mọi người cũng có thể vào contribute cùng với cả mình. Giả
[6:47] sử như mọi người vào để add thêm video mới khi mà đã cắt ghép xong hoặc đưa
[6:53] thêm á nội dung lên trên này hoặc á là những cái nội dung text á thì sẽ cần nó
[6:58] phải bô đen in nghiêng hoặc á là ờ dùng thẻ cho nó ra sao. Thì cái này á là mình
[7:04] đã cần phải setup và mình hướng dẫn lại cho đội ngũ đúng chưa? chứ mình không
[7:08] phải là build từ đầu đến cuối. Đấy, rồi mọi người có thể trượt ngang á
[7:14] a trượt lên trượt xuống và nhìn thấy cái sản phẩm này và sẽ biết được rằng á đâu
[7:19] là những nội dung đã được mở và đâu là nội dung chưa bắt đầu và cái thời gian
[7:24] của từng cái video này. Đó thì đối với Sơn đây là cái phiên bản MVP sử dụng
[7:30] được luôn và mọi người có thể đăng nhập nó vào được bằng cái tài khoản của mọi
[7:34] người. Và ở đây á là Xuân đã cấp theo cái email mà mọi người đang đăng ký
[7:37] chương trình này. Thực ra á nhìn nó đơn giản như vậy á nhưng á bên trong của nó
[7:42] ấy là rất nhiều việc. Nó rất nhiều việc ở trong cả phần backend nữa. Nhưng cái
[7:46] phần fend á thì nhìn cực kỳ đơn giản thì Xơ nó sẽ làm nó tinh gọn nó sử dụng
[7:52] được. Thì đó là cái tính năng một đầu tiên nhá. Còn cái tính năng số hai á là
[7:57] cái phần tiến độ. Phần tiến độ đây chính là cái phần bài tập của các bạn. Giả sử
[8:01] như tuần số 0 thì Xuân có giao cho các bạn là hai nhóm bài tập đó là cài đặt AI
[8:07] agent và ba cái bài tập á liên quan á về một ngày làm việc của các bạn, tiền công
[8:12] cụ mà các bạn đã chi và những cái nỗi đau mà các bạn đang gặp phải hàng ngày.
[8:17] Đấy thì các bạn nó sẽ nhìn thấy được á là những cái bài tập này và các bạn có
[8:21] thể nộp bài được trên này. Thì khi mà các bạn nộp bài được xong à đã có năm
[8:25] người nộp bài trên này này. năm người nộp bài trên này thì các bạn á nộp bài
[8:30] trên này và các bạn sẽ nhìn thấy được bài tập của những người khác đã nộp.
[8:34] Đấy thì thì đó là những cái tính năng mà Sơn build ra nhá. Thì khi mà Sơn build
[8:38] ra cái tính cái sản phẩm này á Sơ mới phát hiện ra được á là một cái điều đó
[8:44] là Sơn nó tính ra cái bảng giá, cái bảng chi phí á cái bảng chi phí mà Sơn bất
[8:50] ngờ luôn. Bảng chi phí và Sơn chạy thử. Giả sử như chương trình này có 130 người
[8:54] học và cứ lấy ví dụ như bây giờ các bạn đã sẽ tỉ lệ á là 100% các bạn đã sẽ muốn
[9:01] xem nó lại và các bạn xem đầy đủ luôn thì cái chi phí sẽ hết bao nhiêu tiền
[9:07] đấy thì các bạn có muốn biết cái chi phí nó sẽ hết bao nhiêu tiền cho cái này
[9:10] không? Và các bạn còn nhớ cái ngày hôm trước
[9:14] Sơn có nói với các bạn ấy là cái teach á mà Sơn á dùng cách đây rất nhiều năm.
[9:21] Đây Sơn dùng nó rất là nhiều năm ở trong cái phần pricing này
[9:25] thì cái cái chi phí mà Sơn đang trả cho nó hàng tháng á là 189 đô theo có tháng
[9:31] là Sơn trả cho nó 189 đô ở đây thì cứ 1 năm như vậy á là mình mất trung
[9:37] bình là 2000 đô và tính ngược trở lại đi thì cái hôm gần đây nhất chúng ta học ấy
[9:44] thì lúc đó Sơn vẫn chưa có build được cái gì hết đúng không Sơn nó chỉ đó là
[9:48] một cái bản prototype ở trên cái phí trên bản máy của Sơn thôi và Sơn chưa có
[9:52] buill cái gì hết nhưng cho tới ngày hôm nay thì các bạn đã có thể vào login nó
[9:56] vào được rồi. Các bạn đã vào để xem được lại video. Các bạn đã vào nộ được bài
[10:01] tập và đội ngũ của Sơn có thể contribute được, đóng góp được vào để cùng làm với
[10:05] cả Sơn trong cái nền tảng này. Thì nói chung nó chỉ mất khoảng hai ngày làm
[10:09] việc của mình thôi. Thực ra không tới hai ngày làm việc nhưng Sơn cứ nói là
[10:12] khoảng hai ngày làm việc. Thì khi mà Sơn nó làm á, Sơn nó mới nhân nó ra là cái
[10:17] này á nó hết chi phí bao nhiêu. Thì lúc này á, Sơ đã tạo ra một cái bảng plan
[10:21] giữ dự trù là một chương trình này là 130 người đang ký học. Và mọi người sẽ
[10:27] xem nó với thời lượng á là 100% cứ coi như là 100% đi là trung bình ấy. Nó
[10:32] trung bình là 100%. Còn nếu như là 200% là kéo lên. Nhưng mà thường sẽ nghĩ rằng
[10:35] khoảng 100% không tới bởi vì đây là cái chỉ số trung bình. Trừ khi là các bạn à
[10:41] share tài khoản này cho người khác học chung. thì may ra cái chỉ số này nó mới
[10:44] lên thôi đúng không? Nhưng mà trung bình thơ nghĩ là khoảng 100%
[10:49] hoặc là 200% đi thì nó sẽ bao nhiêu tiền? Đây dân kéo xuống thì sẽ tính ra ở
[10:55] đây á là chi phí 1 tháng là 65 đô. 65 đô chi phí 1 tháng. Còn nếu như á mà xem á
[11:02] là 100% thì chi phí là 34 đô. Thế bạn mới đặt
[11:07] câu hỏi là ô thế 64 đô so với 189 đô thì nó có rẻ hơn được bao nhiêu đâu?
[11:13] Đúng không? Các bạn sẽ đặt câu hỏi như thế đúng không ạ? Xuân cứ lấy ví dụ như
[11:16] bây giờ các bạn sẽ xem hết 200% luôn đi. Các bạn học kỹ các bạn học trăm các bạn
[11:20] xem tới hai lần. Mỗi người trung bình các bạn sẽ học tới hai lần. Nào bây giờ
[11:24] cho Sơ hỏi ở đây có anh chị em nào mà mình sẽ xem khoảng hai lần trung bình
[11:27] như vậy không? Tức là để cái con số này là 200% trung
[11:31] bình á thì sẽ phải có những người xem ít đúng không? Xem ít là giả sử như
[11:36] các bạn sẽ không có xem lần nào hoặc các bạn chỉ xem 10% 20% 30% chương trình
[11:40] học. Nhưng có một số người thì các bạn xem rất là kỹ, các bạn xem tới 4 năm lần
[11:45] thì lúc đó mới chia ra trung bình là 200% thôi nhá. Chứ không phải rằng á là
[11:50] đấy thì ý là như thế để các bạn hình dung được con số. Rồi
[11:56] thì đây Sơn cũng có so nó ra một vài những cái nơi khác, một cái nền tảng và
[11:59] một vài nền tảng khác, một vài cái chi phí khác là nếu như mình trả cho trên
[12:03] Superbase ấ Sơn đang sử dụng trên Superbase thì sẽ hết 65 đô một tháng.
[12:07] Nếu như 130 người này sẽ học với là 200% thì Sơn sẽ hết 65 đô một tháng. Còn nếu
[12:16] như sử dụng trên Cloud Flare ấy thì hết 286 đô đắt hơn, thậm chí đắt hơn cả trên
[12:20] thằng Table. Đấy nên á là đây Sơn sử dụng trên thằng Super Base. Còn trên
[12:26] YouTube ấy thì nó không chuyên nghiệp và dường như là ai cũng có thể share được
[12:30] cho nhau và nó không có tài khoản gắn liền với cái email đã đăng ký chương
[12:34] trình nên Sơn sẽ không chọn là trên thằng YouTube không
[12:39] không công khai đúng không? Trước đây là mình hay share trên này YouTube không
[12:42] công khai nhưng mà nó không chuyên nghiệp nên lúc này bây giờ Sơn đã đẩy nó
[12:45] lên và có được cái dữ liệu để cho mọi người vào được xem. Và quan trọng nhất á
[12:51] đây là chương trình tên là Build to own nên Sơn sẽ demo cho các bạn đây là một
[12:56] cái project thực tế đó mà Sơn á đang làm vào ngày một các bạn nhìn thấy à nó chưa
[13:01] có gì cả nó mới chỉ là một cái ý tưởng mà Sơn muốn làm nó thôi. Nhưng sau đó ấy
[13:06] đến kết thúc tuần số tuần số 4 thì các bạn sẽ thấy nó là một cái phiên bản cực
[13:11] kỳ hoàn thiện. Dĩ nhiên ở đây là buổi số hai thì nó sẽ có những cái lỗi này, cái
[13:16] bắc này hoặc là những cái vấn đề phát sinh ra mà Sơn đôi khi Sơn chưa có test
[13:20] được hết. Thì các bạn khi mà các bạn dùng các bạn lại đưa ra cho Sơn phản bồi
[13:24] phản hồi thì đó chính là cái việc mà Sơn đang nhận phản hồi từ người dùng của
[13:28] mình. Được chưa ạ? Rồi thế quay trở lại cái giá một chút nhá. Thì đây nó nói là
[13:32] hết 65 đô một tháng nhưng không phải là 65 đô một tháng trả đều đặng. Được chưa
[13:37] ạ? Mà ở đây nó đang tính theo cái kiểu là nếu như 130 người này mỗi một tháng
[13:43] đều coi hai lần trung bình thì mới hết 65 đô một tháng. Còn á nó sẽ tính tiền
[13:48] theo cái kiểu á là khi nào có người xem thì nó mới tính tiền. Còn nếu như nó sẽ
[13:53] không có tính tiền trên cái tiền lưu, cái tiền lưu á cái video này á thì nó sẽ
[13:58] lưu là hết 25 đô một tháng này. Nhưng được cái á lại Sơn lại đang dùng một cái
[14:03] chung. À Sơn lại đang dùng một cái chung. Thế là Sơn lại chi không phải là
[14:07] hết 25 đô một tháng nữa đây nhá. Ở trên thằng Superbase này thì cái thằng Kima
[14:12] API này á thì Sơn đang trả với nó là gói 35 đô một tháng. Nên suy ra á là cái
[14:17] thằng build to own này á không cần phải trả một đồng nào cả.
[14:20] Thì cái cùng lắm ở Sơn trả ấy đó là cái 65 đô này là khi mà các bạn đã xem hết
[14:27] hai lần trung bình 130 người này hết hai lần trung bình thì tổng cộng á là Sơn
[14:32] chi hết là 65 đô và không cần phải chi thêm.
[14:36] Các bạn hình dung được cái cách nó tính không? Đấy thì dĩ nhiên là trong cái quá
[14:41] trình mà Sơn làm Sơn sẽ cần phải verify lại nữa đến cuối tháng mình check cái
[14:45] buill xem nó có thực tế là như thế hay không.
[14:49] Đấy còn nếu như mà các bạn đã làm ra cái sản phẩm tương tự như như Sơn các bạn đã
[14:53] đẩy lên trên thì các bạn sẽ mất này 25 đô một tháng. Tức là 1 năm các bạn hết
[14:58] 250 đô cộng với cả 65 đô này thì trung bình á cứ coi như là bây giờ các bạn sẽ
[15:02] cần phải chi ra khoảng 350 đô đi. 350 đô cho tới 400 đô. Đấy còn hơn ở đây á là
[15:09] các bạn đã đang phải chi ra là 189 đô một tháng. Tức là hơn 2000 đô một năm
[15:13] thì trênh nhau khoảng bao nhiêu lần? Trênh nhau khoảng bao nhiêu lần? Mà đây
[15:18] sơ đang á chỉnh ra là 1 200% nhá. Thì cứ cho 200% đi. Bởi vì cái 65 đô này không
[15:24] có đáng kể. Nó chỉ tốn cái tiền á là chúng ta lưu chữ này thôi. Lưu chữ là
[15:28] 225 đô một tháng. À lưu trữ là 25 đô một tháng. Nhưng ở đây á lại Sơn lại không
[15:33] có tốn cái tiền 25 đô đó. Bởi vì cái gói mà Sơn đang trả cho thằng Kima này á nó
[15:37] tốn hơn một chút nó 35 đô và nó bao luôn cả cái phần bu này thì suy ra là cái 25
[15:42] đô một tháng mình không cần phải trả. Đấy mình sẽ quản lý được trên nhiều dự
[15:46] án khác nhau trên này. Đấy 35 đô nhưng mình quản lý được nhiều dự án.
[15:51] Đ

BUỔI 2 - TRANSCRIPT 04 - BẢN GỐC
Thời lượng video: 10:24
Giữ nguyên bản chép lời tự động và mốc thời gian; chưa hiệu đính nội dung.
[0:00] Cái phần tiếp theo ấy đó là cái architecture.
[0:04] Thì đặc biệt nhất á nói chung á là khi mà kinh nghiệm của các bạn nó làm 2 năm
[0:09] 3 năm chăng nữa hoặc là nhiều năm á thì các bạn nên phải có architecture để các
[0:13] bạn nhìn thấy được cái tổng quan. Đây là một cái kinh nghiệm của Sơn nhá. Khi mà
[0:17] Sơn build sản phẩm Aiter ấy thì lúc đó Sơn chưa có biết về Sơn chưa có và đụng
[0:23] tay vào để code đâu. Sơn chưa có đụng tay bất kỳ gì về hết á. Nhưng mà cái
[0:26] việc đầu tiên mà Sơn làm ấy mà cái này Sơn hay yêu cầu bạn developer làm cho
[0:31] Sơn ấy nhưng mà bạn ấy chưa có xuất ra cho mình thì Sơn mới bảo rằng đó là
[0:37] mình muốn nhìn thấy được tổng quan của cái dự án này của cái sản phẩm này như
[0:40] thế nào và các hình ảnh hóa ra được. Bởi vì Sơn thấy
[0:45] rằng á là trong tất cả các phương pháp học thì Sơn rất là mạnh về học theo kiểu
[0:50] hình ảnh hóa thì mình yêu cầu bạn ấy làm nhưng mà
[0:54] mình chưa có được cái kết quả đầu ra. Thế cho tới một ngày thì Sơn mới chọp
[0:59] cái dữ liệu vào. Đây. Đây cũng là trong mấy cái này như này nhá.
[1:04] Thì cái text của Aiter ấy đó là làm ở trên
[1:10] AWS và trên STPY.
[1:15] Strapy là cái nền tảng á để giúp cho để giúp cho team có thể vào để để
[1:23] contribute vào theo kiểu content, hình ảnh, bài post và nó có thể quản lý được
[1:28] cả API ở trên này nữa. Kiểu như nó sẽ dễ dàng sử dụng hơn cho AWS. mà team có thể
[1:34] vào được nhưng mà cũng không có bị lộ cái cái AWS tổng này được chưa? Thì cơ
[1:39] bản là như thế. Thì khi mà làm việc ấy ờ thì khi mà làm việc ấy thì Sơn nó làm
[1:47] một cái đầu tiên đó là Sơn nó cho con AI của mình á hai cái API của hai con này.
[1:52] Và lúc này á Sơn bảo rằng á là bây giờ bạn hãy giúp cho tôi vẽ ra được cái
[1:57] artecture của toàn bộ sản phẩm của tôi và mô tả nó ngược trở lại từ Codebay và
[2:04] từ ABI hiện tại đang có. Và nó cũng kết hợp với cả GitHub luôn nhá. Có nghĩa là
[2:08] ba cái nguồn sự thật. là trên GitHub AWS và Strapy xong sau đó nó vẽ ra cho Sơn
[2:15] toàn bộ những cái mối liên hệ của các APIP hiện tại Sơn đã có. Ồ thế lúc đó
[2:20] Sơn dành chắc đã không đâu đó khoảng một tuần để Sơn nghiên cứu và Sơn đọc toàn
[2:24] bộ mọi thứ thì đó là cái lúc mà Sơn học được nhiều nhất trong cái lúc mà Sơn
[2:28] buill sản phẩm ấy. Tức là Sơn tự học được luôn ấy. Tự học được thông qua cái
[2:31] việc á là đọc ngược trở lại architecture và những cái gì mà mình đang có trong
[2:34] cái sản phẩm của mình. Đâu đó chắc phải đọc ở 7 ngày bởi vì nó có nhiều kiến
[2:38] thức mới và lúc này á Sơn lại bảo nó tạo ra thành nhiều cái nội dung khác. Với
[2:44] Sơn phát hiện ra được một thứ mà trước đây mình bị làm bị sai đó là mình viết
[2:48] document trước. Document tức là cái này Sơn viết ra document public trước xong
[2:54] sau đó thì Sơn mới Sơn mới sao ta? Sơn mới
[3:00] Sơn mới code sau. Tức là kiểu như là mình cứ nghĩ rằng cái
[3:04] document này là kế hoạch thì mình cứ public lên trên này. À nhưng mà cái đó
[3:07] là sai. Cái đó là cách tiếp cận sai. Nó phải có được cái môi trường. Thì cái môi
[3:13] trường ví dụ như là những cái gì mà mình muốn làm á hay là cái vision product
[3:16] vision hoặc là cái plan hoặc là cái spec ấy thì mình phải đẩy nó trên trên liner
[3:22] hoặc ở trên notion. Đấy để cho team của mình vào cùng contribute cùng phát
[3:27] triển. Còn cái document này á nó phải chạy sau cái code bas thì cái code bay á
[3:32] nó sẽ nằm ở trên GitHub được chưa? Nên á lúc đó mình bị tiếp cận sai mình làm bị
[3:37] ngược bị ngược là mình á làm document trước sau đó mình mới làm tính năng sau.
[3:42] À thế bị sai thì lúc đó mình mới phát hiện ra được hai cái là mình cần phải
[3:45] học. Thứ nhất á là mình ảnh hóa nó ra thành architecture diagram. Đấy các bạn
[3:50] mọi mọi người viết nó ra thành cái từ khóa nhá.
[3:54] Đấy mọi người biến nó thành architecture và diagram. để nhìn thấy được cái cấu
[3:59] trúc bên trong và cái sự phụ thuộc những cái gì liên quan đến cái gì đấy
[4:05] mà cái mà cái mà cái này nó rất là hay nhá khi mà mọi người khi mà Sơn nói á
[4:12] là nó sẽ có cái script rồi đấy. Giả sử như mà cái mà Sơn nó Sơn hay
[4:18] chép nó lại này. X sẽ ném nó vào trong cái terminal.
[4:23] Sử dụng cái terminal để cho nó đồng bộ với mọi người đi. Cái terminal đây. Copy
[4:29] nó. Thì đây chính là cái context mà sơ nó
[4:32] thường á làm việc với cả AI. Đây là nội dung cần làm. Đấy. Ví dụ vậy. Thì thì
[4:40] đây là chuyên cái ngữ cảnh của hai cái đoạn mà vừa sẽ nói này. Architecture
[4:45] architecture và diagram. Nó sơ nó biến mọi thứ vào cái này. Rồi
[4:50] lấy một cái ví dụ cụ thể đi. Ngày hôm qua Sơn nó làm cái build to own cái nền
[4:54] tảng học tập ấy thì nó có gặp một cái vấn đề. Nó gặp một cái vấn đề á đây sấn
[5:01] thoát nó ra. Cái riêng mỗi cái đăng nhập này thôi nhá. riêng cái đăng nhập này
[5:06] thôi á nó tiếp cận sai cái con AI nó tiếp cận sai nên á là nó bị lưu cái
[5:13] cookie thì mãi sơ không có đăng nhập được vào. Thế Sơn nó loay hoay cả tiếng
[5:17] đồng hồ thì vẫn không có vào được. Vẫn không vào được. Mặc dù á nó gửi cho Sơn
[5:22] email sáu chữ số ờ sáu cái mã số để Sơn điền nó vào ấy thì giả sử á nó cái đoạn
[5:27] này này gửi đăng nhập này thì nó sẽ gửi cho Sơn á sáu cái mã số này qua email và
[5:31] Sơn nhập nó vào nhưng mà Sơn vẫn không có vào được thì nó bị lưu cái cookie và
[5:36] nó kết lại tại á nên á là nó bị lỗi được chưa? Thế X mới yêu cầu nó làm một cái.
[5:42] Ok. Bây giờ bạn hãy vẽ ra cho tôi toàn bộ cái diagram đi để X cho các bạn nhìn
[5:47] cái diagram ở đây. Đây. Thế X bảo rằng bây giờ bạn hãy vẽ ra cho tôi cái
[5:52] diagram đi. Ờ để tôi nhìn thấy được toàn bộ á là cái luồng nó như thế nào thì lúc
[5:58] đó mình mới fix được là nó sai ở đâu. Có nghĩa là đôi khi rằng á là nó rất là
[6:02] giỏi về lập trình nhưng mà cái này là nó cần con người, nó cần mình vào hỗ trợ.
[6:07] nó không có tự fix được thì mình phải là người vừa kiểm duyệt cho cái kế hoạch
[6:13] cái architecture và sau đấy mình feedback ngược trở lại cho nó thì đây nó
[6:17] vẽ ra sơn nhá khi mà các dần dần bạn đọc cái này sẽ quen thôi đó như ví dụ như
[6:22] cái luồng nó sẽ như thế này này thứ nhất là khi mà người dùng á mở cái trang web
[6:26] tên là build toon.de Cành ngang thì nó sẽ check thứ nhất là
[6:32] đã có cookie để vào hay chưa. Nếu có thì nó sẽ hỏi thêm một câu hỏi là còn hạn 60
[6:37] ngày hay không. Nếu mà còn thì là có trong còn trong cái danh sách á 128
[6:42] người, bây giờ là 130 người đúng không? Hay không? Nếu có thì cái này nó giống
[6:48] như là cái cái nguyên cái luồng này á nó sẽ là real time luôn. Ngay khi mà người
[6:52] dùng áo cái trang này thì nó sẽ trả lời được ngay lập tức vào luôn. nó sẽ dẫn
[6:57] người dùng vào được luôn. Nhưng ở đây là Sơn vừa mới logout ra thì câu trả lời là
[7:01] không đúng không? Thì mình sẽ chưa được đăng nhập vào. Thì nếu mà nó không thì
[7:06] nó sẽ dẫn mình tới cái cổng này để mình á cần nó phải login và mình á điền cái
[7:11] email của mình vào. Sau khi mà mình điền cái email của mình vào này thì nó sẽ hỏi
[7:16] rằng á là cái này nó có đúng định dạng hay không. Kiểu như đuôi email có đúng
[7:20] định dạng hay không á. Kiểu như ví dụ như bây giờ Sơn chỉ nhập là Sơn Pat thôi
[7:24] nhưng mình không có đuôi là a+gmail.com hoặc là cái định dạng không có đúng thì
[7:29] nó sẽ trả lời lại, nó sẽ trả lại. Còn nếu như mà định dạng đúng thì nó sẽ cho
[7:34] mình đi tiếp và nó sẽ đặt ra những cái câu hỏi và nó sẽ thấy rằng là à nếu như
[7:39] mà vẫn đúng trong cái danh sách 128 người thì cái bên dịch vụ á là resent nó
[7:44] sẽ gửi cho người dùng một cái email. Và khi mọi người dùng nhận được cái email
[7:48] này, cái email resent này á thì Sơn sẽ nói cho mọi người vào tuần số 3, tuần số
[7:52] 4 gì đó nha. Mọi người yên tâm là Sơn sẽ nói rất là kỹ đó chi tiết cho mọi người.
[7:57] Và khi mọi người dùng mở cái email này thì nó sẽ xem rằng á là cái chữ ký token
[8:01] nó có đúng hay không và còn cái hạn trong vòng 20 phút thì sau đó được vào.
[8:05] Đấy thì đây là chuyên nguyên một cái architecture chỉ riêng cái phần á là
[8:10] đăng nhập. Chỉ riêng cái phần đăng nhập thôi là
[8:13] phải vẽ được một cái tích chure bởi vì giải quyết mãi không xong. Đấy thì cũng
[8:17] không biết rằng sai từ đâu. Nó cũng không biết, mình cũng không biết, mình
[8:20] test thử rất nhiều lần rồi. Thì Sơn mới bảo rằng bây giờ bạn vẽ ra cho tôi để
[8:25] nhìn thấy được toàn bộ. Thì đó là cái kinh nghiệm nha mọi người. Phải hình ảnh
[8:28] hóa nó ra được. Cái kinh nghiệm đây mọi người phải hình ảnh hóa nó ra được toàn
[8:32] bộ những cái gì mà mọi người muốn làm và cần làm.
[8:38] Được không cả nhà? Ờ nó được tới đây rồi. Mọi người thấy
[8:42] hôm nay có học được chút ít gì không? Rồi thì bây giờ á Sơn chắc là Sơn mới
[8:49] demo cho mọi người toàn bộ những cái gì mà Sơn nói để mọi người sẽ nhìn thấy
[8:53] được cái output đầu của nó. Ví dụ như là à GitHub ví dụ như đẩy lên spec như thế
[8:59] nào, ví dụ như kiến trúc HTML ra sao, ví dụ như là đẩy tích kịt đúng không? Thì
[9:05] bây giờ sẽ cần phải có phần demo. Mọi người có muốn cái phần này không?
[9:09] để cho mọi người nhìn thấy được á toàn bộ những cái gì Sơn làm thực tế chứ vừa
[9:12] nãy chỉ là show cái kết quả thôi. Vừa nãy mới chỉ show cái kết quả thôi.
[9:20] À đúng rồi. Nên á ở đây Chy có hỏi câu hỏi á là bình thường á là khi mà làm ấy
[9:26] thì AI nó sẽ tạo ra cái file á là chấm MD. Chấm MD là nó sẽ giống như cái file
[9:31] này mà mọi người không có công cụ mở hoặc là nhìn nó xấu lắm. Nhìn nó rất là
[9:37] khó nhìn nó kiểu như mình ngồi mình duyệt hết tất cả cái này á thì mình
[9:40] không nhìn thấy được toàn cảnh đúng không? Không nhìn thấy toàn cảnh nên nó
[9:43] cứ vẽ ra vẽ ra là dễ nhìn nhất. Hoặc là diagram và architecture mọi người cứ nhớ
[9:49] từ khóa thôi là được. Được chưa? Mọi người chỉ cần nhớ từ khóa thôi. Còn khi
[9:52] mọi người đã có cái từ khóa này rồi á thì tự nhiên mọi người đưa cho con AI
[9:55] của mọi người thì AI của mọi người sẽ rất là mạnh.
[10:01] Nên sau cái chương trình này này giả sử như mọi người có cái transcript đúng
[10:04] không? Mọi người đưa cái trang script này cho AI. Mọi người bảo hôm nay tôi
[10:08] học được cái gì lưu lại thành nội dung hôm nay tôi học đi. Đúng không? Ngày một
[10:12] mọi người lưu tranpt của ngày 1, ngày hai mọi người lưu transcript của ngày 2
[10:16] thì lúc đó mọi người sẽ thấy nó đỉnh như thế nào.
[10:20] Architecture và diagram là key point.

BUỔI 2 - TRANSCRIPT 05 - BẢN GỐC
Thời lượng video: 39:12
Giữ nguyên bản chép lời tự động và mốc thời gian; chưa hiệu đính nội dung.
[0:00] Rồi bây giờ Sơn sẽ demo trực tiếp luôn này. Hôm nay bạn Phương bạn ấy hỏi Sơn
[0:04] một vài câu ờ về cái sản phẩm này mà Sơn Sơn cũng
[0:09] chưa nghĩ ra đấy. Thế X mới bảo rằng á là à thế được
[0:16] thế tí nữa em hỏi anh đi. Bây giờ em chuẩn bị lại câu hỏi xong tí nữa em hỏi
[0:19] anh đi coi như á là bây giờ chúng ta làm việc với nhau trong
[0:24] thực tế luôn. Thực ra là mấy cái này Sơn chưa có dạy cho Minh Phương luôn nhá.
[0:27] Bởi vì nền tảng là Sơn cũng mới bill và về lập trình các thứ là Sơn chưa có
[0:33] training cho Phương bởi vì trong team á là Phương ở vai trò là marketing growth
[0:38] chứ Phương không phải là lập trình viên hay là thiết kế. Nhưng bây giờ mọi người
[0:42] sẽ thấy rằng á là bất kỳ vị trí nào cũng có thể trở thành developer hoặc là
[0:48] engineer được. Đấy thì bây giờ nhá Phương ơi, bây giờ em có đang ở trong à
[0:53] em còn đang trong cái Zoom không? Em khó chịu.
[0:58] Ok. Thì bây giờ nhá em á chuẩn bị mấy câu hỏi chưa?
[1:04] \>> Em chuẩn bị nhiều câu hỏi. Ok. Thì bây giờ này từ từ nhá
[1:11] \>> để Sơn nói trước cho mọi người cái cách mà Sơn sẽ set up như thế này này. Thì cứ
[1:15] coi như đây là một cái buổi họp của của Sơn với cả team của mình đó là Minh
[1:20] Phương. Thì cái cách mà Sơn set up á là đầu tiên ấy là cái là Sơn sẽ phải có cái
[1:25] record lại. Cái record lại cái record này á đó chính
[1:32] là cái ngữ cảnh cho con AI. Thì thay vì mình phải nhớ mình đừng có tin vào não
[1:36] của mình. Não của mình không phải nhớ đâu. Mình họp xong một cuộc họp 30 phút
[1:40] hoặc là 2 tiếng đồng hồ mình quên sạch. Chắc mình á họp 20 ý thì mình nhớ được
[1:44] một ý thôi. Nhưng con AI nó sẽ nhớ toàn bộ cho mình. Thì cái phương pháp đầu
[1:49] tiên á mình phải nhớ rằng á là mình nên record nó lại. Thì trước đây á khi mà
[1:54] Sơn record á là Sơn á phải record bằng tay. Xong sau đó
[2:00] xong sau đó thì mình mới phải xuất ra thành cái transcript. Nói chung bằng tay
[2:04] thủ công mất nhiều thời gian lắm nên á Sơn mới build ra cái phần mềm này. Được
[2:08] chưa? Thì đó Sơn thấy rằng Sơn chỉ dùng cho nội bộ thôi, Sơn dùng cho cá nhân
[2:12] thôi chứ Sơn cũng không có public ra để thương mại. Một số anh chị cũng hỏi là à
[2:15] cái này có trả phí hay không để mọi người mua ấ nhưng mà góc độ Sơn chỉ
[2:19] build cho mình dùng thôi chứ không phải dành cho tất cả. Đấy thì cái cái cách
[2:23] làm đầu tiên nhá Sơn nó sẽ record nó lại. Thì từ cái record á thì Sơn sẽ có
[2:27] cái transcript. Sơn sẽ thường lấy cái full transcript này để làm contact cho
[2:32] AI. Để làm ngữ cảnh cho AI. Và khi mà mình
[2:38] đã có full cái transcript này á thì Sơn sẽ đẩy nó thành cái spec đấy. Đặc tả sản
[2:43] phẩm đúng chưa? Sơn sẽ có một cái đặc tả sản phẩm và sau đó từ cái đặc tả sản
[2:46] phẩm này thì Sơn sẽ đẩy nó lên trên môi trường á trên
[2:52] Liner ấy để quản lý những cái đặc tả sản phẩm
[2:57] này để cho team của mình có thể cùng vào đóng đóng góp. Và sau đó cái số ba đó là
[3:02] Sơn sẽ đẩy nó lên thành cái những cái tích kịch nhỏ, những cái isu nhỏ.
[3:08] Đấy. Rồi xong sau đó thì Sơn sẽ mới build và cuối cùng á mình đẩy nó lên
[3:13] trên GitHub để deploy. Được chưa? Thì đó là cái quy trình mà
[3:18] Sơn sẽ làm. Rồi thế Phương em chuẩn bị rồi đúng không?
[3:23] \>> Ok. Đây mọi người sẽ nhìn thấy cái trang ship nó nằm ở đây nhá. Đây nằm bên này
[3:25] này. Rồi Phương em bắt đầu em hỏi anh đi.
[3:29] \>> Anh anh vào cho em cái canvas đấy đi.
[3:32] \>> Ok. Rồi. Thế thì em sẽ vào vai là có ba vai. Thứ
[3:36] nhất là em vào vai user là các thành viên. Cái thứ hai là em vào vai admin là
[3:41] ok là em hoặc là anh. Hoặc cái thứ ba là em sẽ vào vai là với các bạn team
[3:45] support. cái gì với user trong cái mụn về buổi học đi trong cái danh sách thì à
[3:51] bên ngoài này em sẽ không thấy được là cái tiến độ ngay mà em học ấy. Có nghĩa
[3:55] là chẳng hạn là em đang học trong bài 1 có sáu hoặc bảy có sáu cái mục thì em
[4:01] vẫn chưa biết là ở trong đấy là nó sẽ là học đến phần nào rồi ấy. Chẳng hạn em
[4:06] học đến 3/6 thì bên ngoài nó cũng sẽ không có ghi của em đó. Em có test thử
[4:12] thì sẽ không thấy trong cái phần mà đi vào chi tiết. Anh có thể bấm vào chi
[4:15] tiết bên trong của một bài bất kỳ đó trong bài một đó
[4:20] đi. Thì khi mà em hoàn thành ấ em hoàn thành bấm một cái thì em chỉ nhìn ở cái
[4:24] lúc đầu em cũng sẽ đi tìm cái phần rất là nhỏ kia cả là hai trong 17 bài đã học
[4:28] xong. Thế thì em thấy là ồ bị nhỏ quá là em nghĩ là em em sẽ nốt lại một số cái
[4:33] thôi. Và tiếp theo đến cái phần mà tex cái mục lục này thì em cũng sẽ phải lướt
[4:37] tất cả để em sẽ xem là à thế thì trong nội dung này tại vì bây giờ em đang muốn
[4:41] là view qua tổng thôi là à cái nội dung này nó sẽ có cái gì? Có cái phần nào mà
[4:46] mình hôm nay mình muốn là tập trung vào cái phần đấy ấy. Mình miss cái phần đấy
[4:50] trong cái buổi zoom thì em muốn tập trung vào đấy hơn. Thì có thể giống như
[4:53] là trong một cái blog mình có cái phần mục lục ấy là mình có thể highlight là ở
[4:56] mục một tại vì em cũng sẽ đánh số phần là một nhỏ một lớn là gì? Một một nhỏ là
[5:01] gì ở bên trong á. Đấy thì em có thể là xem được nhanh hơn. Rồi tiếp theo đến về
[5:06] tab tiến độ thì lúc đầu ấ em nhìn cái tiến độ này em cứ tưởng là cái video mà
[5:10] em bảo anh là ô thế bài tập nộp ở đâu ấy anh thì đấy thì lúc đầu em không nhìn rõ
[5:15] lắm. Thì sau đấy em sẽ thấy phần bài tập. Trong bài tập này thì em chỉ vào
[5:21] cái phần detail thôi. Anh anh có thể vào cho em một cái detail à em có nộp em
[5:26] test luôn cái bài tập ở trong đó thì em sẽ thấy rằng là ồ thế thì khi em nộp bài
[5:31] rồi nhá em bấm test thử. Em ghi là chữ test thế xong em sự bấm em bấm xong em
[5:35] mới thấy là ô thế bây giờ em sửa ở đâu ạ? Ờ em không sửa được cái đấy tại vì
[5:39] bây giờ em muốn là em nộp thật đi. Thay vì là chữ test đấy thì em không có chỗ
[5:43] sửa nha. Cái tiếp theo nữa là tương tác với các bài khác thì có nghĩa là lúc sau
[5:47] thì em mới thấy bài mọi người đang thấy ok cái đấy cũng không có vấn đề gì cả
[5:50] nhưng mà kiểu là ok em có thể xem cái bài của mọi người thì em sẽ thấy rằng là
[5:54] nếu mà ảnh có một cái mọi người screenshot cái màn hình thì lúc đấy nó
[5:58] đẩy sang một cái trình duyên khác thay vì là nó phá mở rộng lên thì có thể ấy
[6:03] này và tiếp theo là em cũng không có thể là share hay là có thể bình luận với bài
[6:08] thì cái đấy là có thể có hoặc không nha em chỉ là hỏi phần đó thôi. Tiếp theo
[6:13] nữa là xem cái phần mà à nếu mà mọi người được phản hồi cống như là ok em là
[6:18] một thành viên, em là một user, em được chấm chữa bài thì em xem nó ở đâu á. Đó.
[6:24] Đó. Tiếp theo
[6:24] \>> khoan cái từ khoan khoan khoan cái phần nó sửa bài chấm bài là như thế nào? Em
[6:29] nói kỹ hơn phần đó được không? Anh chư?
[6:30] \>> À giống như là nhá mọi người nộp bài ở đây rồi. Thế thì làm thế nào để mà user
[6:35] có nghĩa là một anh chị học viên mọi người sẽ biết rằng rằng là à bài này của
[6:38] mình đã được xem, đã được chấm, đã được chữa mà chữa thì chữa như thế nào? mình
[6:42] sai ở đâu hoặc là mình sẽ cần phải tối ưu như thế nào thì ý là em cũng muốn là
[6:46] ok nếu mà mình nộp bài như này chứ không chỉ là nộp không mình cũng sẽ có sự
[6:50] tương tác giữa là người nộp và người được chấm à ý là người chấm đó hoặc là
[6:56] mình cũng sẽ biết là cái bài của mình là đang tình trạng như thế nào có tốt hay
[6:59] không chứ nộp làm không mà không biết là nó có tốt hay không thì cũng không thể
[7:03] cải thiện được nó rồi tiếp theo nữa là em có thể đổi được tên không đó thì đấy
[7:08] là với vai trò như user
[7:10] \>> đó Ok. Tiếp theo nữa bây giờ với vai trò là admin đi thì anh sẽ cần là ok khi mà
[7:16] em vào em cũng sẽ view được tổng quan của tất cả các thành viên thành viên nào
[7:19] đã vào, thành viên nào chưa và mọi người đang ờ như có thành viên xem em có thể
[7:24] thêm xóa sửa thông tin của mọi người hay không. Tiếp theo nữa là em sẽ xem được
[7:28] tiến độ của mọi người như thế nào. Rồi em sẽ
[7:33] \>> em cũng sẽ có cái phần để có thể là update. Tại vì là đương nhiên em sẽ là
[7:37] người khe cái phần đấy chính. Thế nên là em sẽ cần là up cái nội dung trên đấy
[7:40] đúng không? là nội dung của em liên quan tới là ồ mấy cái record đấy xong là
[7:45] video đó thì em sẽ up ở đâu này xong nội dung đấy thì em sẽ up như thế nào này
[7:49] rồi về bài tập nữa bài tập em cũng sẽ up ở trên đấy rồi cái phần mà check sửa
[7:55] feedback cho kiểu mọi người comment ấy mọi người gửi bài tập á thì em có cái
[8:00] thanh tab liên quan tới là về feedback chỉnh sửa cho mọi người không cái đấy là
[8:04] private hay là public cho tất cả các thành viên có thể xem được giống như ok
[8:08] anh chữa bài thì anh để comment lại ở đấy thì có nghĩa là mọi người có thể vào
[8:12] xem hay là hay là để private để thành viên đó xem tôi hay là mình có thể phân
[8:17] quyền các thành viên giống như tiếp theo thì chúng ta sẽ đến viện support đó. Đế
[8:21] với những cái thành viên support thì em cũng sẽ cho mọi người một số quyền thế
[8:24] nên là kể cả trong admin em
[8:26] \>> tức là tức là bây giờ á là em vừa muốn có quyền admin nhưng bên cạnh nó cũng có
[8:30] tiền quyền support và sau đó phân quyền được cho mọi người
[8:34] \>> thì nó sẽ có ba quyền đúng không? quyền user, quyền admin và quyền support sẽ
[8:38] được nhìn thấy cái gì cho từng từng admin thì là nó sẽ bao gồm thì sau đấy
[8:43] là với cái quyền support đi thì chủ yếu support thì vẫn sẽ có quyền user như
[8:47] bình thường. Ngoài ra thì sẽ có thêm cái tab là ok có thể xem là
[8:51] là cái nhóm của mình ý mọi người đang làm việc đến đâu đó mình đang làm việc ừ
[8:57] gọi là ý là ai là người chưa làm ý là có cái tab là tiến độ học vị tiến độ của
[9:02] mọi người mọi người làm đã đăng bài tập hay chưa rồi kết quả như thế nào ấy hoặc
[9:07] là sẽ có cái có thể check bài cho mọi người hoặc là có phản hồi gì của mọi
[9:11] người trên đó thì em sẽ vào ba ba của em là hết rồi Ok.
[9:19] \>> Đại thì
[9:21] \>> ok anh anh anh anh anh hiểu rồi. Những cái mà em đưa ra ấy, nếu như mà
[9:26] bình thường á một team làm sản phẩm ấy làm ấy thì theo theo em hoặc là theo mọi
[9:31] người đây mọi người thử comment xem là làm bao nhiêu lâu xong được những cái mà
[9:34] vừa đấy Minh Phương đề xuất. Nếu ở đây mọi người đang có kinh nghiệm
[9:40] làm sản phẩm nha, kinh nghiệm làm sản phẩm nha, chứ không phải là kinh nghiệm
[9:43] là làm AI nha ạ. Mọi người thử xem giờ á là bao nhiêu lâu và mất bao nhiêu tiền,
[9:49] còn bao nhiêu người. Có người comment là 5 ngày. Ok. Có người comment là 3 phút.
[9:56] Ở đây ai thực sự á là những người đã từng làm sản phẩm product thực tế đâu?
[10:00] Mọi người thử cho Sơn xem rằng là cái yêu cầu mô tả cái đặc tả cái requirement
[10:06] mình vừa nãy của Phương á là mình sẽ cần bao nhiêu người rồi
[10:11] build trong vòng bao nhiêu lâu dự kiến và cần bao nhiêu ngân sách.
[10:16] Ở đây Xuân thấy cũng có hai trường phái nha. Thứ nhất là trường phá rất là quan
[10:19] đúng không? Ấy build á trong vòng 2 tuần 3 tới 5 ngày hoặc á là build trong vòng
[10:26] 3 phút là xong. Đây là trường phái cực kỳ là quan.
[10:31] Còn có một trường phái còn lại á thì có thể là một team buill trong 1 tháng này
[10:36] hoặc á là hai tuần để bill này thì có vẻ là thực
[10:42] tế hơn một chút. Thực tế hơn một chút đấy.
[10:46] Nhưng mà Sơn nó muốn đặt ra câu hỏi là xem ở đây là những ai mà đang thực sự
[10:49] làm sản phẩm để Sơn biết được rằng á là cái câu hỏi thực tế đâ câu trả lời thực
[10:53] tế mọi người đã từng build những sản phẩm tương tự như thế này là mất bao
[10:57] nhiêu thời gian này, bao nhiêu ngân sách cho việc buill cho việc trả lương nhân
[11:02] sự này và cần bao nhiêu người mọi người thử estimate ra mọi người thử estimate
[11:07] ra thử xem là bao nhiêu các bạn thành trả lời này đây là bạn
[11:12] thành trong team build đúng không team builder này một cái hệ thống lms này tầm
[11:16] khoảng 60 triệu. Ừ. Khoảng bao nhiêu người thì build Hả Thành?
[11:21] Cái này là dự án open đã có sẵn đúng không nhở? Chứ không phải là build từ
[11:24] đầu. Cái này là vừa nãy là Phương đưa ra đề xuất á, những cái requirement này là
[11:29] build từ đầu hoàn toàn và customize theo chỉ riêng cái chương trình này thôi chứ
[11:33] không phải là lấy một cái open đang có sẵn.
[11:36] Nhưng đối với câu trả lời của Thành á đó là build một cái mà Open Short đang có
[11:40] sẵn và build trên một cái nền tảng như vậy
[11:43] đó là khoảng 60 triệu. Đây là một con số có thể trả lời được và định định giá
[11:48] được đúng không? Ok. Thôi được rồi. Thế cứ tạm thời như
[11:52] thế đi. Rồi cảm ơn Phương nhá đã đặt cho những câu hỏi rất là rõ ràng và cũng đề
[11:59] xuất ra được những cái ờ những cái tính năng mới và
[12:05] cái vai trò ấy. Cái phân vai trò thì bây giờ cái quy trình mà Sơn làm nó sẽ là
[12:11] như này để Sơ bật nó ra một cái đây là quy trình này. Thì trước đây á là khi mà
[12:17] mình làm á thì thường là mình chỉ nghe chay thôi. Mình nghe họp chay thôi. Còn
[12:20] bây giờ khi mà Sơn làm ấy thì Sơn luôn luôn nó phải có một cái transcript đầy
[12:23] đủ để mình có context. Thì context nó nằm ở đâu đây? Sơ copy đúng cái đoạn mà
[12:28] vừa nãy Sơn nó nói chuyện và phỏng vấn với cả bạn Minh Phương thôi. Cái này lại
[12:32] có cái để cần fix rồi. Lại có cái để cần phải fix rồi. Power lại nó
[12:40] kéo lên thì nó không cho. Rồi không sao.
[12:47] Ờ tiếp tục nhá. Đây S bật một cái terminal mới Sơn đã có giải pháp
[12:53] đây. Bây giờ nhá hãy CD vào build to own
[12:59] CD ở đây á tức là Sơn nó sẽ bảo nó vào ở trong một cái thư mục cụ thể thì nó sẽ
[13:04] vào trong cái thư mục cụ thể. Còn thường á thì Sơn sẽ cài nó. cài nó để mình có
[13:10] gõ được ngay cái command ở ban đầu ấy. Nhưng mà nếu như mà mình không có biết
[13:14] là mình cần phải gõ nó như thế nào đấy thì sơ nó chỉ cần nó gõ một cái lệnh
[13:19] đó là vào clot ở đây để mình kích hoạt thằng clot đúng không? Thì nó sẽ vào
[13:25] trong cái clot nhưng mà đây sẽ nó sẽ vào trong cái thư mục á trên toàn bộ cái máy
[13:30] của mình. Thì bây giờ Sơ mới bảo rằng á là mày hãy CD vào trong cái build to
[13:34] thì nó sẽ vào trong cái build to này. Rồi thì bây giờ Sơn sẽ đưa ra cho nó cái
[13:39] yêu cầu á là bạn hãy check script
[13:45] từ F trực tiếp. Đấy thì nó đang bởi vì cái này nó đang ở
[13:52] trên dữ liệu cá nhân trên cái máy cá nhân của Sơn thôi nên nó sẽ biết thay vì
[13:56] Sơn phải copy. Ờ bạn hãy check cái dữ liệu này á và
[14:00] kiểm tra xem cái đoạn hội thoại của tôi với cả bạn Minh Phương vừa nãy khi mà ờ
[14:05] có cái phần á là Minh Phương sẽ đưa ra những cái câu hỏi, những cái đề xuất
[14:10] tính năng của nền tảng học tập của Build to own và xem cái đoạn transcript đó.
[14:17] Thì công việc của bạn á là cần phải p toàn bộ cái nội dung transcript này và
[14:22] đưa ra được á cho tôi biết được rằng á là chúng ta sẽ cần phải spec nó và đưa
[14:29] ra được cái requirement như thế nào. Thì trong đó là Minh Phương có nói về những
[14:34] thứ liên quan về vai trò của admin, team support và người dùng cũng như là những
[14:40] cái yêu cầu về về xây dựng sản phẩm thì bạn viết ra cho tôi thành cái SPC trước.
[14:48] Đấy thì vừa nãy á Sơn đã giao cho nó một đống việc.
[14:53] Thì cái việc ở đây á thứ nhất đó là nó cần á phải ờ vào trong cái thằng app của
[15:01] Sơn để nó lấy cái trang script về. Thứ hai là nó sẽ viết ra nó sẽ nó sẽ đọc ra
[15:06] được và nó sẽ viết ra được thành cái spec được chưa? Thì nó có hai cái nhóm
[15:11] việc chính như thế thì nó sẽ chui vào trong cái app này thay vì vừa nãy Sơn
[15:17] phải copy bằng tay. Nhưng bên cạnh đó ấy, vừa nãy cái app
[15:21] này Sơn có một cái vấn đề mà có thể Sơn thấy build nó tiếp. Đó là khi mà mình
[15:25] copy hết toàn bộ cái này á thì nó không cho mình kéo lên. Đấy mọi người sẽ thấy
[15:30] là cái tin nhắn là nó sẽ bị mất này. Đấy thì cái này mình cũng chưa ngờ được tới
[15:34] luôn. Được chưa? Chưa ngờ được tới thì mình sẽ cần phải fix nó. Mình fix nó.
[15:39] Thì khi mà Sơn nói chuyện với ở trên cái transcript ở đây này thì Sơn đã có cái
[15:44] mô tả đặc tả sản phẩm rồi. Nên nếu như mà Sơn á mà làm nhanh ấy thì Sơn á sẽ
[15:50] lại đưa nó trên cái này Sơn sẽ vào cái thằng là dự án tên là
[15:56] FM đây. Sơ phóng to lên Sơn làm hai cái dự
[16:02] án đúng không? Thì bạn hãy check cái transcript á, vừa nãy á tôi đang là
[16:07] phỏng vấn với cả Minh Phương ấy thì có một cái vấn đề
[16:11] đó là khi mà tôi làm việc với cả ờ đoạn transcript á thì tôi muốn kéo nó
[16:18] à tôi muốn copy cái đoạn transcript và copy nhiều cơ chứ không phải là copy
[16:23] từng từng nội dung hoặc là từng cái câu chữ một thì nó bị lỗi và tôi không có
[16:29] copy và kéo chuột lên được. Rồi
[16:36] Sơn sẽ chụp nó lại này. Đấy chụp nó lại cái context để cho nó biết được cái
[16:41] context ở đây. Thì cái ngữ cảnh ở đây á đó là khi mà
[16:46] tôi giữ con chuột của tôi và tôi kéo nó lên thì tôi không có copy được ở hàng
[16:52] phía trên nữa. Nên á bạn cần phải cho tôi á một cái nút bấm ờ là copy được
[16:58] full transcript đã nói cho tới lúc đấy hoặc á là ít nhất á là tôi kéo nó lên
[17:04] được và nó vẫn có thể á ờ ờ cho tôi copy được toàn bộ những đoạn nào mà tôi đã
[17:12] chọn. Rồi thì thường khi mà Sơn á làm việc á thì Sơn sẽ nhìn thấy được những
[17:17] vấn đề và Sơn sẽ fix nó lại như thế. Rồi thì khi mà bạn build xong á thì bạn đừng
[17:23] reset cái app bởi vì tôi đang làm trên môi trường và tôi đang record thực tế.
[17:33] Đấy thì đây là một cái một cái size project nhá. Đấy mình làm phụ thôi. Làm
[17:37] phụ thôi. Thường là khi mà kết thúc cái chương trình này thì Sơn mới làm. Nhưng
[17:40] mà đây Sơn demo cho mọi người nhìn thấy được rằng Sơn đang quản lý hai cái
[17:44] project như thế nào. Và vừa nãy Sơn cũng nhìn thấy ai đó có một cái câu hỏi á rất
[17:48] là hay đó là mà làm thế nào á để quản lý được nhiều
[17:52] project và có nên nó sử dụng cùng một cái terminal hay không? Thì cái câu trả
[17:56] lời ở đây á đó là mọi người cần nó phải chia việc ra. Ví dụ như á là ở đây đó là
[18:02] một dự án là build to own. Còn đây là dự án cái app meeting thì mình chia nó ra
[18:09] hoặc các là mình phải chia nó ra một cái là front end, một cái là back end chứ
[18:13] mình không nên á là mình gộp chung vào hết tất cả một nơi thì nó lúc đó nó làm
[18:17] nó sẽ bị viết đè lên và mình sẽ bị code sai hoặc là con này nó đá con kia.
[18:28] Đó thì bây giờ nó có việc nó làm này nó đã phan script về rồi. Và cái phiên hôm
[18:34] nay á thì đ vào lúc á 27 tháng 8 và lúc 5:58 để bắt đầu này. Và kéo dài cho tới
[18:40] bây giờ là 2 tiếng 13 phút rồi thì nó có 1124 đoạn.
[18:47] Ok không mọi người? Thì cái này nó đang làm việc, nó đang
[18:54] lấy dữ kiện rồi nhá. Đấy, code khớp với cả từng lời nói. Thực
[18:58] ra ấy là nếu như mà cái app này á nó hoàn thiện ấy, tức là vừa nãy Xuân chỉ
[19:03] cần copy đúng cái đoạn mà Sơn nói với cả Phương thôi thì nó sẽ tiết kiệm được cái
[19:07] thời gian á mà nó phải vào nó pu nếu như mà Sơn muốn demo nhanh. Còn bình thường
[19:12] á thì Sơn không cần cái điều đấy. Như Sơn đã nói á là cái ứng dụng này Sơn
[19:16] build cho một mình xài thôi. Nên nó Sơn chỉ cần bảo rằng là mày hãy chui vào đây
[19:20] mày xem trực tiếp đi chứ Sơn sẽ không cần phải copy đúng cái đoạn đó cho nó.
[19:24] Mọi người hiểu được ý của Sơn không nào? Nên nó Sơn nó làm thì lúc đó mình không
[19:29] có cần phải về tốc độ thời gian để demo cho mọi người thật nhanh. Nhưng ở đây Sơ
[19:33] muốn demo nhanh á thì Sơ mới cần phải copy đúng cái đoạn này.
[19:39] Đấy thì trong cái lúc á mà nó chờ nó làm như vậy nhá thì Sơ sẽ giảng cho mọi
[19:42] người cơ bản như này này và cũng cần á phải setup ra một cái môi trường trước.
[19:46] Thì đầu tiên á là cái khi mà nó viết ra xong cái spec á thì để contribute ở đây
[19:51] đó là Sơn đang collab với cả Phương thì Sơn sẽ cần phải đẩy nó lên trên cái LN
[19:56] đây. Thì cái nền tảng này á Sơn sẽ quản lý toàn bộ những cái mô tả và đặc tả về
[20:01] sản phẩm và những tích những cái isu để cho nó làm việc. Thì cái này Sơn mới
[20:07] setup. Còn là những cái môi trường cũ đi ví dụ như thằng Kima API này thì S cho
[20:12] mọi người xem này. Thì ở đây á nó sẽ ghi ra được á là những cái tích kịch nào
[20:17] đang trong quá trình nó đang cần phải làm in process những cái nào á đang làm
[20:23] sẽ làm to do và cái nào á là backlock là sẽ làm sau và cái nào thì đã hoàn thành
[20:29] rồi. Thì cái này á là Sơn sẽ làm việc cùng với cả đội ngũ của mình. Đó, giả sử
[20:34] như có hai người, ba người kết hợp với cả Asian thì nút này á là nó có những
[20:39] cái tab á nó ghi ra này cần Sơn duyệt này. Đây là spec này thì Sơn sẽ ngồi Sơ
[20:43] đọc cái này. Thì đây á là những cái spec và Sơn sẽ vào Sơn á Sơn sẽ Sơn sẽ
[20:50] feedback với cả con AI rằng á là những cái này á là tôi duyệt cái gì và cái gì
[20:54] cần phải sửa. Thì xong sau đó Sơn copy cái này. Sơn nó bảo rằng á là à hoặc là
[21:00] Sơn bảo rằng là cái mã này này Kim42 á thì tôi đã feedback vào rồi. Bạn hãy
[21:06] vào trong đó bạn xem đi thì nó lại vào nó xem và nó lại nó lại sửa lại theo cái
[21:11] ý của Sơn. Cho đến khi nào mà duyệt xong rồi thì nó mới tạo ra thành những cái
[21:14] ticket này để build. Thì những cái tích kịch này á nó giống như là những cái
[21:18] tính năng mà vừa nãy Minh Phương mới đưa ra yêu cầu ấy thì sau sau đó nó mới
[21:22] build theo từng cái một. Thì đó nó sẽ là cái quy trình để làm.
[21:31] Cái này á thì sau Sơn sẽ giao cho mọi người bài tập để mọi người khi mọi người
[21:36] nghe xong rồi nghe lý thuyết nhìn thấy demo thực tế nhìn thấy Sơn làm xong rồi
[21:41] mọi người phải làm thì lúc đó mọi người mới nhớ được và mọi người mới hiểu chứ
[21:45] không á là có thể sẽ hơi bị lùng bùng đấy đúng không?
[21:50] Rồi phải cần làm thực tế nên Sơ mới nói rằng
[21:55] á là học một nhưng mà phải làm hai là như thế.
[21:59] Bây giờ nhá, nóã xong cái spec cho Sơn này và cái transcript thì đã lấy được
[22:03] rồi. Thì bây giờ Sơn sẽ bảo nó là bạn hãy mở cái
[22:08] cái spec này lên cho tôi để tôi xem trước đi. Và xong sau đấy á bạn có thể
[22:14] đẩy nó lên trên Liner để chúng ta để tôi sẽ duyệt ở trên này.
[22:24] Bạn đưa nó lên trên lin của B to own nhé.
[22:33] Cái này á mình vừa nãy nói không đúng này.
[22:39] Ok. Thì những cái gì Phương nói này mình sẽ
[22:45] xem lại xem phải không nhá. Thứ nhất á là danh sách buổi không có hiện ra tiến
[22:48] độ. Thứ hai là nút đánh dấu á ờ xong á quá nhỏ. Ok. Không có mục lục trong bài.
[22:55] Có phải là vừa n Phương nói cái này không nhỉ? Nút đánh dấu xong quá nhỏ
[23:00] \>> có anh ạ. Cái này là của user
[23:02] \>> à. Ok. Đó chứng tỏ rằng nó không bịa đúng không?
[23:08] Ờ Phương có nói rằng á nộp rồi mà không có sửa được. Ok. Thì Sơn cũng có đề xuất
[23:13] thêm á là phải có cái nút xóa đi chứ đúng không? Ví dụ như vừa nãy Sơn nhìn
[23:17] thấy được rằng á là khi mà mình nộp xong rồi
[23:20] thì mình không có nhìn thấy cái trạng thái gì. Ví dụ như ở đây có một cái nút
[23:23] edit chẳng hạn để mọi người có thể edit được.
[23:28] hoặc á là cái ảnh để mở sang tab mới. Cái này là
[23:35] cái gì Phương nhỉ? Vừa nãy Phương có đề xuất cái này à?
[23:38] \>> Dạ là có cái bài tập ý là mọi người sẽ setup thế là mọi người screenshot cái
[23:42] màn hình đó. Thế nhưng mà khi mà kiểu bấm vào cái đấy để xem là một người làm
[23:46] như thế nào thì ý là cái screenshot thì nó khá là bé đâu. Mở sang cái trang kia
[23:50] thì nó cũng nhỏ đấy anh đó. Nhưng mà nó không mở ngay trong cái trình duyệ của
[23:53] mình mà nó lại mở sang bên kiểu một cái tab khác thì ý là em chỉ đớ thằng thế
[23:58] thôi.
[23:59] \>> Ừ. Ok. Đấy, cái này bổ sung thêm contex
[24:08] bổ sung thêm context cho cái ảnh mở tab mới.
[24:17] Đấy, thì vừa nãy Sơn đang làm một cái động tác á, đó là Sơn làm rõ
[24:22] chắc phải thêm một cái bước nữa. Giả sử như vừa làm làm việc với cả team đúng
[24:25] không? Thì khi mà hỏi à phải có một phải có là hỏi này
[24:33] xong á làm rõ này, đặt câu hỏi này làm rõ này.
[24:39] Nên mình chưa hiểu cái gì ấ thì mình cứ hỏi lại thôi đúng không? Mình phải hỏi
[24:42] lại. Không biết được cái bài được chấm chưa?
[24:53] Ok. Cái này là sẽ cần xem xét. Và có muốn đổi tên thì đổi tên nó nằm
[24:59] cái phần này. Muốn đổi tên phần này thì cái API của cái thằng LN này á nó
[25:06] nằm ở trên One Password. Thì bây giờ Sơ mới bảo rằng á là bạn hãy chui vào đây
[25:10] để bạn để bạn lấy nó bởi vì nó đang viết lên
[25:15] trên cái workspace nó đang liên kết với cả MCP là Kimia Kima API
[25:22] thì mới đưa nó lên trên kia nó chưa biết.
[25:29] Còn bên này á, đấy thì trong lúc đó thì mình có thể mình làm một cái size
[25:32] project nhỏ là đã build xong rồi này. Và tôi không reset nó này. Ok, đúng rồi đó.
[25:39] Ờ ba cái thứ mà mà nó đã sửa này. Thứ nhất á là copy toàn bộ những cái gì mà
[25:44] vừa nãy đang có. Thứ hai á là vùng chọn giờ được lưu vị trí. Thứ ba là kéo quá
[25:49] mép thì tự cuộn. Ok. Đó mình sẽ test lại sau.
[25:54] Với lại á là vừa nãy Sơn test ra có một cái vấn đề nhỏ thôi là khi mà Sơn kéo
[25:58] lên cái này xong Sơ bấm vào copy nó bằng phím tắt thì không được đấy mà nó bắt
[26:05] buộc mình á phải copy cái này thì giả sử như vậy lại đưa nó thêm ngữ cảnh
[26:11] ở đây có một cái mà tôi muốn đề xuất á nhỏ thôi tức là khi mà tôi chọn những
[26:16] cái ô này tôi bấm vào phím tắt là command cộng C nhưng tôi không copy được
[26:21] đó và bắt buộc Tôi phải bấm vào cái cái button copy nên á là tôi muốn rằng á là
[26:27] khi mà tôi chọn nó thì tôi cần M C thì có thể copy được
[26:36] rồi build.
[26:42] Đấy thì trong cái lúc đấy thì Sơn xem rằng mọi người có câu hỏi gì hay không
[26:46] để Sơn trả lời cho mọi người câu hỏi được nhé.
[26:50] Thì đây là cái thực tế mà Sơn làm việc luôn ấy. Hôm bữa là Xuân có đăng lên một
[26:55] cái bài viết đó là ờ Huy, bạn Huy á có qua nhà Sơn chơi thì cùng một lúc đó ấ
[27:03] là Sơn á vừa làm việc với cả bốn cái size project khác nhau đó cộng với cả
[27:08] lên giáo trình cho cái chương trình toán buổi này và sau đó thì Sơn còn trò
[27:13] chuyện với bạn đó nữa. Nhưng mà mình có thể cùng một lúc kiểu mình có thể làm
[27:16] được như vậy kiểu nó rất là nhàn luôn. Đấy,
[27:28] khi nào mà Xuân làm cái setup nhiều project trên các thư mục, nhiều cái
[27:32] terminal có project đó để làm việc hiệu quả. Cảm ơn Sơn. Ok anh Lương. Cái này
[27:38] thì kiểu như chắc là mọi người sẽ yêu cầu một cái video là nó nó đi sâu về kỹ
[27:43] thuật hơn đúng không? Nó kiểu nó chi tiết một chút đấy. Nhưng mà anh Lương là
[27:47] hôm bữa có làm cái bài tập này chưa? Đây này. Cái bài tập này
[27:53] đây này. Anh Lương có làm cái bài tập này chưa?
[27:56] Bài tập đầu tiên này chứ. Đây này. Xong anh á coi từ cái bản PDF này. Đấy, team
[28:02] đã đưa ra rồi thì anh có thể là xem trực tiếp tại đây. Kho anh tải nó về máy. Anh
[28:07] đã tải nó về xong anh ném cho con agent của anh ạ. Nó nó làm cho anh. Anh xem
[28:12] rằng anh đang sử dụng Windows hoặc là Maos thì nó sẽ làm tới cái bước á là anh
[28:17] phải có được những cái terminal như thế này để nó hiển thị lên. Thì cái đó tức
[28:21] là bây giờ tới cái việc á là đôi khi rằng á là đã có hướng dẫn đầy đủ rồi
[28:25] đấy. Chỉ là chưa có video thôi đúng không? Nhưng tài liệu kỹ thuật thì đầy
[28:29] đủ nên á cái cách làm ở đây á là đôi khi mình chỉ cần biết rằng nó nó có tồn tại
[28:34] thôi. Sau đó mình ném cho con AI bảo rằng á đây là cái phần bài tập của tôi.
[28:38] Bạn làm cho tôi cái này và cái kết quả đầu ra á là tôi muốn có cái terminal nó
[28:42] hiển thị ra giống như cái hình thì giống như cái hình là như thế nào? Anh chụp nó
[28:47] lại ở đây thì đây chính là ngữ cảnh đúng không? Em lấy ví dụ nhá. Đây sẽ là cái
[28:53] phiên mà em làm việc đi chẳng hạn. Và em á sẽ sử dụng ở trên thằng cloud
[28:59] ờ desktop. Đúng chưa? Đây sẽ là cái cái bước mà ban đầu mọi người sẽ làm ấy. Đây
[29:05] là bước bắt đầu mọi người sẽ làm á thì chụp nó lại và phải tải nó về cái phần
[29:11] này. Tải cái PDF này về này. Xong á mình á
[29:15] đưa cho con AI của mình mình kéo nó vào thì đây chính là toàn bộ những cái ngữ
[29:20] cảnh mà cần thiết và mình nói chuyện với nó.
[29:23] Đây là cái phần setup để tôi muốn cài đặt những cái terminal có nhiều cái
[29:30] project khác nhau. Bạn hãy xem rằng á là cái thiết bị của tôi đang có những công
[29:35] cụ nào rồi và còn thiếu cái gì nữa thì bạn đề xuất cho tôi cần cài đặt. Bạn
[29:41] chưa cài đặt vội, bạn đề xuất cho tôi thôi. Tôi đọc qua tôi duyệt trước xong
[29:44] sau đó thì mới được cài đặt. Rồi xong lấy ví dụ như vậy nhá. Được không anh
[29:48] Lương? Thì đây là cái ngữ cảnh. Thì cái cách làm ấy thì thứ nhất là mình có cái
[29:55] điều mình muốn. Cái thứ hai đó là cái hình ảnh chụp. Đó thì trong cái video là
[29:59] sẽ có hình ảnh chụp. Anh vào lại anh sẽ nhìn thấy được rằng à Sơn đã làm tới
[30:02] đâu. Anh chụp lại cái màn hình tới đấy. Xong á anh gửi cho nó cái bài tập mà hôm
[30:06] bữa đã giao là cái PDF này. Hoặc là anh copy luôn cái bài tập bài tập này.
[30:14] Anh copy luôn cái bài tập này. Đấy, anh lại bảo với nó tiếp
[30:23] là tôi đang học trong chương trình là build to own và đây là một phần của bài
[30:29] tập nên á là bạn hãy hướng dẫn cho tôi để tôi hiểu được nữa chứ không chỉ là
[30:34] làm hết cho tôi. Rồi xong á là anh cung cấp cho nó thêm
[30:40] bối cảnh. Ví dụ như á là build toon.d thì đây là chương trình. Xong anh á copy
[30:47] đây là link chương trình. Được chưa? Thì đây là một cái mà em sẽ
[30:51] cung cấp cho toàn bộ mọi thứ. Enter cái rồi xong nó sẽ làm việc. Thế thôi.
[30:57] Được không anh Lương? Nó đơn giản, rất là đơn giản vậy đó.
[31:01] Rồi thì bây giờ mới quay trở lại cái cái kia nó sẽ làm tới đâu rồi nhá.
[31:07] Hoặc á là cái phần nào mà anh chưa có được á anh anh hỏi các bạn trong team
[31:12] support trong nhóm của anh nữa nha. Anh trong nhóm Nă đúng không? Tí nữa ai
[31:15] trong team support nhóm 5 mọi người support anh anh Lương nhá.
[31:21] Ờ rồi xong cái mục 3.6 này ý Phương nói chính xác hơn á lúc mà bạn đã ghi bởi vì
[31:27] lúc đó thực ra Sơn nghe còn chưa hiểu nên A nó cũng không hiểu được thì mình
[31:31] phải mới phải có cái bước hỏi lại là như thế.
[31:38] Ok. Thì cái bước chỗ này á là Sơn nó chưa có
[31:48] cái API của LN thì Sơn sẽ cần phải lên để lấy. Sơ sẽ hướng dẫn mọi người cách
[31:54] để lấy nhá. Đây này mọi người vào trong cái phần á
[31:59] là setting ở mục
[32:07] security and access. Ở đây mọi người tạo ra một cái new API mới.
[32:15] Rồi cái này Xuân khi mà Xuân create ra thì nó hiển thị ra nên Xuân sẽ cái này
[32:19] lại nhá. Rồi thì vừa nãy nó copy nó vào rồi. Bây
[32:29] giờ bạn hãy check ở trên Clipboard đi. Tôi đã có API sẵn rồi đấy. Thì bạn hãy
[32:34] sử dụng nó và đưa tài liệu lên trên L nhá.
[32:42] Bạn thấy không ạ? Tức là Sơn không có dán cái API vào mà Sơn nó chỉ lưu nó lại
[32:49] ở trên cái clip. Tức là Sơn sao chép nó. Thì về nguyên tắc á là cái clip B này á
[32:54] nó đã được lưu lại và để giải thích sao cho mọi người hình
[32:58] dung nhỉ. Tức là ở đây á là Sơn đã lưu nó lại rồi
[33:02] này thì nó gọi là cái cái clip botard thì nó sẽ đọc từ trên cái clip botard
[33:08] này để nó truy cập vào trong cái API của Sơn.
[33:13] Đấy Sơn mong là cái giải thích đó nó dễ hiểu.
[33:17] Rồi nó đã vào được đúng cái workspace này này. Ok ngon.
[33:26] Cái phần demo này hơi tốn thời gian một tẹo. Đó thì hiện tại là chúng ta đang đi
[33:32] tới a tới đây phần spec để l này xong sơ sẽ
[33:40] yêu cầu nó viết thành các tích kịch về nhưng mà hôm nay sẽ chưa build. Hôm nay
[33:46] sẽ chưa build nó chỉ đi tới đây thôi. Được chưa? cho show cho mọi người nhìn
[33:49] thấy. Còn á là trên cái GitHub á đây Sơ đã
[33:56] show cho mọi người trên Ghub này thì cái repo ấy của Build to own ấy là Sơn để
[34:00] trên này nhưng cái này để private nhá có mình Sơn nhìn thấy thôi. Đấy thì Sơn sẽ
[34:06] có là cái build to own site là nguyên cái landing page cộng với cả cái nền
[34:12] tảng học tập thì Sơn build nó từ con số 0. Cái này không phải là sử dụng open từ
[34:17] bất kỳ nơi nào hết nhá. Cái này là tự build từ đầu á.
[34:23] Ở đây là trong lớp mình đã có GHub hết chưa?
[34:31] Ok. Cái phần spec đó là tôi duyệt nhá. Xong á bây giờ ấy bạn hãy viết ra thành
[34:36] những cái ticket isu ở trên build to luôn đi. Và sau đó bạn giúp cho tôi á
[34:45] đánh dấu ra á là cái nào á là vai trò của user, cái nào là vai trò của team
[34:50] support và cái nào là vai trò của admin. Cộng với việc á là hãy giúp cho tôi phân
[34:55] loại ra xem rằng á là cái thứ tự ưu tiên có impact cao và cái nào á thì làm sau.
[35:01] Đấy thì cho tôi nhìn thấy được. Đây á là Sơn đang demo cho mọi người á
[35:10] nhìn thấy được rằng á là cái cách mà chúng ta sẽ sẽ hợp tác với cả con người.
[35:15] Thì thì những cái những cái công cụ như vừa nãy Sơn chia sẻ cho các bạn ấy ví dụ
[35:19] như trên Lin ở đây á thì đây là chúng ta đang hợp tác với cả team con người đấy.
[35:27] Đây này. Nó nó tức là cái cái cái yêu cầu vừa nãy á là Sơn còn chưa kịp enter
[35:33] thì nó đã viết cho Sơn thành ra những cái issue luôn rồi. Bởi vì cơ bản rằng
[35:37] là trong cái yêu cầu vừa nãy của bạn Minh Phương á là nó có có cái điều đấy
[35:42] nên nó Sơn enter luôn đi. Thì nó viết ra cho Sơn nó mười mấy cái yêu cầu này.
[35:46] Mười mấy cái yêu cầu đọc thử nhá. vào đồ thử này
[35:53] xem nào. Làm cái bui từ 5 cho tới à không nó làm từ cái 10
[36:00] cho tới 16. Đây cái 10 cho đến 16 này.
[36:05] Đấy cái cái cái tính năng đầu tiên nhá. Xóa bài nộp của chính mình này là Phương
[36:10] á nộp một cái một cái bài chỉ ghi chữ test thôi. Và rồi muốn nộp bài thật thì
[36:15] không có xóa được và cũng không có sửa được. Thì cái bài test này á nằm vĩnh
[36:19] viễn trong lịch sử. Được chưa? Đây là vấn đề. Đây là vấn đề. Và
[36:25] sau đấy á là sẽ cần nó phải yêu cầu rằng á là phải có cái delete và xóa cái lần
[36:31] nộp mới nhất của chính mình và không xóa được của người khác. Hợp lý và không có
[36:35] xóa được lần cũ hơn. và xóa trong cái xóa xong á thì lần trước đó thành cái
[36:42] bản cả lớp mà nhìn thấy. Thì đây là cái tính năng đầu tiên. Rồi
[36:48] xong check cái 11 xem nào. Hiện tiến độ á ngay ở danh sách theo
[36:53] buổi. Ờ ví dụ như là Phương á đang học á 3 trên
[36:58] á s mục mà bên ngoài thì không thấy gì thì cái dữ liệu có sẵn ở cái bảng lesson
[37:07] program thiếu đúng phần hiển thị. Cái này phương em muốn nó trông như thế nào?
[37:13] Ví dụ như em muốn hiển thị cái danh sách à quên cái cái cái tiến độ á danh sách
[37:18] buổi nó hiển thị ở đâu
[37:20] \>> không? Kể anh anh vào lại cho em cái campus rồi anh vào lại cho em
[37:23] \>> đấy. Đây
[37:25] \>> rồi cái buổi học đấy. Bây giờ nhá ngay ở trong cái danh sách này thì ý là bây giờ
[37:29] có một hai buổi thôi thì em có thể biết là à em đang xem lại đến buổi nào thế
[37:33] nhưng mà sau nó rất là nhiều thì em không biết là em đang xem đến phần nào
[37:36] ấy. Chẳng hạn là em đang học đến 3/5 hay là cái gì của buổi một ấy. Đó thì nó lại
[37:41] đang ghi là sáu video bên ngoài thôi. Đấy em ý là view ngay bên ngoài.
[37:44] \>> Anh hiểu. Tức là thường á là cái nền tảng học tập á là em vào em nhìn thấy
[37:49] cái này luôn. Ừ tại vì em còn ở đây á là mình đang
[37:53] build á là mình nhìn thấy được cái cấu trúc ở bên ngoài tổng quan sau đó mình
[37:57] bấm vào bên trong thì mình mới nhìn thấy cái chi tiết nên á là thực ra là nó chỉ
[38:02] cần thế này thôi là xong
[38:05] \>> được chưa? Nó chỉ cần như này thôi là xong chứ không cần phải có cả bên trong.
[38:08] Ok. Cái này anh anh anh sẽ anh sẽ fix đơn giản thôi.
[38:18] Đây nhá. Thì mọi người thấy này nó đã viết ra sơn xong rồi nhá. Nó viết xong
[38:21] rồi này. Ờ nó chia ra vai trò luôn này. Vile là admin này.
[38:26] Đấy vai trò là support. V trò là user và cần nó phải sắp xếp theo ưu tiên như
[38:33] nào? Vẫn đang viết đấy. Nó đang vẫn đang viết này. Thấy chưa? Mọi người nhìn thấy
[38:36] update không? Nhìn thấy màn hình nó thay đổi không?
[38:42] Đấy, done thì nên duyệt nó lại thôi, nên đọc lại thôi. Còn á là cái cách mà Sơn
[38:48] đọc ấy là Sơn sẽ đọc từ cái chính này trước. Đây là toàn bộ những cái spec này
[38:52] vừa nó viết ở trong cái máy cá nhân của Sơn. Xong đó nó đẩy lên trên cái Lin
[38:58] này. Thì đây là cái spec về cái campus về ba
[39:02] vai trò mà vừa nãy nó trích xuất ra từ transcript. Và đây
[39:07] là mọi người có hình dung được cái cái flow mà Sơn đã làm không?

BUỔI 2 - TRANSCRIPT 06 - BẢN GỐC
Thời lượng video: 27:06
Giữ nguyên bản chép lời tự động và mốc thời gian; chưa hiệu đính nội dung.
[0:00] Ok nhỉ? Hô hôm nay mọi người còn câu hỏi gì nữa không? Ờ để tổng kết lại cái buổi
[0:05] hôm nay á là chúng ta đã đi được hết cái phần này hay chưa? Về mục tiêu, môi
[0:12] trường làm việc mà bạn với cả agent sẽ hợp tác. Đây là Sơn nó làm việc ở trên
[0:17] Liner và trên GitHub là Sơn nó cộng tác với cái agent là môi trường đấy cộng với
[0:21] cả ứng dụng là app Fem đó. Sơn hay cho nó transcript ngữ cảnh đầy đủ hết đó. Và
[0:27] Sơn sai cái công việc này, Sơn đồng bộ cái công việc này với cả team của Sơn.
[0:30] Ví dụ như vừa nãy Sơn demo cho các bạn, Sơn làm việc với cả bạn Minh Phương. Sơn
[0:34] nó sẽ chia quyền cho bạn nó trên những cái công cụ mà đang làm việc
[0:40] và nối AI vào cái hệ thống thật của mình là qua cổng API và MCP. Và cách để bảo
[0:46] mật những cái dữ liệu này như thế nào, ở đâu và những cái quy tắc cần phải bảo
[0:51] mật. Thì cứ nhớ là nếu ở trên local á thì sử dụng thằng One Pass đó. Và khi
[0:58] nào cần gì á là nó sẽ khỏi quyền mình, nó không có được tự ý để nó làm. Nhưng á
[1:02] nó sẽ có một cái bất lợi ngược lại một chút đó là mình sẽ cần phải bảo rằng bạn
[1:07] phải vào đây để lấy bởi vì nó đang quen lấy ở trong cái ENV. Nên nếu như các bạn
[1:12] mà không có cái gì nó liên quan về dữ liệu doanh nghiệp cần bảo mật sâu ấy thì
[1:17] các bạn cứ để cho nó open một chút, nó thoáng được một chút, không cần phải quá
[1:19] kỹ đâu. Còn nếu như mà các bạn ờ ờ có nhiều dữ liệu bảo mật thì các bạn đã nên
[1:27] đổi đánh đổi tới một sự hơi bất tiện nhẹ.
[1:31] Ờ bởi vì mỗi một lần nó cần dùng á thì nó phải hỏi quyền. Đấy. Rồi một cái repo
[1:36] ở trên GitHub. Thì sau cái buổi hôm nay này thì mọi người á trong cái buổi một
[1:40] đúng không mọi người đã có được cái sản phẩm mà mọi người muốn build rồi, cái
[1:44] vấn đề mà mọi người muốn giải quyết rồi. Và hôm nay mọi người đã biết cách để
[1:48] viết ra được một cái đặc tả về cái spec nó như thế nào đẩy lên trên lin làm việc
[1:52] rồi. Thì mọi người cần nó phải tạo ra được á là một cái repo ở trên GitHub.
[1:57] Mọi người đẩy nó lên và làm thế nào á để mọi người có thể lấy được cái API của
[2:04] GitHub và sau đó giao cho agent để nó tự làm được mấy cái này. Tức là mấy cái
[2:08] GitHub như này là Sơn không có ngồi để tạo bằng tay. Mọi người hình dung không
[2:11] ạ? Mà Sơn ấy bảo rằng á là bạn hãy đẩy lên trên GitHub thì nó tự làm hết. Ok
[2:17] chưa? Thì đó sẽ là nằm trong cái chuỗi bài tập của các bạn nhá. Là các bạn cần
[2:21] phải có một cái repo đẩy lên trên GitHub bằng cái dự án mà bạn muốn làm thật.
[2:27] Và một cái spec có một trang bạn đẩy nó lên trên liner bạn đưa các isu các tích
[2:32] kịch các tính năng mà các bạn muốn xây đưa lên trên liner và các bạn cũng cần
[2:37] nó phải kết nối với cả cổng API vào. Rồi những cái gì á mà các bạn á cần nó phải
[2:42] vẽ nó ra cần nó hiển thị hóa hình ảnh hóa thì bạn cần phải có kiến trúc phải
[2:46] có architecture hoặc là diagram được chưa? Thì đây là những cái mà chúng ta
[2:51] đã đi được trong cái buổi ngày hôm nay đúng không nhỉ? Hình như còn đi hơn
[2:54] luôn. Sơn demo cho các bạn rất là chi tiết đó cụ thể á là thông qua cái việc á
[2:59] là Sơn á làm trực tiếp đó chứ không phải là từ hình ảnh mà Sơn đi hết cho các bạn
[3:03] á cả nguyên một cái flow mà Sơn làm việc theo đúng một cái chu trình mà Sơn làm
[3:07] việc hàng ngày. Ở Việt Nam bây giờ của mình nó đang
[3:16] 11:00 đêm đúng chưa? Đấy thì cái cái cái go target của Sơn là thường á là Sơn nói
[3:23] đúng hai tiếng bởi vì trước đây á Sơn tổ chức chương trình á là cứ nói bảo là tổ
[3:27] chức nói hai tiếng nhưng mà thường là cứ 3 tiếng 4 tiếng 5 tiếng đồng hồ thì Sơ
[3:31] thấy rằng là thứ nhất á như vậy nó không hiệu quả. Thứ hai á là mọi người nghe
[3:35] nhiều á thì mọi người lại ít làm nên á là Sơn muốn rằng á là nó phải có sự cân
[3:39] bằng. Mọi người nghe xong mọi người học xong rồi mọi người vẫn phải có thời gian
[3:44] để mọi người thực hành. Đấy thì nó làm xong hết rồi đấy.
[3:54] Ok nhá. Thì trước khi kết thúc có một hai người là muốn nói hay muốn chia sẻ
[3:59] hay muốn đặt câu hỏi gì cuối buổi này không?
[4:10] Và trong quá trình mà Sơn chia sẻ ấy thì Sơn nó sẽ luôn luôn khi mà bước qua một
[4:15] cái module mới á thì Sơn sẽ hỏi rằng á mọi người có câu hỏi gì á thì mọi người
[4:21] cứ đặt câu hỏi mạnh dạn nhá. Đấy cái đó là quyền lợi của mọi người. Mọi người
[4:24] đặt câu hỏi mạnh dạn. Ờ đừng có ngại trong việc này. Và mọi người đặt câu hỏi
[4:28] thì biết đâu á ai đó trong cái buổi này cũng muốn đặt câu hỏi đó nhưng mà họ họ
[4:32] chưa kịp đặt. Và mọi người câu hỏi của mọi người nó sẽ giải quyết được luôn cái
[4:35] câu hỏi của mọi người khác. Nên đừng có sợ là à nó bị mất thời gian chung hay gì
[4:39] cả. Chúng ta lớp chương trình như này chúng ta nên có sự tương tác chéo với
[4:42] nhau chứ không phải là tương tác một chiều. Không phải là một mình nó xong
[4:46] mọi người ngồi nghe mọi người nên chủ động hơn. Được chưa?
[4:51] Ok không cả nhà? Đó từ buổi thứ ba, buổi thứ tư hoặc là từ bây giờ đến cuối cái
[4:56] chương trình này nó phải như thế. Sơn chào Sơn nhá.
[5:01] \>> Ok anh Phương. Sơ cho mình hỏi là ví dụ như một người
[5:06] mà đang bán cái sản phẩm mà chạy trên nền tảng thuê á thì mình nên là một cái
[5:11] mini tool ghép vào cái đang có hay là tch ra những dựng
[5:17] \>> sao? Từ từ từ từ. Anh anh Vương anh hỏi lại giúp em. Em vừa em nghe chưa rõ.
[5:21] À tức là mình có à tức là người mà đang bán sản phẩm mà chạy trên nền tảng đang
[5:27] thuê
[5:29] \>> đó thì mình nên làm cái mini tool ghét vào cái đang có
[5:35] hay là mình tự dừng riêng. À ok anh Vương. Cái này nó tùy vào cái
[5:44] năng lực và cái khả năng của mình nên là nếu như mà mình build nhiều rồi á thì
[5:49] mình build một cái nền tảng đôi khi nó cũng rỗng dễ như một cái mini tool. Còn
[5:53] nếu như mà mình mới build á thì theo em đề xuất thất á là anh cứ build nhiều cái
[5:57] để anh có được cái kinh nghiệm tổng thể trước xong sau đó anh bill một cái nền
[6:01] tảng sau. Bởi vì bu một cái nền tảng á thì mình nghĩ rằng á là AI nó làm nhanh
[6:06] thì đúng có thể rằng nó chỉ xây cho mình á trong khoảng 1 ngày 2i hai ngày là
[6:09] xong. Nhưng để mình duy trì mình cho nó ấy thì nó là cái câu chuyện á cả nhiều
[6:14] tháng thậm chí cả năm nên để anh có được những cái mà kiểu như dùng được ngay á
[6:19] thì anh build những cái mini trước. Với cả với cả cái triết lý ở đây này là
[6:28] cái nào á người ta đang làm tốt rồi á thì mình đừng cố để mình build lại.
[6:33] \>> Đấy mình đừng cố để build lại. Mình chỉ build á khi mà người ta làm thực sự
[6:36] không tốt để giải quyết vấn đề cho mình ấy hoặc là mình cố để mình tìm ra được
[6:41] những cái giải pháp rồi nhưng mình không có một cái giải pháp nào để đáp ứng được
[6:45] thì mình mới bill. hoặc á là anh quyết định bu bởi vì anh có thị trường, anh có
[6:49] người dùng và anh sẵn sàng anh đầu tư thời gian, tiền bạc đó và cái công sức
[6:55] của anh vào trong cái sản phẩm đấy thì anh mới bill. Nhưng anh phải nhớ rằng
[6:58] anh phải có cộng đồng và phải có người dùng rồi ấy chứ không á mình build một
[7:03] cái vấn đề không tồn tại thì nó hơi bị mất thời gian của mình. Đấy thì kinh
[7:08] nghiệm của em là thế. Với lại một cái cái ý của mình nói nữa
[7:12] tức là mình ví dụ nha mình ví dụ giống như là một cái nền tảng lớn nó đang
[7:17] thiếu một cái một cái gì đó nhưng mà nền tảng đó mình thuê nên mình bị phụ thuộc
[7:23] mình không thể làm gì vì mình không sở hữu cái sổ cod thành ra là mình nên
[7:29] buill một cái để ghép vào cái nền tảng đang dùng đó không ý mình nói như vậy
[7:40] Em hiểu ý của anh.
[7:44] \>> Chẳng hạn đi. Chẳng hạn như là mình nói hơi nhỏ đúng không?
[7:48] \>> Không nghe được. Nghe được. Anh nói chậm lại một chút thôi để mọi người nghe được
[7:51] thôi chứ em nghe được.
[7:53] \>> Chẳng hạn như là lúc trước mình có nói là cái vô ha level đi thì nó sẽ không có
[8:01] cộng thanh toán strike được. vì không thể mở công ty ở Mỹ thì mình dùng cái
[8:08] thằng xe pay mình đấu nối thẳng vào trong cái hệ thống nó đang dùng luôn thì
[8:12] hiện tại nó vẫn đang tự động được. Đó ý nói như vậy.
[8:16] \>> Ừ thì thế nhưng được rồi. Có nghĩa là anh chỉ nên build á để giải quyết được
[8:20] đúng cái vấn đề nhu cầu đó thôi chứ đừng nên tự build một cái nền tảng bởi anh
[8:25] build một cái nền tảng anh anh có thể mất nhiều năm ấy.
[8:29] \>> Ừ.
[8:31] \>> Rồi cảm ơn s. Ok anh chỉ nên thế thôi.
[8:39] \>> Hello anh Sơn anh cho em hỏi một chút.
[8:41] \>> Ừ chào bạn nhá. Dạ.
[8:45] Lúc nãy anh có nói về cái RBO ở trên GitHub á thì hiện tại thì em cũng đang
[8:51] đang vọc vạch cái con cloud thì em để nó trên cái ổ nhớ của máy. Thì như hồi nãy
[8:59] anh anh anh có nói là mình sẽ đẩy lên trên cái RBO của GitHub. Vậy thì mình
[9:04] nên đẩy trên lên trên đó hết luôn hay là mình à một vài con mình có thể thích
[9:08] mình giữ ở máy cũng được, một vài con mình sẽ đẩy lên đó. Và nếu như mà giữ
[9:12] ống máy thì nó có rủi ro gì không anh?
[9:15] \>> Ừ rủi ro là giả sử máy em bị mất ờ máy em
[9:21] bị reset hết tất cả dữ liệu thì em sẽ bị mất hết tất cả dữ liệu đấy. Ờ còn trên
[9:26] GitHub ấy thì dĩ nhiên em không nhất thiết em phải đẩy hết toàn bộ. Em chỉ
[9:30] thấy rằng cái nào em cần sao lưu. Đấy và trên GitHub á nó sẽ là một cái môi
[9:34] trường rất là tốt để cho các developer hoặc là trong team mình có thể cùng làm
[9:39] chung một dự án. Ấy thì nếu như khi nào em có một trong
[9:43] hai nhu cầu đấy thì em cần đẩy lên trên git hub.
[9:47] \>> Dạ. Có nghĩa là nếu như mà mình muốn share
[9:51] cái cái dự án của mình cho những người khác
[9:55] \>> ờ họ cùng tham gia vào thì mình nên để lên trên đó. Và em có một cái thắc mắc
[10:01] nữa là nếu như mà mình đẩy hết lên trên GitHub thì bản thân mình khi mà mình sử
[10:09] dụng tại vì em còn mới cho nên là đôi khi nó anh chị biết nhưng mà em thì em
[10:13] không có rành cái này cho lắm thì nó có nó có giới hạn cái gì cho cái người dùng
[10:19] không hay là mình có phải trả phí cho nó để là mình có thể đẩy càng nhiều lên đó
[10:24] không? có nghĩa là cái cái lượng mà mà các cái con AI mình tạo ra.
[10:31] \>> Ừ. Về trả phí thì thì em chưa cần phải care về việc đó lắm đâu. Thứ nhất là
[10:36] team em nhỏ. Thứ hai á là cái dữ liệu em đẩy lên em sử dụng nó không quá nhiều để
[10:41] em cần phải trả phí. Thực ra GitHub bây giờ anh vẫn dùng miễn phí mà. Chắc anh
[10:44] dùng anh dùng cũng gọi là dùng nhiều luôn ấy. Thì có một cái dự án cho anh
[10:49] trả khoảng 20 đô một tháng thôi. Có nghĩa anh dùng nhiều theo góc góc độ
[10:52] doanh nghiệp ấy thì anh mới cần phải trả tiền. Chứ còn cơ bản rằng á là em dùng
[10:56] gọi là tẹt ga luôn thì em không không có phải tốn tiền em thoải mái đi.
[11:00] \>> Dạ. Vậy an toàn nhất là mình đẩy lên đó hết đúng không anh? Đẩy đẩy lên đẩy cái
[11:05] project lên trên mà anh nói trên đó hết.
[11:07] \>> Dạ. Ok. Em đẩy lên đi thói quen và em tập để sau này khi mà em có team đội ngũ
[11:12] rồi thì mọi thứ em đã set up xong. Dạ ok em cảm ơn s thắc mắc em hỏi thêm ở
[11:18] những chương trình.
[11:19] \>> Ok bạn bảo nhá.
[11:27] \>> Ờ bạn bạn Thành bạn Thành muốn đặt câu hỏi hả? Mời bạn Thành nha.
[11:32] Dạ thì mình có một cái câu hỏi như này thì bây giờ mình cũng là người phát
[11:36] triển về phần mềm á nên là mình có một cái góc thắc mắc là mình hiện tại thì
[11:40] mình đang tập trung ở cái nhiều ở cái vấn đề là mình lấy tính năng từ người
[11:43] dùng. Nhưng mà khi mà một cái feature mình mới mình sinh ra á thì cái việc mà
[11:48] mình làm sau đó mình đồng bộ với cái phần mà UI US và cái phần mà cái cơ sở
[11:54] dữ liệu bên dưới á thì Sơn có thể chia sẻ thêm một một cái ý về đó không? Bởi
[11:59] vì mình cũng đang thấy nó hơi nó gọi là cái mà nó khác với cái quy trình mà tụi
[12:04] mình đang làm phần mềm á.
[12:06] \>> Ừ. Kiểu như là anh em mình
[12:10] \>> khi mà cái phờ nó đi rồi á là cái những cái phần kiến trúc về dữ liệu của mình á
[12:14] nó cũng phải đi theo và ngay cả cái việc mà mình thiết kế lại cái giao diện bên
[12:18] trên á nó cũng phải đi theo luôn. Còn nếu mà mình để chạy liên tục vào cái
[12:23] feature không á là hầu như là những cái luồng vi sau á và một thời gian dài mình
[12:27] phát triển á là nó sẽ không còn giữ cái tính toàn vẹn nữa và nhiều lúc là nó sẽ
[12:31] vỡ cái cờ sơ liệu và nó ảnh hưởng tới cả cái performance của mình luôn.
[12:36] Thì cái hướng của mình mình sẽ xử lý cái đó như thế nào ạ?
[12:40] \>> Ừ. Cái anh có cái case nào nó cụ thể về cái quá trình mà anh anh anh làm mà anh
[12:45] có thể nhớ lại và anh mô tả ra được không?
[12:48] Ví dụ như mình này mình cũng đang thiết kế nhưng mà cái phần mềm về trường học
[12:51] đi chẳng hạn thì mình sẽ có những cái chờ về mình lên lớp hoặc là mình chuyển
[12:56] lớp hoặc là mình đổi từ trong cái nhóm đó nó sẽ có những lớp mà những cái bé mà
[13:02] đổi từ cit cit này qua cit kia thì khi mà mình giữ cái feature ban đầu á là
[13:07] mình chỉ thực hiện mình chuyển lớp thôi nhưng mà trong một số cái tình huống á
[13:12] khi mình chuyển lớp mình cần phải lưu lại cái lịch sử của lớp và mình phải đưa
[13:17] những cái thông số đi kèm. Bây giờ là mình chuyển tình trạng sức khỏe cho bé,
[13:21] mình chuyển những cái tình tình trạng về à sức khỏe y tế, học phí để mình di
[13:26] chuyển từ lớp cũ qua lớp mới nếu mà họ vẫn còn nợ học phí. Thì nếu mà mình
[13:31] những cái feature mình phát sinh thêm á là lúc trước là mình hay đẩy cho clot để
[13:35] nó tiếp tục nó nó đẩy feature nhưng mà sau một thời gian lại á còn một thời
[13:40] gian mình chạy cái lại cái dữ liệu á là những cái bộ dữ liệu cũ nó sẽ bị mất và
[13:44] mình sẽ không có kiểm soát được lại cái dữ liệu cũ.
[13:48] Đó là một cái mà mình mình cũng đang rất là lăng tăng khi mà mình cứ mình nói
[13:52] chung là mình cũng đang cho chạy agent chạy liên tục đấy. Và sau khi chạy một
[13:56] thời gian rồi á là lúc mình mình muốn kiểm tra lại hoặc là mình muốn muốn là
[14:01] nó không có một cái cơ chế nào để mình kiểm soát được là cái dữ liệu mà mình
[14:05] thay đổi rồi thì làm sao đó để mình rollback lại cái version cũ mà mình cần.
[14:11] \>> Ừ. Ô mà cái dữ liệu đó là cái dữ liệu liên quan về gì với cả vừa nãy anh đang
[14:15] hỏi em về thiết kế về UI UX và
[14:19] \>> có nghĩa là đã ban đầu là fe nó phải chung một câu hỏi không? Dạ đúng rồi.
[14:23] Bởi vì cái đó là nó phải đi chung với nhau. Mình lúc nào mình cái buổi học hôm
[14:28] nay của mình á là mình đang nói về future phía trên thôi. Còn những cái nào
[14:32] mà ảnh hưởng tới cái luồng người dùng á là mình có phải giống như là mình có đẩy
[14:36] vô trong cái memory hay là đẩy vô trong cái cái cái prom của mình nè để mình ép
[14:42] những cái cái skill cho nó đi kèm hay không.
[14:46] \>> Ừ. Ờ ok anh Thành. Đây đó là đúng gọi là kiểu developer engineer đi hỏi vi coder.
[14:55] Một người chuyên về kỹ thuật hơn là đi hỏi một người ít chuyên về kỹ thuật hơn.
[14:59] Rồi như nhưng cái cách mà khi mà em làm về sản phẩm ấy thì thực ra thực tế ra là
[15:04] cũng có nhiều lần đập đi xâ lại rồi ờ
[15:08] \>> hoặc á là build cái tính năng này không có hợp rồi xong á thay thế cái khác hoặc
[15:12] á là phải chèn lên những cái thứ mớ rồi thì cái nhưng mà cái kinh nghiệm của em
[15:16] á ví dụ nhá về thiết kế đi thì em sẽ luôn luôn có một cái bộ system design
[15:21] thì giả sử như á là system design sẽ lưu ở đâu một là trên fma hai á là bằng tài
[15:26] liệu ở trên line và trong cái tài Tài liệu này phải mô tả ra được á toàn bộ
[15:30] những cái gì liên quan về system design. Thằng đang nghĩa hôm nay em chưa nói về
[15:34] cái điều này đâu nhưng mà cái system design này á nó sẽ có bao gồm á là những
[15:38] cái là màu sắc thương hiệu này, logo này, cách hiển thị này, về màu về kích
[15:42] cỡ chữ này. Nói chung là rất là chi tiết về một cái bộ system design hoặc bao gồm
[15:47] cả component nó sẽ như thế nào để sau này khi mà team mình có build một cái
[15:53] fanel mới thì đảm bảo rằng á nó cũng phải đi theo cái system design đấy.
[15:58] Nhưng nếu như mà làm việc theo cách của một bạn thiết kế hoặc là một bạn product
[16:02] manager ấy thì sẽ một á là môi trường làm việc của thiết kế sẽ nằm ở trên
[16:06] Figma, môi trường làm việc của Product Manager sẽ nằm ở trên Liner nhưng môi
[16:11] trường của developer á thì nó lại nằm ở trên GitHub cơ nên là ờ đấy thì những
[16:17] cái gì á mà liên quan tới GitHub bởi vì developer mới chính là người buill chính
[16:22] thì lúc này á là mấy cái component ấy hoặc là cái system design á là em đưa nó
[16:26] lên thẳng ở trên GitHub để sau này á khi mà mỗi lần á cần sử dụng liên quan tới
[16:32] thiết kế á thì clot á nó sẽ chui vào đó nó đọc trước à đây là system design của
[16:36] công ty thì nó sẽ thiết kế theo đúng cái mẫu tiêu chuẩn đấy. Đấy ví dụ màu sắc
[16:41] thương hiệu, background, kiểu chữ, cái cách thông báo như thế nào, pop up ra
[16:46] sao là nó phải đi theo cái luồng của mình. Thì đó nó là cái câu trả lời của
[16:50] em về cái phần thiết kế về UIX FN mà em thường hay làm.
[16:55] Rồi xong khi nào mà mà thiếu cái gì á là em sẽ bổ sung thêm đó. Ví dụ như là à
[17:00] cái này là mình chưa được định nghĩa cho nó thì lần sau á mình mới có định nghĩa
[17:04] thì mình mới đưa nó lên trên đó để nó update.
[17:09] \>> Có nghĩa là mình vẫn đẩy ra những cái bộ skill hay là bộ MD trực tiếp vào trong G
[17:13] luôn. Nhưng mà mình định nghĩa với cái ngôn ngữ là của m bạn lập trình.
[17:18] \>> Ừ. Đúng không? Bởi vì mà em bởi vì Thành thấy là khi mà mình mở cái file thiết kế
[17:24] trên FMA á khi mình chuyển qua MD hầu như là nó cũng chỉ giữ được gọi là cái
[17:29] phần mà nội dung về dạng dạng trpt thôi.
[17:33] \>> Ừ.
[17:33] \>> Còn về cái mặt hình ảnh thì nó sẽ không có giữ được chính xác.
[17:36] \>> Đó là cũng là một cái cái mà vấn vấn đề mà mình khi mà mình kiểm soát lại cái
[17:40] phần mà UI á.
[17:43] \>> Yes, đúng rồi đó. Thực ra là cái đó nó cũng là vấn đề của
[17:48] nhiều team ấy. Lúc trước đây á là em là bên công ty của em thực ra cũng không
[17:52] giải quyết được vấn đề đó đâu bởi vì thiết kế không đồng nhất một chút nào
[17:56] cả. Thậm chí rằng Figma đã làm ra rất là rõ rồi á nhưng mà developer đẩy lên nó
[18:01] vẫn kém chất lượng như thường. Thì mình hay đổ lỗ cho là AI thiết kế kém. Nhưng
[18:07] về sau em mới phát hiện ra là à mình mới chỉ có thiết kế dạng là theo code thôi.
[18:12] Có bạn thiết kế chưa chắc đã nhìn thấy được cái những cái gì mà developer đang
[18:16] làm nên lúc đấy em mới phải thiết kế ra một cái chuẩn là system design của công
[18:20] ty. Rồi xong sau đó em định nghĩa nó ra luôn nha là cái system design này nó
[18:25] định nghĩa như thế nào bằng chữ và định nghĩa như thế nào bằng code. Thì code
[18:30] thì em đẩy nó lên trên những cái component và để cho AI làm. đó thì cũng
[18:34] kết nối với các skill để sau này nó biết rằng à cái này cần thiết kế fan nhá thì
[18:38] nó sẽ biết chọp vào đâu, nó sẽ lấy dữ liệu đâu để nó làm quy trình như thế
[18:41] nào. Đúng rồi đấy.
[18:46] \>> Dạ. Vâng.
[18:48] \>> Còn một cái thứ hai nữa là liên quan tới về phần dữ liệu đó thì mình cũng cũng
[18:52] cũng chưa có hình dung mà khi các bạn làm với agent nó như thế nào đó. Sơ
[18:58] \>> dữ liệu à về cái text thì anh đang lưu dữ liệu ở đâu? Database các thứ như thế
[19:01] nào? Toàn bộ là mình mình xài Mongo với Bry.
[19:07] Ừ. Bry hết.
[19:08] \>> Ừ. Nhưng mà liên quan về dữ liệu thì cái câu hỏi của anh là gì?
[19:12] \>> Khi mà mình cái cái bởi vì mình luôn cho chạy vài con nó chạy nó develop cùng lúc
[19:18] thì khi mà nó chạy á là cái bộ dữ liệu ấy nó sẽ không còn đúng như cái bộ dữ
[19:22] liệu tại cái thời điểm mà mình thiết kế ban đầu.
[19:25] \>> Ừ. Giống như mình nói là mình sẽ thêm một cái tính năng mới thì những cái cột
[19:28] những cái bản biểu nó đã nhảy nó đã thêm rồi thì trong cái bộ mà dữ liệu ban đầu
[19:34] nó khi nó chạy á là nó sẽ soát cột là khi đó là những cái câu nó sẽ không còn
[19:39] đúng nữa như ban đầu. Đấy là khi nó gọi là nó bị lỗi ngầm á. Lỗi ngầm có nghĩa
[19:45] là khi mà cái action đó nó phát triển được feature mới nó lại sinh ra những
[19:49] cái lỗi ở những cái feature cũ. Đó đó nên là cái cái chỗ đó là mình cũng chưa
[19:53] có kiểm soát được. Ừ đúng rồi. Thì thực ra là nó cũng liên
[19:58] quan về cái ngữ cảnh nữa. Ví dụ như ngữ cảnh context của nó nó chỉ có 1 triệu
[20:03] token thôi. Trong khi đó ấy là cái công việc mà nó liên quan và liên đới á nó có
[20:08] thể nó lại cần phải tổng ít nhất phải 5 triệu token đi chẳng hạn. Nhưng mà nó
[20:12] cũng không bao giờ nó sẽ nó sẽ tự dùng hết tất cả 5 triệu cái token đó. Ngay cả
[20:16] khi mà có 5 triệu token thật. thì mình vẫn phải có những cái đặc tả hoặc là
[20:21] những cái yêu cầu của chính mình hoặc là những cái checklist của chính mình để
[20:25] mình bảo với nó rằng là à khi mà làm công việc này thì bạn cần phải chui vào
[20:28] đây để là bạn đạn lấy dữ liệu nhé. Rồi thì em có làm một cái bước đó là
[20:34] trước đây em làm thủ công thôi cũng không có theo kiểu developer hay gì cả
[20:38] nhưng em hay làm ra các workflow workflow hoặc là những cái pine á bằng
[20:42] bằng dog thì khi nào á liên làm công việc liên quan tới công việc gì thì em
[20:47] bảo rằng bạn hãy đọc cái workflow này đi. Bởi vì em xây cái workflow đó rồi
[20:51] thì mỗi một khi á nó làm tới cái workflow đấy thì nó thì á làm xong rồi
[20:55] thì em lại cập nhật nó thêm mới vào để cho nó hoàn thiện hơn. Em lấy ví dụ như
[21:00] em làm con Kima API đi thì bây giờ nhá các hãng á họ sẽ ra các model mới và các
[21:05] model như thế này á ví dụ như á là dips đi chẳng hạn thì em sẽ lấy từ trên
[21:11] năm cái provider khác nhau của dipick thì bây giờ á là nó sẽ có rất nhiều cái
[21:15] công đoạn công đoạn này rất là dài nhá em mô tả để cho mọi người hình dung luôn
[21:19] nha là thứ nhất là là add cái model này vào này xong á là tính được cái giá
[21:24] thành mà giá mua, giá bán và giá nhập này xong á là deploy nó lên trên nền
[21:29] tảng của mình này, xong nó viết được mô tả này và testing này. Đây thì đây là
[21:33] giai đoạn của developer. Xong khi mà testing xong, verify xong nó đã hoạt
[21:37] động được và đo được cái up time thời gian của nó bao nhiêu thì đẩy lên dữ
[21:42] liệu ở trên document để cho người dùng khác nhìn thấy public và đẩy lên trên
[21:48] lms.root gì đấy để cho bọn AI có thể chọt vào đây
[21:53] để có thể đọc được nó. Rồi viết ra thành một cái bài viết trên blog và viết ra
[21:58] thành chen lock để cho developer nhìn thấy được. Thì đấy nguyên cả một cái
[22:02] workfow như vậy thì ban đầu á là em không có một cái workflow đầy đủ như
[22:05] thế. Và mỗi một lần khi mình làm cái gì ấ là mình phải nhắc mình phải nhắc mình
[22:09] phải nhắc. Nhưng dần dần khi mà em làm ra dài, em làm ra nhiều rồi á thì em xây
[22:13] được một cái workflow từ A cho tới Z. Tức là end to end luôn. là khi mà có một
[22:17] cái mod mới nó có thì nó đã có một cái cảnh báo rồi là à hôm nay đã có bên này
[22:24] ra mod mới nhá. Rồi hoặc là hôm nay bên này giảm giá nhá hoặc là bên này tăng
[22:29] giá nhá. Thì mình đã có một cái cái cái notification nó gửi tới cho mình ở trên
[22:34] một cái tín hiệu rồi. Và sau đấy á thì mình bảo rằng à hãy lên kệ mod này đi
[22:38] thì nó sẽ chạy từ đầu đến cuối cho em về cái workflow đó. Thì cái kinh nghiệm đây
[22:42] đó là em xây một cái workflow đầy đủ hết từ A tới Z và em đã cover được hết luôn
[22:47] tới những cái gì á mà nó gọi là phụ thuộc vào nhau. Thì khi mà nó làm mà nó
[22:52] sai á là bởi vì nó chưa chui vào cái nơi đó để nó đọc thì mình muốn nó làm đúng á
[22:57] mỗi lần mình làm mình phải nhắc nó. Thì bây giờ mình không muốn nhắc nó nữa thì
[23:01] mình phải xây ra được cái workflow. Còn đối với developer á thì anh em chắc hay
[23:06] sử dụng là C á, kiểu như là mình sẽ đưa ra cho nó những cái quy tắc thì nếu như
[23:11] mà nó đạt được đúng những cái quy tắc và những cái tiêu chí á thì nó mới được MF
[23:16] lên ở trên cái PR. Còn nếu không á thì nó bị đỏ thì nó là màu xanh và màu đỏ
[23:20] thì em nghĩ rằng cái đó nó sẽ là developer dùng hàng ngày. Còn đối với em
[23:24] thì em sử dụng workflow và dần dần á thì em sẽ kéo gần cái cái gáp này lại để cho
[23:29] bởi vì agent nó sẽ luôn luôn làm việc nó thân quen nhất là developer còn workflow
[23:33] nó hay bị quên nhưng mà em đang chuyển từ workflow em chuyển qua thành cái
[23:37] những cái quy tắc ở trên PR. Mình có cái vòng đời nào khi mà mình cái
[23:44] cái vai trò của con người mình can thiệp vào ngay cái thời điểm nó chạy không vậy
[23:48] sân như cái kinh nghiệm của sân á khoảng bao nhiêu lâu mình nên đối xót nó lại
[23:52] một lần để mình kiểm tra lại cái vòng đời á.
[23:55] \>> Khi nào em thấy vấn đề nó có vấn đề thì em em đối soát vấn đề lớn ấy. Vấn đề lớn
[24:00] thì em đối đôi khi có những cái vấn đề nó nhỏ đó em không không ke cho lắm. Em
[24:04] không có quá đi vào cái chi tiết khi đó là vấn đề nhỏ. Khi nào mà nó nó bắt đầu
[24:09] nó nảy sinh ra vấn đề lớn mà mình nhìn thấy được theo cái độ lớn của vấn đề lên
[24:12] rồi đó thì bắt đầu em em vào em giải quyết một lần.
[24:19] Đó kinh nghiệm của em thế thì kinh nghiệm của em mới chỉ khoảng 2
[24:23] năm trong lĩnh vực bill sản phẩm thôi chứ chưa phải là quá kỳ cựu đâu. Nhưng
[24:28] góc độ của em em tiếp cận là như vậy. Mong á là giúp anh có được thêm thông
[24:32] tin hữu ích. Ừ cũng cũng biết ăn sơ do mình cũng có
[24:36] muốn có nhiều cái góc nhìn á từ bởi vì cái chuyện mà vi code này là nó đi khác
[24:42] hoàn toàn so với cái flow mà truyền thống trước giờ tụi mình làm nên là tụi
[24:46] mình cũng mong muốn mà mình học hỏi để mình tìm hiểu thử và mình cũng có một
[24:50] cái đánh giá nào đó ngoại lề để mình cải thiện lại cái quy trình đó hơn trong cái
[24:55] xu thế mùa của cái mùa AI build cái dạng vai code như thế này. Và thật sự là
[25:01] trước giờ này mình tụi mình không có làm nhiều thì mình mới chỉ làm đảng 1 năm
[25:04] trở lại đây thôi. Và cũng cập vướng mắt rất là nhiều cái vấn đề khi mà trong
[25:09] suốt cái quá trình mình build và để mình so sánh giữa hai cái quy trình đó.
[25:13] \>> Ừ. Ok anh Thành. Câu hỏi của anh Thành rất là giá trị ạ.
[25:22] \>> Cảm ơn Sơ.
[25:23] \>> Ok anh Thành nhá. Ừm thế hôm nay mình kết thúc buổi hôm nay ở đây nhá.
[25:29] Ờ ok nhá cả nhà nhá. Ờ bài tập sẽ được gửi
[25:36] tới cho cả nhà ở trong Discord và ở trên build to own. Thì mọi người dành thời
[25:42] gian ra làm bài tập gửi trước vào hôm chủ nhật. Bài tập sẽ rất là nhiều đấy.
[25:46] Mọi người muốn giỏi được á thì mọi người phải làm bài tập thôi. Không có cách nào
[25:50] khác đâu. M phải thực hành, phải làm thực tế. Ờ chứ còn nghe và xem á không
[25:55] bao giờ ra được kết quả. Nên cái chương trình của Sơn á, Sơn không bao giờ muốn
[25:59] gọi là một khóa học. Đấy, bởi vì khóa học là chỉ nghe thôi, chỉ học thôi. Nên
[26:03] Sơn muốn rằng á là nó giống như một cái bootcam ấy, là một cái workshop là mọi
[26:07] người nghe, mọi người phải thực hành thực tế đi. Những cái event ở bên quốc
[26:11] tế này, speaker á họ nói ít lắm. Họ chỉ nói đâu đó khoảng 10 phút cho đến 15
[26:18] phút thôi. Xong sau đó là họ dừng chứ họ không bao giờ có những cái buổi chia sẻ
[26:23] nói khoảng hai tiếng ba tiếng như thế này đâu. Thì quan trọng nhất á là nghe
[26:27] xong mình phải action. Thì những cái chương trình mà Sơn á Sơn Sơn chuyển đổi
[26:32] cho Sơn ý là Sơn định hướng cho mọi người á là Sơn cũng nói ngắn thôi. Thực
[26:38] ra mọi người thấy rằng nãy giờ một tiếng đồng hồ Sơn chỉ là trả lời câu hỏi chứ
[26:42] không có phải rằng là chia sẻ nữa đúng không? để giải quyết được vấn đề cho mọi
[26:45] người nên mọi người hãy hãy làm thì mọi người mới có vấn đề và mọi người mang
[26:49] cái vấn đề tới để đặt câu hỏi. Và cái nội dung mà Sơn chia sẻ lần tới á thì
[26:53] Sơn chắc chỉ chia sẻ trong khoảng 1 tiếng đồng hồ thôi, 60 phút thôi. Xong
[26:58] sau đó là tới phần đặt câu hỏi. Mọi người phải đặt câu hỏi nhiều lên được
[27:01] chưa nhá. Rồi hẹn gặp lại mọi người trong hôm chủ nhật. M.

## Table 1
| Phần | Thời lượng | Ghi chú |
| --- | --- | --- |
| Transcript 01 | 22:23 | Bản người dùng cung cấp - đã hiệu đính |
| Transcript 02 | 19:21 | Bản gốc |
| Transcript 03 | 15:51 | Bản gốc |
| Transcript 04 | 10:24 | Bản gốc |
| Transcript 05 | 39:12 | Bản gốc |
| Transcript 06 | 27:06 | Bản gốc |

## Table 2
| Ghi chú hiệu đính: Đã sửa các lỗi nhận dạng giọng nói, chính tả và tên thuật ngữ/công cụ có thể xác định chắc chắn (ví dụ: AI Agent, ChatGPT, Linear, Vercel, Supabase, Cloudflare, HubSpot, Stripe, Claude). Một số câu được chỉnh nhẹ để dễ đọc nhưng vẫn giữ nguyên ý và mốc thời gian của bản chép lời gốc. |
| --- |