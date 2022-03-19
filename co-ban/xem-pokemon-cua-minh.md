# Xem Pokémon của mình

Giờ bạn đã bắt đầu bắt thật nhiều Pokémon rồi, có lẽ bạn muốn xem thông số, chỉ số những Pokémon mà mình đã bắt rồi nhỉ!

Việc này có thể làm được qua 2 cách. Cách 1 sẽ cho bạn xem thông tin đầy đủ của một con, cách 2 sẽ cho bạn xem toàn bộ Pokémon của bạn ở rất nhiều trang, mỗi trang có 20 con.

**p!info** (p!i):

Câu lệnh này hiển thị thông tin về con Pokémon bạn đã chọn hiện tại trong một tin nhắn dạng nhúng. Mọi thông tin xuất hiện trên đó bao gồm một bức ảnh, cấp độ, tên, biệt danh, XP hiện tại, môi trường (mint), chỉ số và IV, ngoài ra cũng có ảnh đại diện của bạn và id của Pokémon đó. Nó cũng sẽ có hai nút mũi tên bên dưới để di chuyển giữa các con Pokémon. Câu lệnh p!next (p!n) và p!back (p!b) cũng hoạt động tương tự như thế.

Giờ bạn đang muốn xem thông tin của những con khác thay vì chứ phải chọn con khác thành con hiện tại để xem, giờ có một cách khác. Câu lệnh **p!info latest** (p!i l) sẽ hiện thông tin của con mới có gần đây nhất, **p!info \<id>** (p!i \<id>) để xem thông tin Pokémon theo id. Để tìm id của một con Pokémon thì chúng ta phải thực hiện một câu lệnh khác.

**p!pokemon** (p!p)

Đây là câu lệnh mà ai mới chơi cũng cần nên biết. Câu lệnh sẽ liệt kê tất cả Pokémon bạn đang có hiện tại. Những thông tin nó cung cấp từ trái sang phải gồm id, một bức ảnh nhỏ, tên, biệt danh, hình trái tim kế bên (nếu được đặt là yêu thích), cấp độ và tổng IV. Như p!info, ở đây cũng có hai nút mũi tên để điều hướng sang các trang khác nhau, ấn mũi tên trái ở trang đầu sẽ đưa bạn đến trang cuối cùng. Bạn cũng có thể dùng **p!go \<trang>** để đến với trang nhất định. Ví dụ, nhập p!go 5 sẽ đưa bạn đến trang 5 của danh sách đó.

**p!order** (p!or)

Nếu chạy câu lệnh không kèm theo gì thì nó sẽ cho bạn các tùy chọn bao gồm sắp xếp theo số thứ tự/id (từ thấp đến cao), IV (từ cao đến thấp), cấp độ (từ cao đến thấp), và từ dex (từ thấp đến cao). Để sắp xếp lại danh sách (id không thay đổi), dùng p!order \<tùy chọn>. --order không hoạt động với p!pokemon.&#x20;

Một cách tìm kiếm nhanh với câu lệnh p!pokemon khác là qua bộ lọc. Xem danh sách các Bộ lọc Tìm kiếm để biết thêm chi tiết. Câu lệnh **p!favorite** (p!fav) \<id> dùng để thêm một Pokémon vào danh sách Pokémon yêu thích, thêm trái tim bên cạnh tên, **p!favoriteall** (p!favall) \<bộ lọc> dùng để yêu thích tất cả Pokémon \<theo một cái bộ lọc cho sẵn>. Xem các Pokémon yêu thích bằng câu lệnh p!pokemon --favorite.

**p!nickname** (p!nick)

Câu lệnh p!nickname \<id> \<tên> và p!nicknameall \<bộ lọc> đều hoạt động, dùng để đặt biệt danh cho một/nhiều Pokémon. Để bỏ biệt danh, nhập p!nickname reset (p!nicknameall cũng hoạt động). Để xem danh sách Pokémon có biệt danh "a" thì nhập: p!p --ni a.
