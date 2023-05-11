# BigData
**Tóm tắt**
  <br> <br>
  Khuyết tật hàn là các lỗi được tạo ra do sai lệch về hình dáng bên ngoài, độ nặng và cấu trúc kim loại so với thiết kế trong quá trình làm việc của thợ hàn với máy hàn. Khuyết tật hàn có thể ảnh hưởng đến chất lượng và thẩm mỹ của mối hàn. Trong quá trình sản xuất và thi công thép tiền chế cho các công trình, nếu các khuyết tật mối hàn không được phát hiện sẽ gây ảnh hưởng lớn đến chất lượng và an toàn cho công trình, cũng như đe dọa tính mạng con người. Trong lĩnh vực gia công, có 2 cách kiểm tra khuyết tật mối hàn là kiểm tra phá hủy và kiểm tra không phá hủy. Kiểm tra phá hủy thường thực hiện trong các phòng thí nghiệm, trong khi kiểm tra không phá hủy thường được ưu tiên thực hiện trong quá trình sản xuất.
<br> <br>
  (K. Schabowicz, 2019) Có nhiều phương pháp kiểm tra không phá hủy để kiểm tra khuyết tật trong mối hàn như kiểm tra bằng sóng siêu âm (UT), kiểm tra bằng tia X (RT), kiểm tra bằng tia gamma (GT), kiểm tra bằng dòng điện xoay chiều (ET), và kiểm tra bằng phương pháp quang (VT). Hiện nay, với sự phát triển của thị giác máy tính trong các lĩnh vực y tế, an ninh, sản xuất kinh doanh, việc phân loại khuyết tật mối hàn dựa trên hình ảnh cũng có thể thực hiện bằng thị giác máy tính.
Dữ liệu hình ảnh về khuyết tật mối hàn rất đa dạng do quá trình sản xuất. Tuy nhiên, việc xây dựng mô hình phân loại khuyết tật mối hàn sử dụng các phương pháp học sâu cho bộ dữ liệu ngày càng lớn sẽ gặp rất nhiều thách thức. Một trong những thách thức lớn nhất đó là chất lượng hình ảnh khi thu thập từ camera hoặc điện thoại thông minh bị ảnh hưởng bởi góc chụp ảnh, độ sáng hoặc các mối hàn bị che khuất. Điều này dẫn đến việc có thể thiếu sót thông tin và làm giảm độ chính xác của mô hình phân loại. Bên cạnh đó, chi phí huấn luyện cho mô hình cũng là một thách thức khác. Một số phương pháp học sâu đòi hỏi một lượng lớn dữ liệu và thời gian để huấn luyện, và việc thu thập dữ liệu phù hợp cũng là một vấn đề. Do đó, việc xây dựng một mô hình phân loại khuyết tật mối hàn đáng tin cậy và chính xác có thể đòi hỏi sự cân nhắc kỹ lưỡng và công phu trong quá trình thu thập và xử lý dữ liệu.
<br> <br>
  *Để giải quyết những thách thức trên, Luận văn này trình bày phương pháp phân loại hình ảnh mối hàn dựa trên công nghệ xử lý dữ liệu lớn. Phương pháp này sử dụng các mô hình dữ liệu đào tạo trước để học chuyển giao (LT) và đào tạo dữ liệu bằng phương pháp huấn luyện song song phân tán dữ liệu. Nền tảng tập trung dữ liệu Apache Spark kết hợp thư viện BigDL giúp cho việc huấn luyện phát hiện khuyết tật mối hàn trở nên nhanh chóng và chính xác hơn.*
