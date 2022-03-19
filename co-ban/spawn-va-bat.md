# Spawn và Bắt

### Hệ thống spawn pokémon

Cách tốt nhất để làm cho Pokémon spawn ra là làm cho máy chủ hoạt động; tức là có người chat trên máy chủ của bạn, càng nhiều người chat thì khả năng spawn ra pokémon càng cao và nhanh nữa!

### Bắt pokémon

Đầu tiên, bạn phải đoán được tên của Pokémon đó là gì. Nếu bạn đã biết tên của nó thì nhập: \<prefix>catch (c) \<tên pokémon> (mỗi máy chủ sẽ có prefix khác nhau). Nếu bạn không biết prefix của bot thì bạn cũng có thể ping bot thay cho prefix. Ví dụ, nếu prefix ở máy chủ bạn là "p!":

![](<../.gitbook/assets/image (1).png>)

Bạn cũng có thể nhận được huy hiệu (xem qua câu lệnh "\<prefix>profile") chỉ bằng cách bắt pokémon! Kiểm tra ở phần Nhiệm vụ để biết thêm chi tiết!

### Đoán tên Pokémon

Nếu như bạn không nhớ tên của Pokémon, hoặc đơn giản là không nhớ cách nó được gọi như thế nào thì bạn có thể sử dụng gợi ý để đoán ra tên Pokémon.

Để xuất hiện gợi ý cho Pokémon hiện tại, nhập lệnh \<prefix>hint (h). Nó sẽ xuất hiện vài kí tự như hình bên dưới, từ những kí tự đó mà đoán ra tên Pokémon thôi!

Ví dụ, tên Pokémon trong hình dưới đây là "Swinub"

![](../.gitbook/assets/image.png)

### Shiny Hunts (Săn tìm Shiny)

Đầu tiên, bạn cần nên biết rằng là shiny không thể spawn tự nhiên ra. Khi mà bạn bắt một con Pokémon nào đó thì sẽ có một tỉ lệ rất là nhỏ để nó thành shiny; shiny hunt là một cách để tăng tỉ lệ đó lên, và số lượng (chain) sẽ nhiều hơn.

Câu lệnh để shiny hunt một con nào đó là: \<prefix>shinyhunt (sh) \<tên pokémon>.

**Lưu ý:** Bạn không thể shiny hunt các dạng khác của Pokémon (galarian, alolan,...) hay Event Pokémon. Nhưng bạn có thể shiny hunt dạng thường và có thể bắt dạng nào mà bạn thích.

#### "Tôi có thể bắt được con shiny, mặc dù nó không phải con tôi săn hay không?"

Vâng, bạn có thể! Bạn sẽ bắt được shiny nếu thông báo bạn bắt thành công cùng với dòng chữ **These colors seem unusual...** như hình dưới đây.

![](<../.gitbook/assets/image (3).png>)

#### "Tôi đã bắt nhiều Pokémon hơn bạn của tôi, nhưng bạn tôi đã bắt được 3 con shiny rồi và tôi vẫn chưa có con nào. Liệu có một cái giới hạn nào đó cho việc bắt được Pokémon Shiny hay không?"

Không, không hề có giới hạn nào cả, nó phụ thuộc hoàn toàn vào sự may mắn của bạn. Shiny hunt cũng thế.

### Tên Pokémon ở ngôn ngữ khác

Pokémon cũng có tên ở các ngôn ngữ khác, nghĩa là bạn có thể catch Pokémon với những cái tên đó, nhưng chỉ những cái tên ở trong dex có mới được tính.

Đây là một ví dụ về những cái tên ở ngôn ngữ khác của Charmander mà có thể xem qua bằng cách dùng lệnh \<prefix>dex Charmander.

![](<../.gitbook/assets/image (2).png>)

Như vậy bạn có thể nhập **p!catch ヒトカゲ/Hitokage/Charmander/Glumanda/Salamèche** để bắt con Charmander đó.

### Incense

**"Tôi muốn bắt Pokémon ở máy chủ của tôi, nhưng máy chủ không có ai hoạt động cả, hoặc tôi chỉ muốn bắt chúng một mình ở máy chủ riêng. Vậy có cách nào để cho Pokémon spawn liên tục mà không cần phải hoạt động trong đó không?"**

Incense là một thứ như thế dành cho bạn, và tất nhiên, để mua incense bạn phải có 50 shard, tức 10 nghìn Pokécoins. Bạn có thể mua shard bằng lệnh \<prefix>buy shard(s) 50 (Gía là 200 Pokécoins mỗi một shard).

Chúng sẽ bắt đầu spawn tổng cộng 180 con, mỗi con cách nhau 20 giây, tức là kéo dài khoảng 1 tiếng. Để mua incense nhập lệnh \<prefix>buy incense.

Bạn có thể mua nhiều incense cùng một lúc, nhưng phải ở những kênh khác nhau.**Bạn không thể gộp incense.**

Để mua được incense thì bạn cần có quyền Người Quản Trị hoặc là chủ của một máy chủ thì mới mua được. Để dừng một cái incense nào đó, bạn cần có quyền Đề Cập (mention) và chạy câu lệnh \<prefix>stopincense. Một khi đã dừng là không thể bật trở lại và bạn phải mua cái khác.

### Bùa tăng tỉ lệ ra Shiny

Khi bạn nhập câu lệnh \<prefix>shop 7, bạn sẽ thấy một thứ ở trong shop có tên gọi là "Shiny Charm" (bùa tăng tỉ lệ ra Shiny).Gía của nó là 150 shard, tức 30 nghìn Pokécoins. Nó sẽ tăng tỉ lệ ra Shiny của bạn trong vòng 1 tuần và không thể dùng nhiều cái trong một lúc.

Nếu bạn không có tiền để mua những thứ trên thì hãy chuyển sang phần Nhiệm vụ để biết thêm chi tiết.

### Thiết lập kênh spawn Pokémon

Với \<prefix>redirect \<kênh>, bạn có thể thiết lập những kênh mà bạn muốn nó spawn (tất nhiên là máy chủ cần hoạt động để spawn). Nếu bạn đặt nhiều kênh thì nó sẽ spawn một cách ngẫu nhiên trong phạm vi các kênh đó.

Với câu lệnh \<prefix>redirect reset, bạn có thể khôi phục lại thiết lập spawn.

**Lưu ý:** Bạn bắt buộc phải có quyền quản trị hoặc là chủ máy chủ mới dùng được lệnh redirect.

Để xem các kênh spawn và những thứ khác, nhập lệnh \<prefix>config (configuration).

### Tắt ping khi bắt được Pokémon

Bạn có thể dùng câu lệnh \<prefix>togglemention để bật/tắt tùy chọn ping mỗi khi bắt được Pokémon

**Lưu ý: Tự động spam** là bạn đang vi phạm luật của Discord ToS. **Tự động bắt** là bạn đang vi phạm luật của Pokétwo ToS và sẽ khiến tài khoản của bạn không thể chơi được Pokétwo nữa. Do nên bạn hãy cẩn thận với những gì bạn đang làm!
