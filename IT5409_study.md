# IT5409 - Ngân hàng câu hỏi Thị giác máy tính

- Tổng số câu: 1.000
- Nguồn: [PDF gốc](<IT 5409 - Bài Kiểm Tra Thị Giác Máy Tính - Tất Cả Nội Dung.pdf>)
- Nội dung được chuyển đổi và làm sạch từ PDF; đáp án được giữ nguyên theo nguồn.

## Mục lục

1. [CHƯƠNG 1-2: Giới thiệu & Thu nhận ảnh](#chương-1-2-giới-thiệu--thu-nhận-ảnh)
2. [CHƯƠNG 3.1: Tăng cường chất lượng ảnh - Lọc ảnh](#chương-31-tăng-cường-chất-lượng-ảnh---lọc-ảnh)
3. [CHƯƠNG 3.2: Biến đổi ảnh - Miền tần số](#chương-32-biến-đổi-ảnh---miền-tần-số)
4. [CHƯƠNG 4.1: Phát hiện biên](#chương-41-phát-hiện-biên)
5. [CHƯƠNG 4.2: Trích chọn đặc trưng và so khớp ảnh](#chương-42-trích-chọn-đặc-trưng-và-so-khớp-ảnh)
6. [CHƯƠNG 5: Phân vùng ảnh (Segmentation)](#chương-5-phân-vùng-ảnh-segmentation)
7. [CHƯƠNG 6: Chuyển động và Theo dõi](#chương-6-chuyển-động-và-theo-dõi)
8. [CHƯƠNG 7: Deep Learning cho Computer Vision](#chương-7-deep-learning-cho-computer-vision)
9. [CÂU HỎI TỔNG HỢP - LIÊN CHƯƠNG](#câu-hỏi-tổng-hợp---liên-chương)

## CHƯƠNG 1-2: Giới thiệu & Thu nhận ảnh

### Câu 1
Nguồn PDF: trang 2

Thị giác máy tính (Computer Vision) được định nghĩa là gì?

- A. Lĩnh vực nghiên cứu về cách con người nhìn thấy hình ảnh
- B. Lĩnh vực khoa học liên ngành cho phép máy tính hiểu nội dung ảnh/video ở mức cao
- C. Lĩnh vực chỉ xử lý tín hiệu số
- D. Lĩnh vực thiết kế camera và thiết bị quang học

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Lĩnh vực khoa học liên ngành cho phép máy tính hiểu nội dung ảnh/video ở mức cao

**Giải thích:** Thị giác máy tính là lĩnh vực khoa học liên ngành (kết hợp toán học, học máy, xử lý tín hiệu...) nhằm mục đích trở thành cầu nối giữa giá trị điểm ảnh và "ngữ nghĩa" của bức ảnh[cite: 1]. Các đáp án khác chỉ bao hàm một phần nhỏ kỹ thuật hoặc thuộc về thị giác con người thay vì định nghĩa toàn diện về lĩnh vực này[cite: 1].

</details>

### Câu 2
Nguồn PDF: trang 2

Mức xử lý nào trong Computer Vision có đầu vào là ảnh và đầu ra là ảnh?

- A. High-level vision
- B. Middle-level vision
- C. Low-level vision
- D. Semantic vision

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** C. Low-level vision

**Giải thích:** Low-level vision (mức thấp) tập trung vào việc tạo ảnh, thu nhận và các phép xử lý tiền kỳ trên dữ liệu 2D như lọc nhiễu hay tăng cường tương phản[cite: 1]. Do đó, quá trình này nhận đầu vào là một bức ảnh và trả ra kết quả cũng là một bức ảnh đã qua xử lý[cite: 1].

</details>

### Câu 3
Nguồn PDF: trang 2

Middle-level Vision bao gồm các nhiệm vụ nào? (Chọn tất cả đáp án đúng)

- A. Trích chọn đặc trưng (cạnh, góc, kết cấu)
- B. Phân vùng ảnh
- C. So khớp ảnh
- D. Nhận dạng đối tượng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Trích chọn đặc trưng (cạnh, góc, kết cấu); B. Phân vùng ảnh; C. So khớp ảnh

**Giải thích:** Xử lý mức giữa (Middle-level Vision) đóng vai trò trung gian, thực hiện các nhiệm vụ như trích chọn đặc trưng (cạnh, góc, đường), phân vùng và so khớp ảnh[cite: 1]. Nhận dạng đối tượng (đáp án D) đòi hỏi sự thấu hiểu ngữ nghĩa nên thuộc về mức cao (High-level vision)[cite: 1].

</details>

### Câu 4
Nguồn PDF: trang 2

Tế bào thụ cảm quang nào trong mắt người hoạt động tốt trong điều kiện ánh sáng yếu?

- A. Cones (tế bào hình nón)
- B. Rods (tế bào hình que)
- C. Cả hai loại như nhau
- D. Iris (mống mắt)

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Rods (tế bào hình que)

**Giải thích:** Trong võng mạc, tế bào hình que (Rods) có độ nhạy cảm với ánh sáng rất cao, giúp mắt có khả năng hoạt động tốt trong môi trường ánh sáng yếu[cite: 1]. Tuy nhiên, loại tế bào này lại có nhược điểm là rất ít nhạy cảm với màu sắc so với tế bào hình nón (Cones)[cite: 1].

</details>

### Câu 5
Nguồn PDF: trang 2

Tế bào Cone loại L nhạy cảm nhất với bước sóng ánh sáng khoảng bao nhiêu?

- A. 440 nm
- B. 530 nm
- C. 560 nm
- D. 700 nm

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** C. 560 nm

**Giải thích:** Tế bào hình nón (Cones) được chia làm ba loại chịu trách nhiệm cảm thụ các dải bước sóng khác nhau[cite: 1]. Loại L nhạy cảm nhất với ánh sáng có bước sóng cao, đạt đỉnh hấp thụ ở mức xấp xỉ 560 nm[cite: 1].

</details>

### Câu 6
Nguồn PDF: trang 2

Trong mô hình pin-hole camera, yếu tố nào quyết định độ mờ (blur) của ảnh?

- A. Tiêu cự của thấu kính
- B. Độ mở của lỗ thủng (aperture size)
- C. Khoảng cách từ object đến camera
- D. Tốc độ chụp ảnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Độ mở của lỗ thủng (aperture size)

**Giải thích:** Đối với mô hình pin-hole camera (máy ảnh không có thấu kính), độ mở của lỗ thủng chính là yếu tố quyết định độ mờ (blur) của bức ảnh thu được[cite: 1]. Kích thước aperture càng lớn thì hiện tượng nhòe hình càng tăng do các tia sáng từ một điểm trên vật thể chiếu lên nhiều điểm trên màng phim[cite: 1].

</details>

### Câu 7
Nguồn PDF: trang 2

DOF (Depth of Field) và aperture size có mối quan hệ gì?

- A. Tỉ lệ thuận
- B. Tỉ lệ nghịch
- C. Không liên quan
- D. Phụ thuộc vào tiêu cự

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Tỉ lệ nghịch

**Giải thích:** Độ sâu vùng quan sát (Depth of Field - DOF) có mối quan hệ tỉ lệ nghịch với kích thước độ mở ống kính (aperture size)[cite: 1]. Nghĩa là, khi kích thước aperture tăng lên (mở khẩu lớn), vùng đối tượng được lấy nét (in focus) sẽ thu hẹp lại, làm giảm DOF[cite: 1].

</details>

### Câu 8
Nguồn PDF: trang 3

Quá trình số hóa (digitization) ảnh bao gồm hai bước chính là gì?

- A. Nén ảnh và lưu trữ
- B. Lấy mẫu (Sampling) và Lượng tử hóa (Quantization)
- C. Lọc nhiễu và tăng tương phản
- D. Thu nhận và truyền tải

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Lấy mẫu (Sampling) và Lượng tử hóa (Quantization)

**Giải thích:** Để chuyển đổi cảnh thật thành một bức ảnh số (digitization), hệ thống phải thực hiện hai bước toán học cốt lõi thông qua bộ ADC: Lấy mẫu (sampling) để tạo thành mảng các điểm ảnh rời rạc trên không gian 2D, và Lượng tử hóa (quantization) để làm tròn giá trị tín hiệu của từng điểm về các mức số nguyên[cite: 1].

</details>

### Câu 9
Nguồn PDF: trang 3

Cảm biến hình ảnh CCD và CMOS hoạt động theo nguyên lý nào?

- A. Chuyển đổi nhiệt thành điện
- B. Chuyển đổi photon thành electron
- C. Chuyển đổi âm thanh thành tín hiệu
- D. Chuyển đổi từ trường thành điện

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Chuyển đổi photon thành electron

**Giải thích:** Các cảm biến hình ảnh phổ biến như CCD hay CMOS được cấu tạo từ một mảng các diode nhạy sáng (photodiodes)[cite: 1]. Nguyên lý hoạt động cơ bản của chúng là bắt giữ hạt ánh sáng (photon) và chuyển đổi năng lượng đó thành tín hiệu điện (electron) để tạo ra dữ liệu ảnh[cite: 1].

</details>

### Câu 10
Nguồn PDF: trang 3

Ảnh grayscale (đa mức xám) có giá trị pixel nằm trong khoảng nào?

- A. [0, 1]
- B. [0, 127]
- C. [0, 255]
- D. [-128, 127]

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** C. [0, 255]

**Giải thích:** Ảnh đa mức xám (grayscale) tiêu chuẩn phân bổ 8 bits (tương đương 1 byte) để lưu trữ thông tin cường độ sáng cho mỗi pixel[cite: 1]. Do đó, giá trị điểm ảnh là các số nguyên dương trải dài từ mức 0 (màu đen tuyệt đối) đến mức 255 (màu trắng tuyệt đối)[cite: 1].

</details>

### Câu 11
Nguồn PDF: trang 3

Một pixel trong ảnh màu RGB chiếm bao nhiêu bytes?

- A. 1 byte
- B. 2 bytes
- C. 3 bytes
- D. 4 bytes

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** C. 3 bytes

**Giải thích:** Bức ảnh màu định dạng RGB cần lưu trữ thông tin cho ba kênh màu riêng biệt gồm Red, Green và Blue[cite: 1]. Do mỗi kênh màu sử dụng 8 bits (1 byte) để biểu diễn mức cường độ, tổng cộng mỗi pixel trong ảnh RGB tiêu chuẩn sẽ chiếm 24 bits, tương đương với 3 bytes[cite: 1].

</details>

### Câu 12
Nguồn PDF: trang 3

Ảnh nhị phân (binary image) lưu trữ bao nhiêu bit cho mỗi pixel?

- A. 8 bits
- B. 4 bits
- C. 2 bits
- D. 1 bit

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** D. 1 bit

**Giải thích:** Ảnh nhị phân là dạng biểu diễn hình ảnh đơn giản nhất, trong đó mỗi pixel chỉ mang một trong hai trạng thái giá trị (thường là 0 tương ứng với đen và 1 tương ứng với trắng)[cite: 1]. Bởi vì chỉ có hai trạng thái, hệ thống chỉ cần sử dụng 1 bit dữ liệu cho mỗi pixel[cite: 1].

</details>

### Câu 13
Nguồn PDF: trang 3

Không gian màu RGB là hệ thống phối màu nào?

- A. Phối màu trừ
- B. Phối màu cộng
- C. Phối màu tuyến tính với mắt người
- D. Phối màu độc lập thiết bị

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Phối màu cộng

**Giải thích:** Hệ RGB (Red-Green-Blue) là hệ thống phối màu cộng (additive color model)[cite: 1]. Nó hoạt động bằng cách phát ra và chồng (cộng) các kênh màu ánh sáng cơ bản lại với nhau để tạo ra mọi màu sắc khác, là nguyên lý nền tảng của các thiết bị hiển thị như màn hình máy tính[cite: 1].

</details>

### Câu 14
Nguồn PDF: trang 3

Không gian màu nào thường được dùng trong in ấn?

- A. RGB
- B. HSV
- C. CMY
- D. Lab

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** C. CMY

**Giải thích:** Hệ màu CMY (Cyan-Magenta-Yellow) là hệ thống phối màu trừ, hoạt động dựa trên nguyên lý hấp thụ ánh sáng của mực in trên giấy trắng[cite: 1]. Do đó, CMY là không gian màu chuyên dụng và phổ biến nhất trong các ngành công nghiệp in ấn và photocopy[cite: 1].

</details>

### Câu 15
Nguồn PDF: trang 3

Trong không gian màu HSV, thành phần H (Hue) có giá trị trong khoảng nào?

- A. 0 đến 1
- B. 0 đến 255
- C. 0 đến 360
- D. -127 đến 127

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** C. 0 đến 360

**Giải thích:** Trong mô hình không gian màu HSV, thành phần H (Hue) đại diện cho sắc tố hay tông màu cốt lõi[cite: 1]. Nó được biểu diễn về mặt toán học trên một vòng tròn màu (colour cone) dưới dạng góc, vì vậy giá trị của H có đơn vị là độ và nằm trong khoảng từ 0 đến 360 độ[cite: 1].

</details>

### Câu 16
Nguồn PDF: trang 4

Không gian màu Lab có ưu điểm gì so với RGB? (Chọn tất cả đúng)

- A. Độc lập với thiết bị
- B. Tuyến tính với cảm nhận màu của mắt người
- C. Phân tách rõ thông tin độ sáng (L) và màu sắc (a, b)
- D. Dễ hiển thị trên màn hình hơn

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Độc lập với thiết bị; B. Tuyến tính với cảm nhận màu của mắt người; C. Phân tách rõ thông tin độ sáng (L) và màu sắc (a, b)

**Giải thích:** Không gian màu Lab (CIE L*a*b*) được nghiên cứu để mô phỏng cách thức nhận thức màu sắc của con người[cite: 1]. Nó sở hữu ưu điểm vượt trội so với RGB ở việc tuyến tính với cảm nhận của mắt, độc lập hoàn toàn với thiết bị phần cứng, và có khả năng phân tách riêng biệt thông tin độ sáng (L) khỏi các kênh màu sắc (a, b)[cite: 1].

</details>

### Câu 17
Nguồn PDF: trang 4

Công thức tính Luminance Y trong không gian YUV là gì?

- A. Y = 0.299R + 0.587G + 0.114B
- B. Y = (R + G + B) / 3
- C. Y = 0.5R + 0.3G + 0.2B
- D. Y = 0.114R + 0.587G + 0.299B

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Y = 0.299R + 0.587G + 0.114B

**Giải thích:** Trong hệ không gian màu YUV, thành phần Y biểu diễn độ sáng (Luminance) của bức ảnh[cite: 1]. Công thức chuẩn chuyển đổi từ RGB sang Y được thiết kế dựa trên độ nhạy khác nhau của mắt người với từng dải màu, cụ thể là: Y = 0.299R + 0.587G + 0.114B (mắt nhạy cảm nhất với ánh sáng xanh lá)[cite: 1].

</details>

### Câu 18
Nguồn PDF: trang 4

Histogram ảnh biểu diễn thông tin gì?

- A. Phân bố không gian của các pixel
- B. Phân bố mức xám/màu sắc của các pixel
- C. Thông tin về độ sâu ảnh
- D. Thông tin về chuyển động trong ảnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Phân bố mức xám/màu sắc của các pixel

**Giải thích:** Lược đồ Histogram của một bức ảnh là một hàm thống kê rời rạc[cite: 1]. Mục đích của nó là biểu diễn tần suất xuất hiện (phân bố) của từng mức xám hoặc từng giá trị màu sắc của các điểm ảnh có mặt trên bức ảnh đó, không chứa thông tin về vị trí không gian[cite: 1].

</details>

### Câu 19
Nguồn PDF: trang 4

Tại sao mắt người cần nhiều loại tế bào cảm quang khác nhau?

- A. Để thấy được ảnh 3D
- B. Để phân biệt màu sắc và hoạt động trong điều kiện ánh sáng khác nhau
- C. Để tăng tốc độ xử lý hình ảnh
- D. Để giảm nhiễu trong môi trường tối

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Để phân biệt màu sắc và hoạt động trong điều kiện ánh sáng khác nhau

**Giải thích:** Võng mạc mắt người chứa hai loại tế bào thụ cảm ánh sáng có chức năng bù trừ cho nhau[cite: 1]. Tế bào hình nón (Cones) giúp phân biệt màu sắc và hoạt động mạnh dưới ánh sáng tốt, trong khi tế bào hình que (Rods) có độ nhạy cao để duy trì thị lực khi môi trường thiếu sáng[cite: 1].

</details>

### Câu 20
Nguồn PDF: trang 4

Ứng dụng nào sau đây thuộc lĩnh vực Computer Vision trong y tế? (Chọn tất cả đúng)

- A. Phân đoạn ảnh MRI
- B. Phẫu thuật robot có hướng dẫn thị giác
- C. Nhận diện khuôn mặt bảo mật
- D. Phân loại và phát hiện ung thư

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Phân đoạn ảnh MRI; B. Phẫu thuật robot có hướng dẫn thị giác; D. Phân loại và phát hiện ung thư

**Giải thích:** Trong miền ứng dụng y tế (Medicine Application), thị giác máy tính hỗ trợ các quy trình chẩn đoán và điều trị như: phân loại và phát hiện bệnh lý, phân đoạn ảnh 2D/3D (như MRI), tái tạo nội tạng người, và điều khiển robot phẫu thuật (vision-guided robotics surgery)[cite: 1]. Nhận diện khuôn mặt thuộc lĩnh vực an ninh/bảo mật[cite: 1].

</details>

### Câu 21
Nguồn PDF: trang 4

Thành phần nào trong camera số thực hiện chuyển đổi tín hiệu analog sang digital?

- A. Lens
- B. CCD sensor
- C. ADC (Analog-to-Digital Converter)
- D. DSP (Digital Signal Processor)

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** C. ADC (Analog-to-Digital Converter)

**Giải thích:** Tín hiệu 2D thu được từ cảm biến quang học (như CCD/CMOS) là tín hiệu liên tục (analog) chứa thông tin dạng điện tích[cite: 1]. Để biến đổi nó thành ma trận số lượng tử hóa mà máy tính hiểu được, camera số sử dụng một thành phần chuyên dụng là bộ chuyển đổi ADC (Analog-to-Digital Converter)[cite: 1].

</details>

### Câu 22
Nguồn PDF: trang 4

Ảnh số I có kích thước N×M, chỉ số (0,0) nằm ở vị trí nào?

- A. Góc dưới trái
- B. Góc dưới phải
- C. Góc trên trái
- D. Tâm ảnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** C. Góc trên trái

**Giải thích:** Trong thị giác máy tính và xử lý ảnh, một bức ảnh số I kích thước N×M được lưu trữ dưới dạng ma trận 2D[cite: 1]. Hệ tọa độ quy ước của ma trận này luôn đặt gốc chỉ số (0,0) nằm ở vị trí góc trên cùng bên trái của hình ảnh, trong đó trục x hướng sang phải và trục y hướng xuống dưới[cite: 1].

</details>

### Câu 23
Nguồn PDF: trang 4

Tại sao cần nhiều không gian màu khác nhau? (Chọn đúng nhất)

- A. Vì mỗi không gian màu phù hợp với ứng dụng riêng
- B. Vì RGB không thể biểu diễn đủ màu
- C. Vì camera chỉ hỗ trợ một loại không gian màu
- D. Vì máy tính không thể xử lý RGB

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Vì mỗi không gian màu phù hợp với ứng dụng riêng

**Giải thích:** Không có một không gian màu nào là hoàn hảo cho mọi trường hợp. Sự tồn tại của nhiều không gian màu bắt nguồn từ đặc thù của từng lĩnh vực ứng dụng[cite: 1]. Chẳng hạn: RGB dùng để hiển thị màn hình, CMY phục vụ ngành in ấn, còn Lab hay HSV hữu ích cho các thuật toán phân tích thị giác vì chúng tách biệt độ sáng và mô phỏng tốt cảm nhận của mắt người[cite: 1].

</details>

### Câu 24
Nguồn PDF: trang 5

Trong điều kiện chiếu sáng thay đổi, không gian màu nào compact nhất trên kênh màu (chrominance)?

- A. RGB
- B. HSV (kênh H)
- C. Lab (kênh ab)
- D. YCrCb

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** C. Lab (kênh ab)

**Giải thích:** Các nghiên cứu cho thấy khi hình ảnh chịu sự thay đổi của điều kiện chiếu sáng, kênh màu của RGB bị biến thiên rất mạnh[cite: 1]. Trong khi đó, các kênh màu độc lập độ sáng như H (HSV), CrCb (YCrCb) và ab (Lab) đều duy trì được tính tập trung (compact), trong đó mức độ tập trung trên không gian màu Lab được đánh giá là ổn định và tốt nhất[cite: 1].

</details>

### Câu 25
Nguồn PDF: trang 5

Khi aperture size tăng lên, điều gì xảy ra với DOF?

- A. DOF tăng
- B. DOF giảm
- C. DOF không đổi
- D. DOF phụ thuộc vào tiêu cự

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. DOF giảm

**Giải thích:** Độ mở ống kính (aperture size) đóng vai trò quyết định đến độ sâu vùng quan sát (Depth of Field - DOF)[cite: 1]. Theo nguyên lý quang học, kích thước aperture tỉ lệ nghịch với khoảng hội tụ; vì vậy khi aperture size tăng, DOF sẽ thu hẹp lại, khiến phông nền bị làm mờ nhiều hơn[cite: 1].

</details>

### Câu 26
Nguồn PDF: trang 5

High-level vision bao gồm các nhiệm vụ nào? (Chọn tất cả đúng)

- A. Nhận dạng và phân loại đối tượng
- B. Phân tích chuyển động
- C. Tái tạo cảnh 3D
- D. Lọc nhiễu ảnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Nhận dạng và phân loại đối tượng; B. Phân tích chuyển động; C. Tái tạo cảnh 3D

**Giải thích:** Các nhiệm vụ của thị giác máy tính ở mức cao (High-level Vision) tập trung vào việc tạo ra các thông tin ngữ nghĩa và ra quyết định[cite: 1]. Những chủ đề điển hình bao gồm: nhận dạng (phân loại), định danh đối tượng, phát hiện, phân tích chuyển động và tái tạo cảnh/dựng 3D[cite: 1]. Lọc nhiễu ảnh thuộc giai đoạn tiền xử lý mức thấp[cite: 1].

</details>

### Câu 27
Nguồn PDF: trang 5

Cones loại S nhạy cảm nhất với bước sóng khoảng bao nhiêu nm?

- A. 440 nm
- B. 530 nm
- C. 560 nm
- D. 620 nm

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. 440 nm

**Giải thích:** Võng mạc mắt người sở hữu 3 loại tế bào hình nón (Cones) khác nhau để cảm thụ màu sắc dựa trên chiều dài bước sóng[cite: 1]. Tế bào Cone loại S (Short) là loại nhạy cảm nhất với ánh sáng có bước sóng thấp, nằm trong dải màu xanh lam với đỉnh hấp thụ ở mức xấp xỉ 440 nm[cite: 1].

</details>

### Câu 28
Nguồn PDF: trang 5

Ảnh đa phổ (multispectral image) khác ảnh màu RGB ở điểm nào?

- A. Ít kênh màu hơn
- B. Có nhiều kênh hơn 3 và ngoài dải nhìn thấy
- C. Không có thông tin màu
- D. Chỉ là ảnh grayscale

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Có nhiều kênh hơn 3 và ngoài dải nhìn thấy

**Giải thích:** Trong khi ảnh màu truyền thống như RGB chỉ bao gồm 3 kênh cường độ mô phỏng dải ánh sáng nhìn thấy của con người, ảnh đa phổ (multispectral image) là loại dữ liệu mở rộng chứa nhiều kênh hơn[cite: 1]. Nó có khả năng ghi nhận cả các dải phổ điện từ nằm ngoài khả năng nhận biết của mắt thường như hồng ngoại hay tử ngoại[cite: 1].

</details>

### Câu 29
Nguồn PDF: trang 5

Trong không gian màu HSV, khi Saturation = 0, pixel đó có màu gì?

- A. Màu đỏ
- B. Màu trắng
- C. Màu xám (không màu)
- D. Màu đen

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** C. Màu xám (không màu)

**Giải thích:** Trong mô hình không gian màu HSV, S đại diện cho độ bão hòa màu (Saturation)[cite: 1]. Khi S tiến về 0, màu sắc bị triệt tiêu hoàn toàn, khiến thông số H (Hue) không còn mang ý nghĩa định dạng màu, và pixel đó sẽ trở thành một sắc thái xám (nằm trên trục xám vô hướng phụ thuộc vào V)[cite: 1].

</details>

### Câu 30
Nguồn PDF: trang 5

Phép lấy mẫu (sampling) trong số hóa ảnh thực hiện điều gì?

- A. Làm tròn giá trị pixel về số nguyên
- B. Thu thập các mẫu tại các vị trí rời rạc trên ảnh
- C. Nén ảnh để giảm dung lượng
- D. Tăng độ phân giải ảnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Thu thập các mẫu tại các vị trí rời rạc trên ảnh

**Giải thích:** Quá trình chuyển đổi cảnh thực liên tục thành ảnh số (Digitization) bắt đầu bằng bước lấy mẫu (Sampling)[cite: 1]. Phép toán này thực hiện việc thu thập các mẫu tín hiệu vật lý tại các điểm hoặc vị trí không gian rời rạc (thường là lưới đều 2D) để định hình tọa độ pixel cho bức ảnh[cite: 1].

</details>

### Câu 31
Nguồn PDF: trang 5

Ứng dụng nào sử dụng Computer Vision trong giao thông?

- A. Xe tự hành
- B. Giám sát lái xe
- C. Đọc biển số xe (ANPR)
- D. Tất cả các đáp án trên

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** D. Tất cả các đáp án trên

**Giải thích:** Trong miền ứng dụng giao thông (Transportation Application), thị giác máy tính được ứng dụng rộng rãi để giải quyết nhiều bài toán[cite: 1]. Các ví dụ tiêu biểu bao gồm hệ thống đọc biển số xe tự động (ANPR), công nghệ xe tự hành (Autonomous vehicle), và phần mềm an toàn giám sát sự tập trung của tài xế (driver vigilance monitoring)[cite: 1].

</details>

### Câu 32
Nguồn PDF: trang 6

Trong RGB, màu Yellow (vàng) được tạo ra bằng cách nào?

- A. R=255, G=0, B=255
- B. R=255, G=255, B=0
- C. R=0, G=255, B=255
- D. R=255, G=0, B=0

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. R=255, G=255, B=0

**Giải thích:** RGB là một hệ thống phối màu cộng (additive colors)[cite: 1]. Khi chồng ánh sáng Đỏ (Red ở cường độ cực đại R=255) và ánh sáng Xanh lá (Green ở cường độ cực đại G=255) trong điều kiện thiếu vắng kênh Xanh dương (B=0), ta sẽ thu được màu Vàng (Yellow)[cite: 1].

</details>

### Câu 33
Nguồn PDF: trang 6

Màu Cyan trong RGB có giá trị nào?

- A. (255, 0, 0)
- B. (255, 0, 255)
- C. (0, 255, 255)
- D. (0, 0, 255)

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** C. (0, 255, 255)

**Giải thích:** Thuộc tính của hệ phối màu cộng RGB cho phép sinh ra màu Cyan (Lục lam) thông qua việc kết hợp ánh sáng Xanh lá (Green) và Xanh dương (Blue)[cite: 1]. Do đó, giá trị bộ ba tương ứng để hiển thị màu Cyan ở cường độ chuẩn trên thiết bị là R=0, G=255, B=255[cite: 1].

</details>

### Câu 34
Nguồn PDF: trang 6

Lượng tử hóa (quantization) trong số hóa ảnh thực hiện điều gì?

- A. Thu thập mẫu tại các điểm rời rạc
- B. Làm tròn giá trị tín hiệu về số nguyên gần nhất
- C. Nén ảnh
- D. Tăng số pixel

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Làm tròn giá trị tín hiệu về số nguyên gần nhất

**Giải thích:** Sau khi tín hiệu liên tục được lấy mẫu (sampling) theo không gian, nó trải qua bước lượng tử hóa (quantization) mức xám[cite: 1]. Bước này áp đặt tín hiệu điện tích (vốn liên tục) cho từng điểm mẫu bằng cách làm tròn nó thành các mức giá trị số nguyên rời rạc gần nhất (ví dụ: từ 0 đến 255 đối với 8-bit)[cite: 1].

</details>

### Câu 35
Nguồn PDF: trang 6

Một camera CMOS khác CCD ở điểm chính nào?

- A. CMOS rẻ hơn và tiêu thụ ít điện hơn
- B. CMOS cho chất lượng ảnh tốt hơn trong mọi điều kiện
- C. CMOS không thể chụp màu
- D. CMOS chỉ hoạt động ban ngày

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. CMOS rẻ hơn và tiêu thụ ít điện hơn

**Giải thích:** Cả CCD và CMOS đều là các loại cảm biến hình ảnh dùng các diode nhạy sáng (photodiodes) để chuyển đổi photon thành electron[cite: 1]. Điểm khác biệt quan trọng định vị ứng dụng của CMOS là công nghệ này tiêu thụ ít năng lượng điện hơn và có chi phí sản xuất thấp hơn nhiều so với CCD[cite: 1].

</details>

### Câu 36
Nguồn PDF: trang 6

Thành phần b* trong không gian màu Lab biểu diễn trục màu nào?

- A. Trục xanh lá - đỏ
- B. Trục xanh dương - vàng
- C. Độ sáng
- D. Độ bão hòa

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Trục xanh dương - vàng

**Giải thích:** Không gian màu Lab gồm một kênh ánh sáng L và hai kênh phân phối màu sắc a* và b*[cite: 1]. Trong khi a* là trục biểu diễn sự biến thiên từ green (âm) đến red (dương), thì b* là trục biểu diễn màu chạy từ blue (xanh dương ở giá trị âm) chuyển dần sang yellow (vàng ở giá trị dương)[cite: 1].

</details>

### Câu 37
Nguồn PDF: trang 6

Khi độ phân giải không gian (spatial resolution) tăng, điều gì xảy ra?

- A. Số pixel tăng, ảnh chi tiết hơn
- B. Số pixel giảm, ảnh mờ hơn
- C. Không ảnh hưởng đến chất lượng
- D. Dung lượng file giảm

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Số pixel tăng, ảnh chi tiết hơn

**Giải thích:** Độ phân giải không gian trong quá trình lấy mẫu (sampling) quyết định mật độ các điểm dữ liệu được thu thập[cite: 1]. Khi độ phân giải này tăng lên, số lượng pixel phân bố trên hình ảnh sẽ tăng theo, giúp hình ảnh lưu giữ được nhiều cấu trúc nhỏ và trở nên chi tiết, sắc nét hơn[cite: 1].

</details>

### Câu 38
Nguồn PDF: trang 6

Ứng dụng OCR (Optical Character Recognition) thuộc lĩnh vực ứng dụng nào?

- A. Y tế
- B. Tự động hóa công nghiệp
- C. Bảo mật
- D. Robotics

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Tự động hóa công nghiệp

**Giải thích:** Optical Character Recognition (OCR - Nhận dạng ký tự quang học), hay khả năng đọc hiểu tài liệu (document understanding), được hệ thống hóa vào nhóm ứng dụng tự động hóa công nghiệp (Industrial Automation Application)[cite: 1]. Phân nhóm này cũng bao gồm các chức năng như đọc mã vạch, phân loại vật thể và phát hiện hàng hóa lỗi[cite: 1].

</details>

### Câu 39
Nguồn PDF: trang 6

Màu Magenta trong RGB có giá trị nào?

- A. (255, 255, 0)
- B. (0, 255, 255)
- C. (255, 0, 255)
- D. (128, 0, 128)

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** C. (255, 0, 255)

**Giải thích:** Màu Magenta (Hồng sẫm/Đỏ tươi) là một màu thứ cấp trong hệ thống không gian màu cộng RGB[cite: 1]. Nó được sinh ra nhờ sự kết hợp song song của ánh sáng kênh Đỏ (Red) và ánh sáng kênh Xanh dương (Blue) ở mức cường độ tối đa, tương ứng với bộ giá trị R=255, G=0, B=255[cite: 1].

</details>

### Câu 40
Nguồn PDF: trang 7

Điều nào sau đây là đúng về mắt người so với camera pin-hole?

- A. Mắt người không có cơ chế tương đương aperture
- B. Pupil (con ngươi) của mắt tương đương aperture của camera
- C. Mắt người không có cảm biến hình ảnh
- D. Mắt người hoạt động hoàn toàn khác camera

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Pupil (con ngươi) của mắt tương đương aperture của camera

**Giải thích:** Cấu trúc vật lý của mắt người hoạt động theo các nguyên lý quang học tương đồng với máy ảnh[cite: 1]. Trong đó, con ngươi (Pupil) đóng vai trò là một "hole" (lỗ hổng), có độ mở thu nhận ánh sáng tương đương hoàn toàn với thành phần aperture (độ mở) trên cấu trúc của camera[cite: 1].

</details>

### Câu 41
Nguồn PDF: trang 7

Structure from Motion (SfM) là kỹ thuật gì?

- A. Phát hiện chuyển động trong video
- B. Tái tạo cấu trúc 3D từ nhiều ảnh 2D
- C. Phân tích chuyển động của đối tượng
- D. Tạo animation từ ảnh tĩnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Tái tạo cấu trúc 3D từ nhiều ảnh 2D

**Giải thích:** Structure from Motion (SfM) là một bài toán quan trọng thuộc mức xử lý cao (High-level vision), sử dụng hình ảnh như một thiết bị đo lường không gian[cite: 1]. Kỹ thuật này phân tích sự biến thiên qua một chuỗi các bức ảnh 2D liên tiếp nhằm mục đích đo khoảng cách và tái tạo lại mô hình cảnh 3D (3D Model Building)[cite: 1].

</details>

### Câu 42
Nguồn PDF: trang 7

Histogram chuẩn hóa h(k) được tính bằng cách nào?

- A. Chia số pixel có mức xám k cho tổng số pixel
- B. Nhân số pixel có mức xám k với tổng số pixel
- C. Lấy logarithm của số pixel có mức xám k
- D. Lấy căn bậc hai của số pixel có mức xám k

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Chia số pixel có mức xám k cho tổng số pixel

**Giải thích:** Quá trình chuẩn hóa Lược đồ mức xám (Histogram) nhằm biến đổi đồ thị tần suất thành đồ thị phân bố xác suất[cite: 1]. Phép toán này được thực hiện bằng cách lấy số lượng điểm ảnh mang mức xám cụ thể $k$ (ký hiệu $n_k$) chia cho tổng số lượng toàn bộ điểm ảnh có trong bức ảnh ($n$)[cite: 1].

</details>

### Câu 43
Nguồn PDF: trang 7

Tại sao Computer Vision là lĩnh vực khoa học liên ngành?

- A. Vì nó chỉ cần kiến thức toán học
- B. Vì nó kết hợp thị giác người, toán học, thống kê, học máy và xử lý tín hiệu
- C. Vì nó chỉ áp dụng trong ngành y tế
- D. Vì nó chỉ dùng trong robotics

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Vì nó kết hợp thị giác người, toán học, thống kê, học máy và xử lý tín hiệu

**Giải thích:** Thị giác máy tính không tồn tại như một môn học độc lập đơn lẻ[cite: 1]. Nó là một lĩnh vực liên ngành rộng lớn, hình thành nhờ sự kết nối của nhiều khoa học như sinh học (thị giác con người, thần kinh học), toán học, vật lý (quang học), khoa học máy tính, xử lý tín hiệu, thống kê và học máy[cite: 1].

</details>

### Câu 44
Nguồn PDF: trang 7

Ảnh màu có kích thước 1920×1080 RGB chiếm bao nhiêu bytes (chưa nén)?

- A. 1,920 bytes
- B. 2,073,600 bytes
- C. 6,220,800 bytes
- D. 24,883,200 bytes

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** C. 6,220,800 bytes

**Giải thích:** Để tính dung lượng mảng pixel chưa nén của ảnh màu RGB, ta nhân tổng số lượng điểm ảnh với dung lượng của mỗi điểm[cite: 1]. Một ảnh 1920×1080 có 2,073,600 pixel, mỗi pixel sử dụng 3 bytes (đại diện cho 3 kênh R, G, B, mỗi kênh 8 bits), do đó dung lượng tổng là 1920 × 1080 × 3 = 6,220,800 bytes[cite: 1].

</details>

### Câu 45
Nguồn PDF: trang 7

Trong mắt người, thành phần nào điều khiển lượng ánh sáng vào mắt?

- A. Võng mạc (retina)
- B. Thủy tinh thể (lens)
- C. Mống mắt (iris)
- D. Tế bào hình que (rods)

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** C. Mống mắt (iris)

**Giải thích:** Trong mô hình sinh lý học của mắt người, con ngươi (pupil) đóng vai trò là cửa sổ thu nhận ánh sáng[cite: 1]. Tuy nhiên, để kiểm soát và điều tiết độ mở của cửa sổ này (quyết định lượng ánh sáng có thể đi qua), mắt dựa vào sự vận động của mống mắt (iris) - một cấu trúc cơ hình khuyên có chức năng hướng tâm[cite: 1].

</details>

### Câu 46
Nguồn PDF: trang 7

Không gian màu nào thường được khuyến nghị dùng để phân vùng màu sắc dựa trên hue?

- A. RGB
- B. HSV
- C. Lab
- D. CMY

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. HSV

**Giải thích:** Không gian màu HSV (Hue, Saturation, Value) mô phỏng cách nhận thức và sắp xếp màu sắc tự nhiên của con người[cite: 1]. Bởi vì kênh Hue chứa toàn bộ thông tin sắc tố/tông màu độc lập hoàn toàn với thông số độ sáng hay độ bão hòa, HSV là hệ thống thường được dùng nhất cho các thuật toán phân vùng hoặc nhận dạng màu sắc[cite: 1].

</details>

### Câu 47
Nguồn PDF: trang 7

Biometrics trong ứng dụng bảo mật bao gồm những gì? (Chọn tất cả đúng)

- A. Nhận diện khuôn mặt
- B. Quét mống mắt
- C. Nhận dạng vân tay
- D. Phân tích giọng nói

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Nhận diện khuôn mặt; B. Quét mống mắt; C. Nhận dạng vân tay

**Giải thích:** Các giải pháp sinh trắc học (Biometrics) thuộc ứng dụng bảo mật (Security Application) trong khuôn khổ môn học Thị giác máy tính xoay quanh việc xử lý hình ảnh[cite: 1]. Chúng bao gồm các hệ thống nhận diện khuôn mặt (face recognition), quét mống mắt (iris), và nhận dạng vân tay (fingerprint) thông qua phân tích mẫu ảnh[cite: 1]. Phân tích giọng nói là bài toán của lĩnh vực xử lý âm thanh[cite: 1].

</details>

### Câu 48
Nguồn PDF: trang 8

Khi quantization levels giảm (ít mức xám hơn), ảnh bị ảnh hưởng như thế nào?

- A. Ảnh bị giảm độ phân giải không gian
- B. Ảnh xuất hiện dải màu giả (false contouring)
- C. Ảnh trở nên sắc nét hơn
- D. Ảnh mờ hơn

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Ảnh xuất hiện dải màu giả (false contouring)

**Giải thích:** Lượng tử hóa (quantization) quyết định số lượng mức xám (bits) để biểu diễn độ chi tiết của cường độ sáng[cite: 1]. Khi số mức xám này bị giảm (ví dụ: chuyển từ 8-bit xuống 4-bit hay 2-bit), sự chuyển tiếp mượt mà giữa các vùng màu bị phá vỡ, dẫn tới hiện tượng phân dải màu giả (false contouring)[cite: 1].

</details>

### Câu 49
Nguồn PDF: trang 8

Ứng dụng robot phẫu thuật liên quan đến Computer Vision như thế nào?

- A. Không có liên quan
- B. CV cung cấp hướng dẫn thị giác cho robot phẫu thuật
- C. CV chỉ dùng để giám sát bệnh nhân
- D. CV dùng để thiết kế robot

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. CV cung cấp hướng dẫn thị giác cho robot phẫu thuật

**Giải thích:** Trong danh mục các ứng dụng y tế (Medicine Application), thị giác máy tính tích hợp trực tiếp vào hệ thống vận hành robot[cite: 1]. Nó thực hiện nhiệm vụ cung cấp hệ thống hướng dẫn bằng thị giác (vision-guided robotics surgery) để robot có khả năng nhận biết tọa độ, nội tạng và thực hiện các vết cắt phẫu thuật một cách chính xác[cite: 1].

</details>

### Câu 50
Nguồn PDF: trang 8

Dải động (dynamic range) của ảnh được tính như thế nào?

- A. Trung bình cường độ sáng
- B. Khoảng từ mức xám nhỏ nhất đến lớn nhất [min, max]
- C. Độ lệch chuẩn của mức xám
- D. Tổng số pixel trong ảnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Khoảng từ mức xám nhỏ nhất đến lớn nhất [min, max]

**Giải thích:** Đặc tính quang học của một bức ảnh số được đánh giá một phần qua dải động (dynamic range)[cite: 1]. Thông số này được định nghĩa là biên độ giới hạn của cường độ ánh sáng, bao gồm khoảng cách trải dài từ giá trị mức xám nhỏ nhất (min intensity) cho đến giá trị mức xám lớn nhất (max intensity) ghi nhận được trên mảng pixel[cite: 1].

</details>

### Câu 51
Nguồn PDF: trang 8

Màu trắng trong RGB có giá trị nào?

- A. (0, 0, 0)
- B. (255, 255, 255)
- C. (128, 128, 128)
- D. (255, 0, 0)

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. (255, 255, 255)

**Giải thích:** RGB là không gian phối màu cộng, trong đó màu sắc hình thành nhờ sự kết hợp các luồng ánh sáng[cite: 1]. Trạng thái màu trắng được tạo ra khi ánh sáng của cả 3 kênh Đỏ (Red), Xanh lá (Green), và Xanh dương (Blue) đều được bật ở mức cường độ phát quang lớn nhất là 255, tức là vector màu (255, 255, 255)[cite: 1].

</details>

### Câu 52
Nguồn PDF: trang 8

Phép "Structure from Motion" sử dụng nguyên lý gì?

- A. Phân tích chuyển động đối tượng
- B. Tái tạo 3D từ chuỗi ảnh 2D
- C. Nhận dạng khuôn mặt
- D. Phân vùng ảnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Tái tạo 3D từ chuỗi ảnh 2D

**Giải thích:** Structure from Motion (SfM) là một kỹ thuật tiên tiến thuộc High-level vision[cite: 1]. Khác với phân tích sự di chuyển của vật thể, SfM hoạt động dựa trên nguyên lý đối chiếu vị trí thông qua chuyển động của camera để tái tạo lại cấu trúc và hình học 3D của cảnh quan bằng cách tính toán đo lường từ một chuỗi các hình ảnh 2D thu được[cite: 1].

</details>

### Câu 53
Nguồn PDF: trang 8

Trong không gian màu Lab, L biểu diễn gì và có giá trị trong khoảng nào?

- A. Màu sắc, 0-360
- B. Độ sáng, 0%-100%
- C. Độ bão hòa, 0-1
- D. Độ xanh lam, -127 đến 127

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Độ sáng, 0%-100%

**Giải thích:** Không gian màu Lab (CIE L*a*b*) tách biệt hoàn toàn thông số màu sắc (chrominance) khỏi ánh sáng[cite: 1]. Thành phần L trong hệ thống này đóng vai trò đại diện cho yếu tố độ sáng (Lightness/Luminance), với thang đo tuyến tính chạy trong khoảng từ 0% (hiển thị màu đen) lên đến 100% (hiển thị màu trắng)[cite: 1].

</details>

### Câu 54
Nguồn PDF: trang 8

Điều nào sau đây là nhược điểm của không gian màu RGB? (Chọn tất cả đúng)

- A. Không phân tách được chrominance và luminance
- B. Phụ thuộc vào thiết bị
- C. Không tuyến tính với cảm nhận màu của mắt người
- D. Khó xử lý bằng máy tính

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Không phân tách được chrominance và luminance; B. Phụ thuộc vào thiết bị; C. Không tuyến tính với cảm nhận màu của mắt người

**Giải thích:** Dù rất phổ biến để hiển thị màn hình, không gian RGB tồn tại nhiều nhược điểm cản trở các thuật toán xử lý ảnh nâng cao[cite: 1]. Cụ thể, hệ màu này gộp chung thông tin màu (chrominance) và độ sáng (luminance) nên dễ bị nhiễu do bóng đổ, nó cũng không tuyến tính với cách mắt người cảm nhận, đồng thời màu sắc hiển thị phụ thuộc chặt chẽ vào đặc tính của thiết bị phần cứng[cite: 1].

</details>

### Câu 55
Nguồn PDF: trang 9

Kênh a* trong không gian màu Lab biểu diễn trục màu nào?

- A. Blue - Yellow
- B. Green - Red
- C. Độ sáng
- D. Màu Cyan - Magenta

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Green - Red

**Giải thích:** Không gian Lab sử dụng hai kênh a* và b* để chứa thông tin đối lập màu[cite: 1]. Kênh a* là biểu diễn của trục phổ màu chạy từ màu xanh lá (green) khi có giá trị âm, sang đến màu đỏ (red) khi có giá trị dương[cite: 1]. Trục Blue-Yellow (B) là nhiệm vụ của kênh b*[cite: 1].

</details>

### Câu 56
Nguồn PDF: trang 9

Ảnh thu nhận từ camera hồng ngoại (infrared) khác ảnh thông thường ở điểm nào?

- A. Ảnh hồng ngoại thu nhận bức xạ nhiệt thay vì ánh sáng nhìn thấy
- B. Ảnh hồng ngoại có độ phân giải cao hơn
- C. Ảnh hồng ngoại luôn là ảnh màu RGB
- D. Ảnh hồng ngoại không thể xử lý bằng CV

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Ảnh hồng ngoại thu nhận bức xạ nhiệt thay vì ánh sáng nhìn thấy

**Giải thích:** Sự khác biệt gốc rễ nằm ở nguyên lý hoạt động của các bộ cảm biến[cite: 1]. Camera kỹ thuật số thông thường thu thập phản xạ của dải ánh sáng nhìn thấy, trong khi camera hồng ngoại (infrared sensor) được thiết kế đặc biệt để bắt sóng và thu nhận bức xạ nhiệt (năng lượng điện từ ngoài vùng sáng) phát ra từ các vật thể[cite: 1].

</details>

### Câu 57
Nguồn PDF: trang 9

Hệ thống thị giác máy tính cơ bản gồm các bước nào theo đúng thứ tự?

- A. Xử lý → Thu nhận → Hiểu
- B. Thu nhận (sensing) → Xử lý → Diễn giải (interpreting)
- C. Diễn giải → Xử lý → Thu nhận
- D. Hiểu → Thu nhận → Xử lý

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Thu nhận (sensing) → Xử lý → Diễn giải (interpreting)

**Giải thích:** Luồng làm việc cơ bản (pipeline) của một hệ thống thị giác máy tính được xây dựng mô phỏng tương đồng với thị giác con người (Human vision)[cite: 1]. Hệ thống bắt đầu bằng quá trình thu nhận dữ liệu từ cảm biến quang học (Sensing), sau đó tiến hành xử lý kỹ thuật số, và bước cuối cùng là diễn giải (Interpreting) để rút trích ý nghĩa của thông tin[cite: 1].

</details>

### Câu 58
Nguồn PDF: trang 9

Khi chuyển ảnh từ RGB sang Grayscale, công thức chuẩn là?

- A. Y = (R+G+B)/3
- B. Y = 0.299R + 0.587G + 0.114B
- C. Y = max(R,G,B)
- D. Y = min(R,G,B)

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Y = 0.299R + 0.587G + 0.114B

**Giải thích:** Mắt người có độ nhạy không đồng đều với các bước sóng ánh sáng (nhạy cảm nhất với ánh sáng xanh lá cây)[cite: 1]. Do đó, khi tính toán và chuyển đổi hình ảnh từ hệ RGB sang ảnh xám chuẩn (Luminance Y), thuật toán phải sử dụng công thức có trọng số phân phối khác nhau: Y = 0.299R + 0.587G + 0.114B[cite: 1].

</details>

### Câu 59
Nguồn PDF: trang 9

Độ phân giải mức xám (quantization) 8-bit cho phép bao nhiêu mức xám?

- A. 128
- B. 256
- C. 512
- D. 1024

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. 256

**Giải thích:** Bước lượng tử hóa (quantization) làm tròn tín hiệu liên tục thành dạng rời rạc để máy tính lưu trữ thông qua bit[cite: 1]. Nếu ảnh sử dụng hệ mã hóa 8-bit, số lượng trạng thái (hoặc số mức xám) cực đại mà mỗi điểm ảnh có thể đảm nhận sẽ được tính bằng lũy thừa $2^8$, cho ra kết quả chính xác là 256 mức độ khác nhau (từ mức 0 đến 255)[cite: 1].

</details>

### Câu 60
Nguồn PDF: trang 9

Cảm biến ảnh trong camera số gồm mảng các thành phần nào?

- A. Bộ khuếch đại tín hiệu
- B. Photodiodes (diode cảm quang)
- C. Bộ chuyển đổi màu
- D. Bộ nén ảnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Photodiodes (diode cảm quang)

**Giải thích:** Trái tim của hệ thống cảm biến quang điện trong các thiết bị như CCD hay CMOS là một mảng mạng lưới chứa vô số các linh kiện bán dẫn[cite: 1]. Các thành phần này được gọi là Photodiodes (diode cảm quang), chịu trách nhiệm hấp thụ hạt photon từ chùm ánh sáng chiếu tới và tạo ra phản ứng chuyển đổi thành dòng electron[cite: 1].

</details>

### Câu 61
Nguồn PDF: trang 9

Điều nào sau đây đúng về Rods (tế bào hình que)?

- A. Có 3 loại nhạy với các bước sóng khác nhau
- B. Cảm thụ màu sắc tốt
- C. Độ nhạy cao, hoạt động trong ánh sáng yếu
- D. Nằm ở trung tâm võng mạc

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** C. Độ nhạy cao, hoạt động trong ánh sáng yếu

**Giải thích:** Mắt người vận hành hai hệ thống cảm quang chuyên biệt[cite: 1]. Khác với tế bào nón, tế bào hình que (Rods) được sinh ra để nhìn ban đêm; chúng sở hữu độ nhạy sáng (sensitivity) cực cao, cho phép con người nhận diện ánh sáng kể cả trong bóng tối nhưng lại hy sinh khả năng nhận diện ra các màu sắc[cite: 1].

</details>

### Câu 62
Nguồn PDF: trang 9

Ảnh đầu ra của xử lý Low-level Vision là gì?

- A. Thông tin ngữ nghĩa (semantic)
- B. Quyết định
- C. Ảnh đã được xử lý
- D. Đặc trưng trừu tượng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** C. Ảnh đã được xử lý

**Giải thích:** Low-level vision (thị giác mức thấp) tập trung thuần túy vào các phép toán ma trận cường độ sáng 2D nhằm tăng cường chất lượng đầu vào như lọc độ ồn, tăng tương phản, hay sửa méo ảnh[cite: 1]. Do đó, đầu vào và đầu ra của phân hệ này luôn duy trì định dạng là một bức ảnh (ảnh đã qua tiền xử lý)[cite: 1].

</details>

### Câu 63
Nguồn PDF: trang 10

Trong camera số, DSP (Digital Signal Processing) được dùng để làm gì?

- A. Thu nhận tín hiệu quang
- B. Chuyển đổi analog sang digital
- C. Tăng cường ảnh và nén dữ liệu
- D. Lưu trữ ảnh vào thẻ nhớ

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** C. Tăng cường ảnh và nén dữ liệu

**Giải thích:** Trong quy trình xử lý nội bộ của camera số, sau khi cảm biến và ADC hoàn tất số hóa ảnh thô, dữ liệu sẽ được chuyển qua chip DSP (Digital Signal Processor)[cite: 1]. Chip này chịu trách nhiệm thực thi các phép thuật toán chuyên sâu như Demosaic (nội suy màu), cân bằng trắng, làm sắc nét (tăng cường ảnh), và cuối cùng là nén thành định dạng JPEG[cite: 1].

</details>

### Câu 64
Nguồn PDF: trang 10

Mức xám của pixel I(x,y) = 0 tương ứng với màu gì?

- A. Trắng
- B. Đen
- C. Xám
- D. Đỏ

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Đen

**Giải thích:** Hệ quy chiếu cơ bản của ảnh kỹ thuật số lượng tử hóa cường độ ánh sáng thành các giá trị số[cite: 1]. Khi một điểm ảnh $I(x,y)$ ghi nhận giá trị bằng 0, điều này biểu thị trạng thái không có bất kỳ luồng ánh sáng/mức năng lượng nào, do đó nó hiển thị màu đen tuyệt đối[cite: 1].

</details>

### Câu 65
Nguồn PDF: trang 10

Ứng dụng nào sau đây là ví dụ của High-level Vision?

- A. Làm mờ ảnh (image blurring)
- B. Tăng tương phản
- C. Nhận dạng đối tượng trong ảnh
- D. Phát hiện cạnh ảnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** C. Nhận dạng đối tượng trong ảnh

**Giải thích:** Trong cấu trúc phân lớp của Computer Vision, High-level Vision xử lý ở cấp độ cao nhất: thấu hiểu ngữ nghĩa hình ảnh[cite: 1]. Tác vụ nhận dạng đối tượng (định danh, phân loại) là một ví dụ thuộc mức này[cite: 1]. Trong khi đó, làm mờ, tăng tương phản là Low-level, còn phát hiện cạnh là Mid-level[cite: 1].

</details>

### Câu 66
Nguồn PDF: trang 10

Màu sắc trong ảnh được tạo ra như thế nào?

- A. Từ nguồn sáng trực tiếp
- B. Từ đáp ứng của bề mặt với chùm sáng chiếu tới
- C. Từ camera sensor
- D. Từ quá trình số hóa

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Từ đáp ứng của bề mặt với chùm sáng chiếu tới

**Giải thích:** Quá trình hình thành hình ảnh của thị giác dựa trên tương tác vật lý của ánh sáng[cite: 1]. Tia sáng sinh ra từ nguồn sẽ chiếu tới vật thể, và màu sắc mà camera hay mắt nhận được thực chất là kết quả của quá trình đáp ứng quang học (phân xạ, phản xạ) bề mặt đối với chùm sáng đó[cite: 1].

</details>

### Câu 67
Nguồn PDF: trang 10

Khi giảm độ phân giải không gian (downsampling), điều gì xảy ra?

- A. Ảnh sắc nét hơn
- B. Số pixel giảm, chi tiết bị mất
- C. Số pixel tăng
- D. Màu sắc thay đổi

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Số pixel giảm, chi tiết bị mất

**Giải thích:** Độ phân giải không gian (spatial resolution) được xác định bằng tần suất lấy mẫu[cite: 1]. Khi giảm chỉ số này (downsampling), thuật toán sẽ bỏ qua hoặc gộp các điểm lưới lại, khiến tổng số pixel cấu thành ảnh bị giảm sút nghiêm trọng, dẫn đến hệ quả là các thông tin chi tiết mảnh bị mất và hình ảnh bị khối hóa hoặc mờ nhòe[cite: 1].

</details>

### Câu 68
Nguồn PDF: trang 10

Ứng dụng phát hiện hàng hóa lỗi trong dây chuyền sản xuất thuộc lĩnh vực nào?

- A. Y tế
- B. Tự động hóa công nghiệp
- C. Bảo mật
- D. Giao thông

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Tự động hóa công nghiệp

**Giải thích:** Hệ thống phát hiện khuyết tật sản phẩm (industrial inspection defect detection) giúp phân tích hình ảnh từ camera giám sát trong các dây chuyền lắp ráp để tự động cảnh báo sản phẩm hỏng[cite: 1]. Đây là một trong những ứng dụng nền tảng của Computer Vision trong nhóm miền Ứng dụng tự động hóa công nghiệp (Industrial Automation Application)[cite: 1].

</details>

### Câu 69
Nguồn PDF: trang 10

Trong HSV, khi Value (V) = 0, pixel có màu gì bất kể H và S?

- A. Trắng
- B. Đỏ
- C. Đen
- D. Xanh lam

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** C. Đen

**Giải thích:** Mô hình không gian HSV biểu diễn sắc thái bằng một khối chóp[cite: 1]. Trong đó, thuộc tính V (Value) quyết định toàn bộ mức cường độ độ sáng của điểm ảnh[cite: 1]. Vì vậy, một khi giá trị V giảm dần về 0 (không có ánh sáng), điểm ảnh đó chắc chắn sẽ hiển thị là màu đen, và các thuộc tính H (màu) hay S (bão hòa) bị vô hiệu hóa hoàn toàn[cite: 1].

</details>

### Câu 70
Nguồn PDF: trang 10

Hình thức lấy mẫu (sampling) trong 2D thường được thực hiện như thế nào?

- A. Lấy mẫu ngẫu nhiên
- B. Lấy mẫu đều trên không gian 2D (uniform grid)
- C. Chỉ lấy mẫu ở biên ảnh
- D. Lấy mẫu theo đường chéo

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Lấy mẫu đều trên không gian 2D (uniform grid)

**Giải thích:** Giai đoạn lấy mẫu tín hiệu số hóa 2D (sampling) yêu cầu tính đồng nhất để có thể lưu trữ dưới dạng ma trận[cite: 1]. Nó thường được thực hiện thông qua việc chia và thu thập mẫu tín hiệu một cách tuần tự, đều đặn trên một hệ thống lưới không gian tọa độ 2D (uniform grid), tạo nên các điểm ảnh pixel xếp cạnh nhau[cite: 1].

</details>

### Câu 71
Nguồn PDF: trang 11

Histogram của ảnh tương phản cao có đặc điểm gì?

- A. Tập trung ở một vùng hẹp
- B. Trải đều trên dải rộng
- C. Chỉ có giá trị ở 0 và 255
- D. Không thể vẽ histogram

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Trải đều trên dải rộng

**Giải thích:** Lược đồ Histogram thống kê và phản ánh phân bố độ sáng tối (mức xám) của ảnh[cite: 1]. Đặc điểm rõ ràng nhất của một bức ảnh có độ tương phản cao (High-contrast image) là nó sở hữu dải động lớn, bao trùm đầy đủ từ chi tiết bóng đổ tối cho tới vùng chói sáng, do đó biểu đồ histogram của nó sẽ phân bố dàn trải trên một dải rất rộng[cite: 1].

</details>

### Câu 72
Nguồn PDF: trang 11

Tại sao cần dùng Lens (thấu kính) trong camera thực tế thay vì pin-hole?

- A. Để tạo ảnh sắc nét hơn
- B. Để thu đủ ánh sáng mà không cần lỗ quá lớn
- C. Để giảm chi phí sản xuất
- D. Để tăng tốc độ chụp

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Để thu đủ ánh sáng mà không cần lỗ quá lớn

**Giải thích:** Mô hình pin-hole lý tưởng tuy đem lại ảnh rõ nét nhưng do lỗ mở siêu bé, lượng sáng thu được không đủ để cảm biến ghi hình trong điều kiện thực tế (thời gian phơi sáng sẽ vô tận)[cite: 1]. Việc thiết kế và sử dụng các hệ thống thấu kính (Lens) trong máy ảnh giải quyết được nghịch lý này, giúp thu gom đủ lượng ánh sáng vật lý để tạo ảnh mà không đòi hỏi phải sử dụng một aperture lớn gây nhòe nét[cite: 1].

</details>

### Câu 73
Nguồn PDF: trang 11

Khái niệm "circle of confusion" trong camera liên quan đến điều gì?

- A. Hiệu ứng khi đối tượng không nằm trong vùng lấy nét
- B. Hiệu ứng nhiễu trong ảnh
- C. Kích thước của sensor
- D. Số lượng pixel trong ảnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Hiệu ứng khi đối tượng không nằm trong vùng lấy nét

**Giải thích:** Trong hệ quang học sử dụng thấu kính mỏng (thin lens), chỉ những vật thể nằm đúng khoảng cách tính toán mới hội tụ chính xác thành một điểm "in focus" trên màng cảm biến[cite: 1]. Nếu đối tượng bị trượt ra ngoài vùng lấy nét này, điểm ảnh sẽ bị tán xạ mờ thành một vòng tròn nhòe hình, tạo ra hiệu ứng mà quang học gọi là "circle of confusion"[cite: 1].

</details>

### Câu 74
Nguồn PDF: trang 11

Điều nào sau đây đúng về không gian màu YCrCb? (Chọn đúng)

- A. Y là thành phần chrominance
- B. Cb = U/2 + 0.5, là thành phần chênh lệch màu xanh lam
- C. Là không gian màu phổ biến nhất trong in ấn
- D. YCrCb không liên quan đến YUV

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Cb = U/2 + 0.5, là thành phần chênh lệch màu xanh lam

**Giải thích:** Hệ không gian màu YCrCb là một dạng chuẩn hóa kỹ thuật số có mối liên hệ mật thiết và chuyển đổi trực tiếp từ gốc YUV[cite: 1]. Trong đó, thành phần Y đặc trưng cho luminance, còn Cb là tín hiệu sắc độ chrominance chuyên biệt tính toán độ chênh lệch của màu xanh lam (blue), được nội suy theo công thức toán học Cb = U/2 + 0.5[cite: 1].

</details>

### Câu 75
Nguồn PDF: trang 11

Phép chuyển đổi giữa các không gian màu trong OpenCV dùng hàm nào?

- A. convertColor()
- B. cvtColor()
- C. changeColor()
- D. transformColor()

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. cvtColor()

**Giải thích:** Trong thư viện lập trình mã nguồn mở OpenCV, tác vụ chuyển đổi ma trận không gian màu (ví dụ từ BGR sang Grayscale, YCrCb, Lab hay HSV) được chuẩn hóa và thực hiện thông qua hàm gọi `cvtColor()`[cite: 1].

</details>

### Câu 76
Nguồn PDF: trang 11

Điều nào đúng về ảnh số (digital image)? (Chọn tất cả đúng)

- A. Là ma trận các giá trị số nguyên
- B. Có thể là 2D (grayscale) hoặc 3D (color)
- C. Mỗi phần tử gọi là pixel
- D. Luôn có 3 kênh màu

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Là ma trận các giá trị số nguyên; B. Có thể là 2D (grayscale) hoặc 3D (color); C. Mỗi phần tử gọi là pixel

**Giải thích:** Về mặt toán học và lưu trữ máy tính, một ảnh số sau khi lượng tử hóa chính là một cấu trúc ma trận tập hợp các số nguyên[cite: 1]. Cấu trúc này có thể ở dạng ma trận 2D (đối với ảnh đa mức xám) hoặc cấu trúc tensor 3D (với ảnh màu), trong đó thành phần đơn vị cơ bản cấu thành ma trận được đặt tên là pixel (điểm ảnh)[cite: 1]. Tính chất "Luôn có 3 kênh màu" (D) là sai vì ảnh xám hoặc nhị phân chỉ sử dụng 1 kênh[cite: 1].

</details>

### Câu 77
Nguồn PDF: trang 11

Khi ánh sáng chiếu sáng thay đổi, không gian màu nào bị ảnh hưởng nhiều nhất trên các kênh màu?

- A. Lab
- B. YCrCb
- C. RGB
- D. HSV (kênh H)

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** C. RGB

**Giải thích:** Các bài kiểm thử mật độ phân bố (density plot) chỉ ra rằng RGB là một mô hình thiết kế không tách biệt chrominance và luminance[cite: 1]. Việc gộp chung này dẫn đến một vấn đề lớn: khi cường độ nguồn chiếu sáng thay đổi, giá trị của toàn bộ ba kênh R, G, B đều sẽ bị kéo lệch biến thiên dữ dội thay vì giữ được trạng thái compact như các hệ độc lập độ sáng khác[cite: 1].

</details>

### Câu 78
Nguồn PDF: trang 11

Ảnh depth (depth image) lưu trữ loại thông tin gì?

- A. Thông tin màu sắc
- B. Khoảng cách từ camera đến mỗi điểm trong cảnh
- C. Thông tin về chuyển động
- D. Thông tin về nhiệt độ

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Khoảng cách từ camera đến mỗi điểm trong cảnh

**Giải thích:** Trong khi ảnh thông thường đo cường độ sáng, một mảng cảm biến đo chiều sâu hoặc hệ thống thị giác máy tính chuyên biệt sử dụng khái niệm Ảnh chiều sâu (depth image)[cite: 1]. Trong loại ảnh số 2D này, giá trị của mỗi pixel không đại diện cho mức xám mà lưu trữ trực tiếp dữ liệu hình học, tức là khoảng cách từ tiêu điểm của camera cho đến điểm tương ứng trên vật thể thực[cite: 1].

</details>

### Câu 79
Nguồn PDF: trang 12

Tiêu cự (focal length) của thấu kính ảnh hưởng đến điều gì?

- A. Khoảng cách lấy nét và góc nhìn của ảnh
- B. Kích thước cảm biến
- C. Số pixel trong ảnh
- D. Tốc độ xử lý ảnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Khoảng cách lấy nét và góc nhìn của ảnh

**Giải thích:** Tiêu cự (focal length), thường được ký hiệu là f trong mô hình thấu kính mỏng, là một tham số vật lý quang học then chốt[cite: 1]. Nó là thành phần tham gia trực tiếp vào việc xác định khoảng cách để một vật thể đạt trạng thái lấy nét (in focus) lên màng phim, đồng thời quyết định tỷ lệ phóng đại và độ rộng hẹp của góc nhìn toàn cảnh thu nhận được[cite: 1].

</details>

### Câu 80
Nguồn PDF: trang 12

Cảm biến nào phù hợp hơn cho ứng dụng di động do tiêu thụ ít điện?

- A. CCD
- B. CMOS
- C. LIDAR
- D. Infrared sensor

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. CMOS

**Giải thích:** Thị trường camera số tiêu chuẩn sử dụng hai loại công nghệ cảm biến chính là CCD và CMOS[cite: 1]. Sự lên ngôi của cảm biến CMOS trong kỷ nguyên điện thoại thông minh (ứng dụng di động) bắt nguồn từ hai lợi thế tuyệt đối của vi mạch loại này: khả năng tiêu thụ một lượng điện năng rất thấp và có thể được sản xuất hàng loạt với giá thành cực rẻ so với đối thủ CCD[cite: 1].

</details>

### Câu 81
Nguồn PDF: trang 12

Phép biến đổi từ RGB sang CMY được tính theo công thức nào?

- A. C = R, M = G, Y = B
- B. C = 1 - R/255, M = 1 - G/255, Y = 1 - B/255
- C. C = 255 - R, M = 255 - G, Y = 255 - B
- D. Cả B và C đều đúng (tùy cách chuẩn hóa)

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** D. Cả B và C đều đúng (tùy cách chuẩn hóa)

**Giải thích:** Hệ màu CMY vận hành theo cơ chế không gian phối màu trừ, ngược lại với hệ phối màu cộng RGB[cite: 1]. Toán học chuyển đổi hai không gian này rất đơn giản thông qua phép tính phần bù: lấy ma trận đơn vị trừ đi RGB (tương đương công thức B nếu giá trị chuẩn hóa tỷ lệ dải 0-1) hoặc lấy giá trị lượng tử hóa tối đa 255 trừ đi giá trị RGB (tương đương công thức C nếu giữ nguyên dải số nguyên 8-bit)[cite: 1].

</details>

### Câu 82
Nguồn PDF: trang 12

Trong Photogrammetry, ảnh được dùng như một thiết bị đo lường gì?

- A. Đo nhiệt độ
- B. Đo khoảng cách và hình học 3D
- C. Đo cường độ âm thanh
- D. Đo điện từ trường

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Đo khoảng cách và hình học 3D

**Giải thích:** Trắc địa ảnh (Photogrammetry) là một trong những bài toán kinh điển của mức xử lý thị giác máy tính nâng cao[cite: 1]. Lĩnh vực này vượt ra khỏi chức năng lưu giữ thông tin ngữ nghĩa thuần túy, nó sử dụng hình ảnh (thường lấy từ trên không) như một thiết bị đo lường chính xác, nhằm tính toán các chỉ số về khoảng cách và tái tạo lại toàn bộ kết cấu hình học 3D không gian thật của cảnh vật[cite: 1].

</details>

### Câu 83
Nguồn PDF: trang 12

Điều nào sau đây mô tả đúng về "sampling theorem" (định lý lấy mẫu)?

- A. Tần số lấy mẫu phải nhỏ hơn tần số tín hiệu
- B. Tần số lấy mẫu phải lớn hơn hoặc bằng 2 lần tần số tín hiệu cao nhất
- C. Lấy mẫu bất kỳ tần số nào cũng được
- D. Tần số lấy mẫu bằng tần số tín hiệu

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Tần số lấy mẫu phải lớn hơn hoặc bằng 2 lần tần số tín hiệu cao nhất

**Giải thích:** Định lý lấy mẫu (Sampling theorem) là định lý toán học nền tảng định hình quá trình số hóa[cite: 1]. Để đảm bảo tín hiệu vật lý liên tục ban đầu có thể được nội suy và phục dựng lại chính xác 100% từ chuỗi dữ liệu mẫu (mảng pixel) thu được, định lý phát biểu bắt buộc tần số lấy mẫu (sampling rate) phải luôn lớn hơn hoặc bằng hai lần mức tần số cao nhất có mặt trong nguồn tín hiệu[cite: 1].

</details>

### Câu 84
Nguồn PDF: trang 12

Khi ảnh bị undersampled, hiện tượng nào xảy ra?

- A. Ảnh trở nên sắc nét hơn
- B. Xuất hiện aliasing (nhiễu tần số)
- C. Màu sắc bị thay đổi
- D. Kích thước file tăng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Xuất hiện aliasing (nhiễu tần số)

**Giải thích:** Tình trạng undersampled xảy ra khi quá trình lấy mẫu vi phạm giới hạn của "định lý lấy mẫu" do tần số lưới quá thưa thớt[cite: 1]. Sự thất thoát dữ liệu tần số cao này dẫn tới việc tín hiệu gốc không được tái tạo nguyên vẹn, sinh ra một lỗi thị giác nghiêm trọng được gọi là hiệu ứng aliasing (nhiễu tần số), tạo ra các răng cưa, moiré hoặc sóng hình học giả trên ảnh[cite: 1].

</details>

### Câu 85
Nguồn PDF: trang 12

Phần mềm OpenCV chủ yếu dùng để làm gì?

- A. Thiết kế giao diện đồ họa
- B. Xử lý ảnh và thị giác máy tính
- C. Phát triển game
- D. Lập trình web

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Xử lý ảnh và thị giác máy tính

**Giải thích:** Open Source Computer Vision Library (OpenCV) là một thư viện phần mềm lập trình mã nguồn mở đa nền tảng[cite: 1]. Thư viện này chứa hàng ngàn thuật toán tối ưu hóa cao độ, được thiết kế và xây dựng như một công cụ chuyên biệt để phục vụ giải quyết các bài toán về xử lý tín hiệu ảnh (Image Processing) và mô phỏng thuật toán thị giác máy tính (Computer Vision)[cite: 1].

</details>

### Câu 86
Nguồn PDF: trang 13

Điều nào sau đây đúng về ảnh nhị phân?

- A. Mỗi pixel có giá trị thuộc {0, 255}
- B. Mỗi pixel có giá trị thuộc {0, 1}
- C. Không thể lưu trữ thông tin hình dạng
- D. Cả A và B đều đúng tùy quy ước

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** D. Cả A và B đều đúng tùy quy ước

**Giải thích:** Ảnh nhị phân là một lớp ảnh có tính chất đặc thù là chỉ tồn tại hai trạng thái thông tin (đen/trắng) tại mỗi điểm pixel, tiêu thụ 1-bit dữ liệu bộ nhớ[cite: 1]. Tùy vào cách mã hóa và quy ước của các hệ thống phần mềm xử lý, pixel có thể nhận chuỗi giá trị nhị phân toán học {0, 1} hoặc được nội suy hiển thị thang màu xám ở mức {0, 255}[cite: 1]. Do đó, cả hai cách tiếp cận A và B đều có thể xảy ra[cite: 1].

</details>

### Câu 87
Nguồn PDF: trang 13

Khi nói ảnh màu có 24-bit depth, điều này có nghĩa là gì?

- A. 24 mức xám cho mỗi pixel
- B. 8 bits cho mỗi kênh R, G, B
- C. Tổng 24 pixel
- D. 24 frames mỗi giây

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. 8 bits cho mỗi kênh R, G, B

**Giải thích:** Chỉ số "depth" (chiều sâu bit) của một bức ảnh kỹ thuật số là thông số quyết định lượng không gian bộ nhớ phân bổ để chứa thông tin cường độ cho mỗi một pixel[cite: 1]. Khi một bức ảnh màu có "24-bit depth", điều đó mô tả việc hệ thống sử dụng không gian 3 bytes, tức là cấp phát tương ứng 8 bits riêng rẽ cho từng kênh màu cơ sở (R, G, B) cấu thành nên điểm ảnh đó[cite: 1].

</details>

### Câu 88
Nguồn PDF: trang 13

Điều nào đúng về cách lưu ảnh màu trong máy tính?

- A. Lưu 1 giá trị duy nhất cho mỗi pixel
- B. Lưu 3 ma trận riêng biệt (R, G, B) hoặc 1 tensor 3D
- C. Luôn lưu dưới dạng nén JPEG
- D. Không thể lưu ảnh màu trong máy tính

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Lưu 3 ma trận riêng biệt (R, G, B) hoặc 1 tensor 3D

**Giải thích:** Do đặc điểm cấu trúc một bức ảnh màu không gian RGB bao gồm tổ hợp 3 kênh cường độ riêng biệt, bộ nhớ máy tính không thể gộp chúng vào một biến số nguyên đơn lẻ[cite: 1]. Thay vào đó, dữ liệu của toàn bộ hình ảnh phải được lưu trữ và lập trình dưới dạng cấu trúc của 3 ma trận 2D độc lập nhau, hoặc được kết hợp thành một cấu trúc không gian đa chiều (tensor 3D) duy nhất[cite: 1].

</details>

### Câu 89
Nguồn PDF: trang 13

Khi kích thước aperture nhỏ (f/32), ảnh có đặc điểm gì?

- A. DOF hẹp, background mờ
- B. DOF rộng, nhiều vùng sắc nét
- C. Ảnh sáng hơn
- D. Noise nhiều hơn

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. DOF rộng, nhiều vùng sắc nét

**Giải thích:** Các hiệu ứng quang học tuân theo nguyên lý tỉ lệ nghịch giữa khẩu độ mở và khoảng lấy nét[cite: 1]. Nếu camera cấu hình kích thước aperture rất nhỏ (ví dụ độ mở khe sáng chỉ đạt f/32), chiều sâu của khoảng không gian lấy nét "in focus" (DOF) sẽ được tăng cường tối đa, từ đó làm cho rất nhiều vùng ảnh bao gồm cả tiền cảnh và hậu cảnh đều duy trì độ sắc nét cao[cite: 1].

</details>

### Câu 90
Nguồn PDF: trang 13

Histogram của ảnh tối (dark image) có đặc điểm gì?

- A. Tập trung ở vùng giá trị cao
- B. Tập trung ở vùng giá trị thấp (gần 0)
- C. Phân bố đều
- D. Có peak ở giữa

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Tập trung ở vùng giá trị thấp (gần 0)

**Giải thích:** Trục hoành của Histogram đại diện cho các mức xám chạy từ màu đen tuyệt đối (0) đến mức sáng trắng (255)[cite: 1]. Một bức ảnh được phân loại là tối (dark image) sẽ chứa tần suất áp đảo của các hạt pixel mang mức năng lượng cực thấp[cite: 1]. Hiện tượng này tạo nên một lược đồ mà các thanh cột (peaks) gần như đều tập trung túm tụm lại toàn bộ ở khu vực vùng xám thấp (gần sát trục 0)[cite: 1].

</details>

### Câu 91
Nguồn PDF: trang 13

Computer Vision khác Image Processing ở điểm chính nào?

- A. Computer Vision chỉ làm việc với ảnh màu
- B. Computer Vision nhắm đến việc hiểu ngữ nghĩa, Image Processing tập trung xử lý pixel
- C. Image Processing phức tạp hơn
- D. Không có sự khác biệt

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Computer Vision nhắm đến việc hiểu ngữ nghĩa, Image Processing tập trung xử lý pixel

**Giải thích:** Hai môn khoa học này có một lằn ranh khác biệt rất rõ về đầu ra mục tiêu[cite: 1]. Xử lý ảnh (Image Processing) là quá trình biến đổi cấp thấp hoạt động trên ma trận (như lọc nhiễu, tăng sắc nét) với dữ liệu xuất vẫn là một bức ảnh mới[cite: 1]. Trong khi đó, Computer Vision (Thị giác máy tính) đóng vai trò diễn giải (interpreting) cấu trúc điểm ảnh thô thành các quyết định và giúp máy tính "hiểu được ngữ nghĩa" đối tượng[cite: 1].

</details>

### Câu 92
Nguồn PDF: trang 13

Trong ứng dụng Facebook face suggestion, kỹ thuật CV nào được sử dụng?

- A. Object detection
- B. Face recognition/identification
- C. Scene classification
- D. Optical flow

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Face recognition/identification

**Giải thích:** Việc đánh dấu gợi ý tự động tag bạn bè của nền tảng mạng xã hội Facebook là một quá trình liên quan mật thiết tới sinh trắc học cá nhân[cite: 1]. Hệ thống không chỉ nhận biết xem có khuôn mặt trong hình hay không, mà còn sử dụng cấp độ CV cao nhất là mạng lưới Face recognition/identification (Định danh khuôn mặt) để trích xuất đặc trưng và xác định xem người đó cụ thể là ai[cite: 1].

</details>

### Câu 93
Nguồn PDF: trang 13

Điều nào mô tả đúng về Rods?

- A. Có khả năng phân biệt màu tốt
- B. Phân bố nhiều ở trung tâm võng mạc
- C. Rất nhạy cảm với ánh sáng, ít nhạy với màu sắc
- D. Chỉ hoạt động trong ánh sáng mạnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** C. Rất nhạy cảm với ánh sáng, ít nhạy với màu sắc

**Giải thích:** Hệ thống thị giác sinh học ở người chia nhiệm vụ cảm quang cho tế bào hình nón và tế bào hình que (Rods)[cite: 1]. Ưu thế tiến hóa của Rods là khả năng đạt độ nhạy cực lớn với các nguồn năng lượng photon tối thiểu, cho phép ta quan sát được trong ánh sáng yếu (nhìn đêm)[cite: 1]. Sự đánh đổi cho năng lực đó là cấu trúc này cực kỳ kém trong việc ghi nhận và phân loại màu sắc[cite: 1].

</details>

### Câu 94
Nguồn PDF: trang 14

Mảng pixel trong ảnh số được tổ chức theo cấu trúc nào?

- A. Ma trận 2D (hoặc tensor 3D với ảnh màu)
- B. Danh sách liên kết
- C. Cây nhị phân
- D. Đồ thị

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Ma trận 2D (hoặc tensor 3D với ảnh màu)

**Giải thích:** Phương thức mã hóa và tổ chức không gian một bức ảnh kỹ thuật số bên trong bộ nhớ máy tính không dùng đến dạng chuỗi như đồ thị[cite: 1]. Thay vào đó, do đặc tính vị trí của các điểm ảnh được lấy mẫu trên một lưới vuông góc đều đặn, ảnh số chuẩn mực được mô phỏng cấu trúc lưới đó dưới dạng các ma trận toán học 2D (hoặc khối ma trận đa chiều tensor 3D để giữ thông tin màu sắc)[cite: 1].

</details>

### Câu 95
Nguồn PDF: trang 14

Ứng dụng "driver vigilance monitoring" (giám sát sự chú ý của tài xế) sử dụng kỹ thuật CV nào chủ yếu?

- A. Phân vùng ảnh
- B. Phát hiện trạng thái mắt và khuôn mặt
- C. Nhận dạng biển số
- D. Ước lượng quỹ đạo

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Phát hiện trạng thái mắt và khuôn mặt

**Giải thích:** Các giải pháp giao thông an toàn (Transportation Application) sử dụng Computer vision để phân tích tính toàn vẹn khả năng lái của con người[cite: 1]. Hệ thống cảnh báo mất tập trung hoặc buồn ngủ ở tài xế (driver vigilance monitoring) xây dựng thuật toán cốt lõi dựa trên việc phát hiện tư thế, tần suất nhắm mở của đôi mắt, và góc độ chuyển động của khuôn mặt theo thời gian thực[cite: 1].

</details>


## CHƯƠNG 3.1: Tăng cường chất lượng ảnh - Lọc ảnh

### Câu 96
Nguồn PDF: trang 14

Brightness của ảnh được định nghĩa là gì?

- A. Độ lệch chuẩn của mức xám
- B. Trung bình cường độ sáng của tất cả pixel
- C. Giá trị lớn nhất trong histogram
- D. Khoảng cách giữa min và max mức xám

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Trung bình cường độ sáng của tất cả pixel

**Giải thích:** Độ sáng (Brightness) của một bức ảnh được định nghĩa toán học là giá trị trung bình cộng cường độ sáng của tất cả các điểm ảnh cấu thành nên nó[cite: 3]. Các đại lượng như độ lệch chuẩn hay khoảng cách giữa min và max được sử dụng để đo lường độ tương phản (Contrast) chứ không phản ánh mức độ sáng tối tổng thể của bức ảnh[cite: 3].

</details>

### Câu 97
Nguồn PDF: trang 14

Contrast (độ tương phản) có thể được tính bằng cách nào? (Chọn tất cả đúng)

- A. Độ lệch chuẩn (standard deviation) của mức xám
- B. Hiệu giữa giá trị max và min mức xám
- C. Trung bình cộng mức xám
- D. Số pixel trong ảnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Độ lệch chuẩn (standard deviation) của mức xám; B. Hiệu giữa giá trị max và min mức xám

**Giải thích:** Độ tương phản (Contrast) thể hiện mức độ phân biệt dễ dàng giữa các đối tượng trong ảnh và thường được đo lường bằng hai phương pháp chính[cite: 3]. Cách thứ nhất là tính độ lệch chuẩn (standard deviation) của mức xám trên toàn ảnh, và cách thứ hai là tính thông qua sự chênh lệch hiệu số giữa giá trị mức xám lớn nhất và nhỏ nhất[cite: 3]. Việc tính trung bình cộng chỉ trả về kết quả Độ sáng (Brightness)[cite: 3].

</details>

### Câu 98
Nguồn PDF: trang 14

Linear stretching với (r1,s1)=(rmin,0) và (r2,s2)=(rmax,255) thực hiện điều gì?

- A. Nén dải động của ảnh
- B. Kéo giãn mức xám về đúng dải [0,255]
- C. Cân bằng histogram
- D. Làm mờ ảnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Kéo giãn mức xám về đúng dải [0,255]

**Giải thích:** Phép biến đổi kéo giãn tuyến tính (Linear stretching) với bộ tham số này có tác dụng tối đa hóa dải động của bức ảnh[cite: 3]. Nó thực hiện ánh xạ điểm ảnh tối nhất của ảnh gốc ($r_{min}$) về giá trị 0 tuyệt đối và điểm ảnh sáng nhất ($r_{max}$) về giới hạn cực đại 255, giúp dải mức xám bị nén trước đó được kéo căng bao phủ toàn bộ dải [0, 255] tiêu chuẩn[cite: 3].

</details>

### Câu 99
Nguồn PDF: trang 14

Piecewise-linear transformation cho phép điều gì mà linear stretching đơn giản không cho phép?

- A. Xử lý ảnh màu
- B. Tăng hoặc giảm tương phản khác nhau ở các khoảng mức xám khác nhau
- C. Giảm nhiễu trong ảnh
- D. Tạo ảnh nhị phân

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Tăng hoặc giảm tương phản khác nhau ở các khoảng mức xám khác nhau

**Giải thích:** Khác với kéo giãn tuyến tính thông thường áp dụng một hàm ánh xạ duy nhất, biến đổi tuyến tính theo đoạn (Piecewise-linear transformation) chia dải mức xám thành nhiều khoảng (segment) bằng các điểm gãy[cite: 3]. Kỹ thuật này trao cho người dùng sự linh hoạt để tăng độ tương phản cực mạnh ở một khoảng mức xám (ví dụ khu vực vật thể chính) và đồng thời làm phẳng giảm tương phản ở khoảng mức xám khác (như vùng nền)[cite: 3].

</details>

### Câu 100
Nguồn PDF: trang 14

Biến đổi Log (s = c × log(1+r)) có tác dụng gì?

- A. Nén các giá trị mức xám cao, kéo giãn các giá trị thấp
- B. Nén các giá trị mức xám thấp, kéo giãn các giá trị cao
- C. Đảo ngược toàn bộ mức xám
- D. Không thay đổi phân bố mức xám

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Nén các giá trị mức xám cao, kéo giãn các giá trị thấp

**Giải thích:** Theo đồ thị đặc trưng của hàm Logarithm, dải giá trị hẹp ở vùng xám thấp (vùng tối) sẽ được ánh xạ vọt lên thành một dải giá trị rất rộng ở đầu ra, tạo hiệu ứng kéo giãn[cite: 3]. Ngược lại, một dải giá trị cực lớn ở vùng xám cao (vùng sáng chói) lại bị đường cong log chặn lại và nén vào một dải hẹp hơn, giúp làm sáng các chi tiết chìm trong bóng tối[cite: 3].

</details>

### Câu 101
Nguồn PDF: trang 15

Trong biến đổi Gamma (s = c × r^γ), khi γ > 1, ảnh bị ảnh hưởng như thế nào?

- A. Vùng tối bị kéo giãn, vùng sáng bị nén
- B. Vùng tối bị nén, vùng sáng bị kéo giãn
- C. Ảnh bị tối đi
- D. Ảnh sáng đều hơn

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Vùng tối bị nén, vùng sáng bị kéo giãn

**Giải thích:** Đối với phép biến đổi Power-Law (Gamma correction), việc cấu hình tham số $\gamma > 1$ sẽ bẻ võng đồ thị ánh xạ xuống phía dưới đường chéo tuyến tính[cite: 3]. Hiệu ứng toán học này khiến các mức xám ở vùng tối bị nén chặt lại sát trục 0, đồng thời kéo giãn khoảng cách của các mức xám ở dải sáng, hệ quả là làm tổng thể bức ảnh trở nên sẫm tối hơn[cite: 3].

</details>

### Câu 102
Nguồn PDF: trang 15

Khi γ < 1 trong Power-Law transformation, ảnh bị ảnh hưởng như thế nào?

- A. Vùng tối bị kéo giãn (ảnh trở nên sáng hơn)
- B. Vùng sáng bị kéo giãn
- C. Ảnh tối hơn
- D. Không thay đổi

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Vùng tối bị kéo giãn (ảnh trở nên sáng hơn)

**Giải thích:** Hoàn toàn đảo ngược với trường hợp trên, việc thiết lập $\gamma < 1$ tạo ra một đường cong ánh xạ vồng lên phía trên[cite: 3]. Đường cong này hoạt động mạnh tay ở các mức năng lượng thấp bằng cách giãn rộng các giá trị trong dải tối (dark area) và nén các giá trị trên vùng sáng chói lại, giúp các chi tiết khuất bóng hiện rõ nét và đẩy tổng thể ảnh trở nên sáng sủa hơn[cite: 3].

</details>

### Câu 103
Nguồn PDF: trang 15

Histogram equalization (cân bằng histogram) hướng đến phân phối mức xám như thế nào?

- A. Phân phối chuẩn (Gaussian)
- B. Phân phối đều (uniform)
- C. Tập trung tại một điểm
- D. Phân phối mũ

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Phân phối đều (uniform)

**Giải thích:** Cân bằng lược đồ xám (Histogram equalization) là phương pháp tự động dàn xếp lại các mức phân bố sắc độ trên một bức ảnh[cite: 3]. Mục tiêu tối hậu (hoặc đích đến lý tưởng) của quy trình biến đổi này là chuyển một histogram ban đầu gồ ghề, mất cân đối thành một histogram mới tiệm cận với trạng thái phân phối đều (uniform distribution) trên toàn bộ dải mức xám[cite: 3].

</details>

### Câu 104
Nguồn PDF: trang 15

Các bước của histogram equalization theo đúng thứ tự là?

- A. Tính CDF → đếm nk → chuẩn hóa → ánh xạ
- B. Đếm nk → tính histogram chuẩn hóa p(k) → tính CDF T(k) → ánh xạ sk
- C. Ánh xạ → đếm nk → tính p(k) → tính T(k)
- D. Tính p(k) → ánh xạ → tính T(k) → đếm nk

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Đếm nk → tính histogram chuẩn hóa p(k) → tính CDF T(k) → ánh xạ sk

**Giải thích:** Để thực hiện thuật toán cân bằng histogram, hệ thống tuân theo quy trình tuyến tính: Khởi đầu bằng việc quét đếm lượng điểm ảnh $n_k$ tương ứng tại mỗi mức xám[cite: 3]. Bước kế tiếp là chuẩn hóa $n_k$ chia cho tổng pixel để ra xác suất $p(k)$[cite: 3]. Từ $p(k)$, ta cộng dồn để thu được hàm phân bố tích lũy $T(k)$ (CDF), rồi nhân làm tròn để tìm được hàm ánh xạ ra mức xám mục tiêu $s_k$[cite: 3].

</details>

### Câu 105
Nguồn PDF: trang 15

Histogram equalization có tham số cần chỉnh không?

- A. Có, cần chỉnh threshold
- B. Có, cần chỉnh số bins
- C. Không, là phương pháp không tham số
- D. Có, cần chỉnh gamma

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** C. Không, là phương pháp không tham số

**Giải thích:** Trong khi các kỹ thuật Linear stretching hay Gamma correction đòi hỏi người lập trình phải tinh chỉnh tham số đầu vào (như độ dốc hay hệ số $\gamma$), thì Histogram Equalization (Cân bằng histogram) lại hoạt động trên cơ sở hàm tích lũy dữ liệu nội tại[cite: 3]. Do đó, đây là một phương pháp phi tham số (non-parametric), tự động điều chỉnh mà không cần chuyên gia can thiệp[cite: 3].

</details>

### Câu 106
Nguồn PDF: trang 15

Trong OpenCV, hàm nào thực hiện histogram equalization cho ảnh grayscale?

- A. cv2.normalize()
- B. cv2.equalizeHist()
- C. cv2.calcHist()
- D. cv2.threshold()

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. cv2.equalizeHist()

**Giải thích:** Trong thư viện lập trình mã nguồn mở xử lý ảnh OpenCV, thao tác dàn phẳng lược đồ mức xám (cân bằng histogram) cho ảnh đơn kênh (grayscale) đã được các nhà phát triển đóng gói sẵn thành API dưới định danh hàm là `cv2.equalizeHist(img)`[cite: 3].

</details>

### Câu 107
Nguồn PDF: trang 15

Tại sao KHÔNG khuyến nghị áp dụng histogram equalization trực tiếp trên từng kênh R, G, B?

- A. Vì OpenCV không hỗ trợ
- B. Vì có thể tạo ra thay đổi màu bất bình thường
- C. Vì quá chậm
- D. Vì kết quả không thay đổi

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Vì có thể tạo ra thay đổi màu bất bình thường

**Giải thích:** Cấu trúc màu sắc tổng thể của không gian RGB hình thành nhờ sự phân phối tỷ lệ phối kết hợp nhất định giữa ba kênh Đỏ (R), Xanh lá (G) và Xanh dương (B)[cite: 3]. Nếu tiến hành áp dụng độc lập toán tử Histogram Equalization lên riêng rẽ từng kênh, tỷ lệ trộn màu tương đối bị phá vỡ hoàn toàn, sinh ra hiện tượng ám màu hoặc làm thay đổi màu sắc gốc một cách bất bình thường[cite: 3].

</details>

### Câu 108
Nguồn PDF: trang 15

Phương pháp nào được khuyến nghị cho histogram equalization trên ảnh màu?

- A. Áp dụng trực tiếp trên R, G, B
- B. Chuyển sang Lab/HSV, equalize kênh L/V, chuyển ngược lại RGB
- C. Equalize kênh xanh lam trước
- D. Chỉ equalize kênh đỏ

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Chuyển sang Lab/HSV, equalize kênh L/V, chuyển ngược lại RGB

**Giải thích:** Để vượt qua nhược điểm thay đổi màu của hệ RGB, phương pháp chuẩn mực là phải ánh xạ ảnh sang một hệ quy chiếu mới (như HSL, HSV, hay Lab) - nơi mà thông số độ sáng được cô lập riêng biệt với thành phần sắc độ[cite: 3]. Khi đó, ta chỉ việc xử lý cân bằng trên trục ánh sáng (kênh L hoặc V) mà không chạm vào cấu trúc màu, rồi sau đó chuyển ảnh ngược trở lại không gian hiển thị RGB[cite: 3].

</details>

### Câu 109
Nguồn PDF: trang 16

Lọc ảnh trong miền không gian (spatial domain filtering) hoạt động dựa trên nguyên lý nào?

- A. Biến đổi ảnh sang miền tần số trước khi xử lý
- B. Tính giá trị mới của mỗi pixel dựa trên giá trị của các pixel lân cận
- C. Thay thế ngẫu nhiên các pixel
- D. Nhân từng pixel với một hằng số

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Tính giá trị mới của mỗi pixel dựa trên giá trị của các pixel lân cận

**Giải thích:** Phép toán lọc ảnh trong miền không gian (spatial domain filtering) can thiệp trực tiếp lên cấu trúc hình học của ma trận tọa độ ảnh[cite: 3]. Khác với biến đổi cục bộ độc lập (point processing), một bộ lọc không gian hoạt động thông qua một mask/kernel để rà soát, sau đó tính toán ra mức xám mới cho một pixel phụ thuộc vào một hàm liên kết các giá trị của các pixel lân cận xung quanh nó[cite: 3].

</details>

### Câu 110
Nguồn PDF: trang 16

Phép convolution (nhân chập) I' = I * K được tính như thế nào?

- A. Nhân từng phần tử tương ứng (element-wise)
- B. Tổng có trọng số của pixel trong lân cận
- C. Cộng hai ma trận
- D. Lấy giá trị trung bình của toàn ảnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Tổng có trọng số của pixel trong lân cận

**Giải thích:** Phép nhân chập (Convolution) là cốt lõi của xử lý ảnh tuyến tính[cite: 3]. Giá trị điểm ảnh mục tiêu sau nhân chập được nội suy thông qua phép tính tổng có trọng số (weighted sum) giữa các giá trị điểm ảnh gốc trong khoảng không gian lân cận và các hệ số tương ứng nằm trên mặt nạ (kernel) đang trượt qua[cite: 3].

</details>

### Câu 111
Nguồn PDF: trang 16

Sự khác biệt chính giữa Correlation và Convolution là gì?

- A. Correlation dùng kernel bị xoay 180°, Convolution thì không
- B. Convolution dùng kernel bị xoay 180°, Correlation thì không
- C. Chúng hoàn toàn giống nhau
- D. Correlation nhanh hơn Convolution

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Convolution dùng kernel bị xoay 180°, Correlation thì không

**Giải thích:** Khi áp dụng lên mảng điểm ảnh, hai kỹ thuật không gian này (Tương quan và Nhân chập) sở hữu phương trình tính toán có cấu trúc giống hệt nhau[cite: 3]. Tuy nhiên, điểm phân biệt rạch ròi duy nhất là phép Convolution yêu cầu ma trận kernel/mặt nạ phải bị lật ngược (xoay 180 độ theo cả hai trục x và y) trước khi tính tổng chập, trong khi phép Correlation áp dụng trực tiếp nguyên bản[cite: 3].

</details>

### Câu 112
Nguồn PDF: trang 16

Khi nào Correlation và Convolution cho kết quả giống nhau?

- A. Khi kernel có kích thước 1×1
- B. Khi kernel đối xứng
- C. Khi ảnh đầu vào là ảnh đen trắng
- D. Khi kích thước kernel lớn

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Khi kernel đối xứng

**Giải thích:** Bản chất toán học thiết lập rằng Convolution là sự sao chép của Correlation đi kèm với bước lật kernel 180 độ[cite: 3]. Do đó, trong trường hợp mà ma trận trọng số của kernel được thiết kế đối xứng hoàn hảo qua tâm (như Gaussian filter hoặc Mean filter), việc xoay 180 độ không hề làm thay đổi vị trí các hệ số, khiến kết quả trả về của Convolution và Correlation tự động trở nên đồng nhất[cite: 3].

</details>

### Câu 113
Nguồn PDF: trang 16

Tính chất kết hợp (associative) của Convolution: I * h * g = ?

- A. I * (h + g)
- B. I * (h * g)
- C. (I * h) + g
- D. I + h * g

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. I * (h * g)

**Giải thích:** Phép toán nhân chập (Convolution) kế thừa tính chất kết hợp chuỗi (associative property) trong đại số tuyến tính: $I * h * g = I * (h * g)$[cite: 3]. Nhờ định lý này, thay vì phải tốn tài nguyên chạy hai vòng lặp nhân chập ảnh $I$ liên tiếp với mặt nạ $h$ rồi đến $g$, hệ thống có thể gộp trước hai mặt nạ nhỏ lại với nhau ($h * g$) thành một mặt nạ lớn duy nhất để quét qua ảnh một lần[cite: 3].

</details>

### Câu 114
Nguồn PDF: trang 16

Bộ lọc mean filter (trung bình) dùng để làm gì?

- A. Phát hiện cạnh ảnh
- B. Làm trơn ảnh và lọc nhiễu
- C. Tăng tương phản
- D. Chuyển ảnh sang grayscale

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Làm trơn ảnh và lọc nhiễu

**Giải thích:** Bộ lọc trung bình (Mean filter) thuộc họ các bộ lọc thông thấp (low-pass filter), có xu hướng dìm bớt sự chênh lệch sắc thái cực đoan[cite: 3]. Tác dụng chính của nó là thay thế các điểm ảnh bằng trung bình cộng của khu vực, giúp khử đi các điểm nhiễu (noise) lấm tấm, làm phẳng và làm trơn mượt bề mặt hình ảnh (smoothing)[cite: 3].

</details>

### Câu 115
Nguồn PDF: trang 16

Tại sao tổng các hệ số trong kernel của bộ lọc làm trơn phải bằng 1?

- A. Để đảm bảo kernel có thể phân tách
- B. Để tránh thay đổi độ sáng trung bình của ảnh
- C. Để giảm độ phức tạp tính toán
- D. Để kernel có kích thước lẻ

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Để tránh thay đổi độ sáng trung bình của ảnh

**Giải thích:** Khi kernel làm trơn lướt qua để tính trung bình tổng hợp, nó có thể khuếch đại hoặc làm suy giảm dòng năng lượng tín hiệu nếu các trọng số không được cấu hình chuẩn[cite: 3]. Yêu cầu thiết kế khắt khe đặt ra là tổng của mọi hệ số cấu thành mặt nạ bắt buộc phải được chuẩn hóa về mức 1.0 (ví dụ chia cho 9 với kernel $3\times3$ toàn 1) để bảo đảm không làm thay đổi hoặc làm sai lệch cường độ sáng trung bình của bức ảnh sau khi lọc[cite: 3].

</details>

### Câu 116
Nguồn PDF: trang 16

Bộ lọc Gaussian ưu việt hơn Mean filter ở điểm nào?

- A. Nhanh hơn
- B. Làm trơn tốt hơn, ít gây hiệu ứng blocky
- C. Dễ cài đặt hơn
- D. Nhỏ hơn về kích thước

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Làm trơn tốt hơn, ít gây hiệu ứng blocky

**Giải thích:** Trong khi bộ lọc Mean gán trọng số cào bằng cho tất cả các điểm tạo ra biên mờ sắc cạnh kiểu khối vuông (blocky effect), bộ lọc Gaussian mô phỏng tính chất phân tán tự nhiên bằng cách gán trọng số cao nhất ở tâm và giảm dần theo hình chuông[cite: 3]. Điều này giúp nó làm mờ trơn tru, khử nhiễu tự nhiên hơn mà không phá nát các cấu trúc chi tiết hữu ích[cite: 3].

</details>

### Câu 117
Nguồn PDF: trang 17

Quy tắc thực hành cho Gaussian filter: bán kính filter nên đặt bằng bao nhiêu lần σ?

- A. 1σ
- B. 2σ
- C. 3σ
- D. 5σ

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** C. 3σ

**Giải thích:** Phân phối Gaussian kéo dài đến vô cực về mặt toán học, nhưng trong xử lý tín hiệu thực tế, năng lượng dồn chủ yếu quanh tâm[cite: 3]. "Quy tắc kinh nghiệm" (Rule of thumb) để thiết lập một kernel giới hạn là đặt bán kính (filter half-width) của mặt nạ xấp xỉ bằng giá trị $3\sigma$, nhằm đảm bảo bao phủ hơn 99% mật độ tín hiệu mà không làm lãng phí kích thước tính toán[cite: 3].

</details>

### Câu 118
Nguồn PDF: trang 17

Tính chất separability của Gaussian filter 2D có nghĩa là gì?

- A. Có thể áp dụng cho ảnh màu
- B. G(x,y) = G(x) × G(y), cho phép thực hiện 2 convolution 1D thay vì 1 convolution 2D
- C. Có thể tách ra các tần số khác nhau
- D. Kernel có thể chia làm 2 phần bằng nhau

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. G(x,y) = G(x) × G(y), cho phép thực hiện 2 convolution 1D thay vì 1 convolution 2D

**Giải thích:** Tính chất phân tách (separability) là một món quà toán học quý giá của hàm Gaussian 2D, chứng minh rằng ma trận vuông 2D có thể được cấu thành từ phép nhân hai vector 1D độc lập $G_\sigma(x, y) = G_\sigma(x) \cdot G_\sigma(y)$[cite: 3]. Sự phân tách này cho phép hệ thống lập trình đổi từ việc áp một kernel nD nặng nề sang việc chạy song song hai mặt nạ 1D (hàng và cột), giảm thiểu số phép nhân số học đi nhiều lần[cite: 3].

</details>

### Câu 119
Nguồn PDF: trang 17

Kết quả của I*Gσ*Gσ bằng gì?

- A. I * G(2σ)
- B. I * G(σ²)
- C. I * G(σ√2)
- D. I * G(σ/2)

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** C. I * G(σ√2)

**Giải thích:** Nhân chập liên tiếp hai hàm Gaussian sinh ra một hàm Gaussian mới có phương sai được cộng gộp ($\sigma^2_{new} = \sigma^2 + \sigma^2 = 2\sigma^2$)[cite: 3]. Do đó, thay vì phải chạy bộ lọc qua bức ảnh hai lần với độ lệch chuẩn $\sigma$ ($I * G_\sigma * G_\sigma$), ta hoàn toàn có thể trích xuất kết quả tương tự thông qua một phép nhân chập duy nhất bằng một hạt nhân Gaussian lớn hơn có độ rộng là $\sigma\sqrt{2}$[cite: 3].

</details>

### Câu 120
Nguồn PDF: trang 17

Sobel filter được dùng để làm gì?

- A. Làm trơn ảnh
- B. Tính đạo hàm bậc 1 (gradient) theo chiều x và y
- C. Tính đạo hàm bậc 2
- D. Tăng tương phản

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Tính đạo hàm bậc 1 (gradient) theo chiều x và y

**Giải thích:** Bộ lọc Sobel là một toán tử tích chập không gian $3\times3$ đóng vai trò cốt lõi trong các thuật toán phát hiện biên hình[cite: 5]. Ứng dụng gốc của mặt nạ Sobel là cung cấp một xấp xỉ tuyến tính để tính toán tốc độ thay đổi cường độ sáng (đạo hàm rời rạc bậc 1 - gradient) dọc theo hai hướng trực giao riêng biệt: trục hoành $x$ và trục tung $y$[cite: 5].

</details>

### Câu 121
Nguồn PDF: trang 17

Bộ lọc Laplacian (∇²f) dựa trên đạo hàm bậc mấy?

- A. Bậc 1
- B. Bậc 2
- C. Bậc 0 (không đạo hàm)
- D. Đạo hàm riêng bậc 1

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Bậc 2

**Giải thích:** Không giống như các bộ lọc gradient Sobel đo lường tốc độ, toán tử Laplacian ($\nabla^2 f$) được cấu thành từ tổng của các đạo hàm riêng bậc 2 theo không gian $\left(\frac{\partial^2 f}{\partial x^2} + \frac{\partial^2 f}{\partial y^2}\right)$[cite: 3]. Nhờ tính chất đo lường gia tốc biến thiên này, Laplacian thể hiện đặc tính cắt ngang mức 0 (zero-crossing) ngay tại đỉnh của đường biên[cite: 5].

</details>

### Câu 122
Nguồn PDF: trang 17

Sharpening filter sử dụng Laplacian được tính theo công thức nào?

- A. f' = f + ∇²f
- B. f' = f - ∇²f (khi dùng Laplacian dương ở trung tâm)
- C. f' = f × ∇²f
- D. f' = ∇²f

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. f' = f - ∇²f (khi dùng Laplacian dương ở trung tâm)

**Giải thích:** Bộ lọc làm sắc nét (sharpening filter) hoạt động theo nguyên lý tái cấu trúc tần số cao: $f'(x,y) = f(x,y) \pm \nabla^2 f(x,y)$[cite: 3]. Chiều của phép toán (cộng hay trừ) phụ thuộc thuần túy vào thiết kế của ma trận Laplacian. Nếu phần tử ở trung tâm mang hệ số âm, ta dùng phép cộng; ngược lại, nếu mặt nạ Laplacian có hệ số trung tâm mang tính chất dương, ta phải sử dụng công thức trừ để khôi phục và khuếch đại đường biên[cite: 3].

</details>

### Câu 123
Nguồn PDF: trang 17

Ưu điểm của Median filter so với Mean filter là gì?

- A. Nhanh hơn
- B. Bảo toàn cạnh và hiệu quả với salt & pepper noise
- C. Có tính kết hợp
- D. Sử dụng ít bộ nhớ hơn

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Bảo toàn cạnh và hiệu quả với salt & pepper noise

**Giải thích:** Mean filter dễ bị tổn thương bởi các điểm dữ liệu dị biệt (outlier) và thường xuyên làm nát cấu trúc viền ảnh[cite: 3]. Ưu thế tuyệt đối của Median filter (Lọc trung vị) nằm ở khả năng bỏ qua các giá trị biên độ nhiễu xung cực đoan (nhiễu muối tiêu - salt & pepper noise), qua đó giúp "tẩy rửa" bức ảnh một cách đáng kinh ngạc trong khi vẫn giữ nguyên vẹn độ sắc bén của các đường biên (edge preserving)[cite: 3].

</details>

### Câu 124
Nguồn PDF: trang 17

Median filter thuộc loại bộ lọc nào?

- A. Tuyến tính (linear)
- B. Phi tuyến (non-linear)
- C. Tuyến tính cục bộ
- D. Tần số thấp

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Phi tuyến (non-linear)

**Giải thích:** Khác với bộ lọc trung bình tính toán một tổng có trọng số (phép toán cộng tuyến tính), bộ lọc trung vị yêu cầu máy tính phải trích xuất khu vực lân cận rồi tiến hành thuật toán sắp xếp độ lớn (sorting) để mò tìm ra giá trị đứng giữa[cite: 3]. Vì cơ chế này không tuân theo các nguyên lý xếp chồng đại số, Median filter bị liệt vào nhóm bộ lọc phi tuyến tính (non-linear filter)[cite: 3].

</details>

### Câu 125
Nguồn PDF: trang 18

Bộ lọc nào phù hợp nhất để loại bỏ nhiễu muối tiêu (salt and pepper noise)?

- A. Mean filter
- B. Gaussian filter
- C. Median filter
- D. Laplacian filter

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** C. Median filter

**Giải thích:** Nhiễu muối tiêu (salt and pepper) gây ra các đốm nhấp nháy đen tuyền hoặc trắng bóc trên nền ảnh, mang giá trị cực trị[cite: 3]. Vì bộ lọc trung vị (Median filter) vận hành thông qua phép phân loại thứ tự, các đốm nhiễu dị biệt này sẽ bị đẩy ra hai rìa xa nhất của mảng dữ liệu. Kết quả trung vị được chọn luôn là một mức xám ổn định thuộc về cấu trúc vật thể, quét sạch hoàn toàn nhiễu muối tiêu[cite: 3].

</details>

### Câu 126
Nguồn PDF: trang 18

Max filter có tác dụng tương tự phép toán hình thái nào?

- A. Erosion
- B. Dilation
- C. Opening
- D. Closing

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Dilation

**Giải thích:** Dưới góc nhìn toán học, bộ lọc cực đại (Max filter) tìm kiếm và đẩy giá trị mức xám lớn nhất (sáng nhất) lên làm trung tâm của khu vực trượt[cite: 3]. Hành vi khuếch đại này vô hình chung mở rộng vùng hiển thị của các khối vật thể sáng, tạo ra một tác động làm phình to hoàn toàn tương đương (có tác dụng tương tự) với phép toán giãn nở Dilation trong nhóm hình thái học (morphological operations)[cite: 3].

</details>

### Câu 127
Nguồn PDF: trang 18

Min filter có tác dụng tương tự phép toán hình thái nào?

- A. Erosion
- B. Dilation
- C. Opening
- D. Closing

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Erosion

**Giải thích:** Cùng nguyên lý với thao tác Min filter thay thế điểm ảnh ở giữa bằng điểm tối nhất của lân cận, bức ảnh sẽ bị chìm dần trong không gian màu tối[cite: 3]. Mép của các hình khối sáng do đó sẽ bị gặm mòn và co ngót lại, phản chiếu hoàn hảo đặc tính cơ bản của phép toán Erosion (Co hẹp / Ăn mòn) trong việc bóc tách cấu trúc ảnh[cite: 3].

</details>

### Câu 128
Nguồn PDF: trang 18

Phép Dilation trong morphological operations làm gì với ảnh nhị phân?

- A. Thu nhỏ các vùng foreground
- B. Mở rộng các vùng foreground, lấp đầy lỗ
- C. Loại bỏ các vật thể nhỏ
- D. Tìm biên của đối tượng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Mở rộng các vùng foreground, lấp đầy lỗ

**Giải thích:** Khi phần tử cấu trúc (structuring element) quét qua viền, phép toán Dilation (Giãn nở) sẽ thêm các điểm ảnh vào viền của ranh giới kết nối (đối tượng màu trắng/foreground)[cite: 3]. Hành vi kết tụ và lan tỏa diện tích này đóng vai trò quan trọng trong việc khỏa lấp, san phẳng các lỗ hổng (fill holes) và nối liền các thành phần liền kề bị rạn nứt[cite: 3].

</details>

### Câu 129
Nguồn PDF: trang 18

Phép Erosion trong morphological operations làm gì?

- A. Mở rộng vùng foreground
- B. Thu nhỏ vùng foreground, loại bỏ nhiễu nhỏ
- C. Lấp đầy các lỗ hổng
- D. Cộng hai ảnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Thu nhỏ vùng foreground, loại bỏ nhiễu nhỏ

**Giải thích:** Trái ngược với Dilation, phép toán Erosion (Ăn mòn) sẽ gọt rửa các lớp vỏ pixel bên ngoài của đối tượng foreground mỗi khi phần tử cấu trúc quét trượt ra ngoài rìa[cite: 3]. Sự bào mòn khốc liệt này làm cho vật thể (shrink features) thon gọn lại đáng kể, giúp triệt tiêu sạch sẽ các cây cầu kết nối mỏng (bridges) và bóp chết các mảng nhiễu rác nhỏ li ti trên nền ảnh[cite: 3].

</details>

### Câu 130
Nguồn PDF: trang 18

Opening (mở) bằng morphology được định nghĩa là?

- A. Dilation rồi Erosion
- B. Erosion rồi Dilation
- C. Chỉ Erosion
- D. Chỉ Dilation

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Erosion rồi Dilation

**Giải thích:** Phép Opening (Mở) ($A \circ B$) không phải là một thuật toán độc lập mà là một quy trình chuỗi liên kết tuyến tính[cite: 3]. Nó được định nghĩa rạch ròi bằng việc thực hiện lần lượt phép Erosion (để cắt tỉa) lên bức ảnh trước tiên, sau đó tái sử dụng cùng một phần tử cấu trúc đó để chạy tiếp lệnh Dilation (giãn nở) nhằm khôi phục tàn dư[cite: 3].

</details>

### Câu 131
Nguồn PDF: trang 18

Closing (đóng) bằng morphology được định nghĩa là?

- A. Erosion rồi Dilation
- B. Dilation rồi Erosion
- C. Chỉ Erosion
- D. Chỉ Dilation

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Dilation rồi Erosion

**Giải thích:** Đối lập logic với Opening, phép Closing (Đóng) ($A \bullet B$) đòi hỏi máy tính phải kích hoạt mô đun Dilation (Giãn nở) trước tiên để khỏa lấp toàn bộ các lỗ nứt[cite: 3]. Kế đến, ảnh phình to này sẽ bị ép qua mô đun Erosion (Ăn mòn) để loại trừ diện tích mép dư thừa, đưa chu vi vật thể trở về tiệm cận nguyên bản[cite: 3].

</details>

### Câu 132
Nguồn PDF: trang 18

Opening có tác dụng gì đặc biệt?

- A. Lấp đầy lỗ hổng, giữ hình dạng ban đầu
- B. Loại bỏ các đối tượng nhỏ, giữ hình dạng ban đầu
- C. Kết nối các đối tượng riêng lẻ
- D. Làm mờ ảnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Loại bỏ các đối tượng nhỏ, giữ hình dạng ban đầu

**Giải thích:** Giai đoạn ăn mòn (Erosion) tiên phong trong phép Opening đảm bảo càn quét triệt để các đốm nhiễu và "giết chết" bất kỳ đối tượng nào có hình thù mỏng hoặc bé hơn lõi của phần tử cấu trúc[cite: 3]. Bước giãn nở (Dilation) hậu kỳ chỉ có khả năng làm hồi sinh kích thước của những vật thể lớn vững chắc đã vượt qua bước một, giúp bảo vệ hình thái (giữ hình dạng ban đầu) cho các thực thể quan trọng[cite: 3].

</details>

### Câu 133
Nguồn PDF: trang 19

Closing có tác dụng gì đặc biệt?

- A. Loại bỏ các đối tượng nhỏ
- B. Lấp đầy các lỗ hổng nhỏ, giữ hình dạng ban đầu
- C. Tách các đối tượng dính nhau
- D. Tăng tương phản

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Lấp đầy các lỗ hổng nhỏ, giữ hình dạng ban đầu

**Giải thích:** Cú đánh mạnh mẽ của Dilation ngay phần mở màn trong quy trình Closing giúp bơm căng các mô hình, qua đó ép kín, hàn liền tất cả các khe rãnh đứt đoạn và những "lỗ hổng" kẹt trong lòng vật thể (fill holes)[cite: 3]. Khi hình thái ảnh sau đó bị gọt lại bởi nhát cắt Erosion, nó sẽ giữ nguyên được cấu hình dáng vóc ban đầu (keep original shape) nhưng nội hàm đã trở nên đặc ruột[cite: 3].

</details>

### Câu 134
Nguồn PDF: trang 19

Connected component labeling dùng để làm gì? (Chọn tất cả đúng)

- A. Đếm số đối tượng trong ảnh
- B. Tách các đối tượng riêng biệt
- C. Tạo mask cho từng đối tượng
- D. Tính diện tích từng đối tượng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Đếm số đối tượng trong ảnh; B. Tách các đối tượng riêng biệt; C. Tạo mask cho từng đối tượng; D. Tính diện tích từng đối tượng

**Giải thích:** Thuật toán đánh nhãn thành phần liên thông (Connected component labeling) quét qua ma trận ảnh để phát hiện và gán một mã ID định danh duy nhất (label) cho mỗi cụm pixel liền kề nhau[cite: 3]. Việc gán ID này trực tiếp đáp ứng các mục tiêu (Objectifs) quan trọng như: đếm số lượng vật thể hiện diện, trích xuất tách rời chúng, tạo mặt nạ (mask) khoanh vùng, và thống kê diện tích (số lượng pixel cùng nhãn)[cite: 3].

</details>

### Câu 135
Nguồn PDF: trang 19

Thresholding trong xử lý ảnh dùng để làm gì?

- A. Tăng tương phản ảnh
- B. Chuyển ảnh grayscale sang ảnh nhị phân dựa trên ngưỡng
- C. Lọc nhiễu
- D. Phát hiện chuyển động

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Chuyển ảnh grayscale sang ảnh nhị phân dựa trên ngưỡng

**Giải thích:** Phân đoạn ngưỡng (Thresholding) là thao tác so sánh cường độ của một bức ảnh mức xám với một vạch định mức (threshold) duy nhất[cite: 3]. Kết quả của bộ lọc này buộc tất cả pixel nằm trên vạch sẽ thắp sáng thành 1, và dưới vạch sẽ chìm xuống 0, hoàn thành xuất sắc vai trò chuyển đổi định dạng ảnh đa xám (grayscale) thành một ma trận ảnh nhị phân (binary output)[cite: 3].

</details>

### Câu 136
Nguồn PDF: trang 19

Phép toán "Lấy âm bản" của ảnh (negative) được tính bằng công thức nào?

- A. s = r + (L-1)
- B. s = (L-1) - r
- C. s = r × (L-1)
- D. s = r / (L-1)

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. s = (L-1) - r

**Giải thích:** Phép toán "Lấy âm bản" (Negative transformation) là một hàm tuyến tính nghịch đảo nhắm tới việc hoán đổi bản chất ánh sáng: chuyển vùng sáng chói thành tối đen và bù lại vùng bóng tối thành ánh sáng trắng[cite: 3]. Công thức thực tiễn của nó là đảo cực giá trị cường độ $r$ bằng cách trừ nó ra khỏi giới hạn ngưỡng thang xám cực đại của hệ thống: $s = (L-1) - r$[cite: 3].

</details>

### Câu 137
Nguồn PDF: trang 19

Khi thực hiện Image subtraction S(x,y) = f(x,y) - g(x,y), kết quả âm được xử lý thế nào?

- A. Giữ nguyên giá trị âm
- B. Clamp về 0 (Max(result, 0))
- C. Lấy giá trị tuyệt đối
- D. Thay thế bằng 255

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Clamp về 0 (Max(result, 0))

**Giải thích:** Trong máy tính, mức xám vật lý không bao giờ tồn tại dưới dạng một số âm[cite: 3]. Khi thực hiện phép Image subtraction từng pixel, sự chênh lệch có thể cho ra kết quả toán học bị âm. Cú pháp xử lý tiêu chuẩn trong lĩnh vực này là kẹp (clamp) các tín hiệu lỗi đó lại thông qua hàm điều kiện $S(x,y) = Max(f(x,y)-g(x,y); 0)$, ép mọi mức âm dội ngược trở lại đáy đen tuyệt đối là 0[cite: 3].

</details>

### Câu 138
Nguồn PDF: trang 19

Image subtraction có thể dùng để làm gì? (Chọn tất cả đúng)

- A. Phát hiện chuyển động
- B. Phát hiện sự khác biệt giữa hai ảnh
- C. Loại bỏ nền
- D. Tăng độ sáng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Phát hiện chuyển động; B. Phát hiện sự khác biệt giữa hai ảnh; C. Loại bỏ nền

**Giải thích:** Toán tử trừ ảnh (Image subtraction) là công cụ khai thác sự thay đổi[cite: 3]. Nó ứng dụng hoàn hảo trong việc kiểm tra lỗi công nghiệp (phát hiện điểm khác biệt giữa vật thật và ảnh mẫu), gỡ bỏ cảnh vật tĩnh (background subtraction) thông qua việc trừ đi ảnh nền gốc, cũng như theo dấu các vật thể di động (phát hiện chuyển động) trong các luồng video[cite: 3],[cite: 8].

</details>

### Câu 139
Nguồn PDF: trang 19

Phép Image addition R(x,y) = f(x,y) + g(x,y) có thể dùng để làm gì?

- A. Phát hiện cạnh
- B. Giảm nhiễu bằng cách trung bình hóa nhiều ảnh
- C. Tạo ảnh nhị phân
- D. Phân vùng ảnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Giảm nhiễu bằng cách trung bình hóa nhiều ảnh

**Giải thích:** Trong mô hình suy hao tín hiệu, một bức ảnh chụp tĩnh luôn đi kèm theo một lượng hạt nhiễu (noise) phân tán có tính ngẫu nhiên và trung bình bằng 0[cite: 3]. Phép toán cộng (Image addition) rồi chia trung bình từ một loạt các khung hình (frames) đứng yên sẽ tận dụng tính chất bù trừ của xác suất để san phẳng và triệt tiêu (lower the noise) lớp nhiễu đó, từ đó trả lại tín hiệu cảnh quang sạch sẽ[cite: 3].

</details>

### Câu 140
Nguồn PDF: trang 20

Gradient magnitude được tính từ Sobel filter theo công thức nào?

- A. |Ix| + |Iy|
- B. sqrt(Ix² + Iy²)
- C. max(|Ix|, |Iy|)
- D. Ix × Iy

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. sqrt(Ix² + Iy²)

**Giải thích:** Bằng cách quét ma trận Sobel, ta trích xuất ra được hai giá trị đại diện cho vector đạo hàm dọc theo trục x ($f_x$) và trục y ($f_y$)[cite: 5]. Magnitude (Độ lớn của gradient) mô phỏng chính xác "độ sắc dốc" của một đường viền trong không gian hình học Euclidean, do đó nó được tính quy chuẩn dựa trên độ dài đường chéo theo định lý Pytago: $|\nabla f(x,y)| = \sqrt{I_x^2 + I_y^2}$[cite: 5].

</details>

### Câu 141
Nguồn PDF: trang 20

Gradient direction (hướng gradient) được tính bằng công thức nào?

- A. atan(Ix/Iy)
- B. atan(Iy/Ix)
- C. sqrt(Ix/Iy)
- D. atan2(Iy, Ix)

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** D. atan2(Iy, Ix)

**Giải thích:** Vector hướng của gradient luôn luôn đâm thẳng 90 độ, vuông góc vuông vức với mặt phẳng của đường viền biên (edge)[cite: 5]. Theo lượng giác, góc định hướng $\theta$ của vector này được giải quyết thông qua tỷ lệ arctangent của các thành phần đạo hàm ($\theta = \tan^{-1}(f_y/f_x)$). Trong lập trình, hàm `atan2(Iy, Ix)` được chuộng dùng hơn để phân biệt trọn vẹn và chuẩn xác góc phủ ở cả 4 cung phần tư (0 đến $360^\circ$)[cite: 5].

</details>

### Câu 142
Nguồn PDF: trang 20

Điều nào đúng về đạo hàm bậc 1 tại biên ảnh?

- A. Bằng 0 tại vị trí biên
- B. Đạt cực trị (không phải 0) tại vị trí biên
- C. Tuyến tính trong vùng ramp
- D. Cả B và C

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** D. Cả B và C

**Giải thích:** Sự biến đổi cường độ mức xám (gradient) hình thành nên một ranh giới biên (edge)[cite: 5]. Tại giai đoạn dốc lên (Ramp region), tỷ lệ biến thiên là đều đặn, khiến đồ thị đạo hàm bậc 1 tạo ra một giá trị khác không và đi theo đường thẳng nằm ngang (tuyến tính)[cite: 5]. Hơn nữa, tại chính xác các điểm uốn chuyển giao (Step changes), tốc độ dốc đạt mức điên cuồng nhất, tạo ra một đỉnh vọt lên cao nhất thể hiện điểm cực đại cường độ cực trị (Strong response)[cite: 5].

</details>

### Câu 143
Nguồn PDF: trang 20

Bộ lọc Prewitt khác Sobel ở điểm nào?

- A. Kích thước kernel khác nhau
- B. Prewitt dùng trung bình đơn giản, Sobel dùng trọng số Gaussian cho hướng ngang
- C. Prewitt phát hiện biên theo hướng dọc, Sobel theo hướng ngang
- D. Prewitt cho kết quả chính xác hơn

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Prewitt dùng trung bình đơn giản, Sobel dùng trọng số Gaussian cho hướng ngang

**Giải thích:** Mặc dù đều chia sẻ chung một kích thước cấu trúc và khả năng đạo hàm cơ sở để tìm biên, điểm mấu chốt tạo ra sức mạnh chống nhiễu vượt trội của Sobel là nó tích hợp bộ làm trơn trung tâm[cite: 5]. Trong khi Prewitt sử dụng cơ chế cào bằng (các số 1 trải đều), Sobel gán trọng số 2 (gấp đôi) vào giữa tâm giống như thuộc tính đỉnh chuông của Gaussian, để tăng cường độ mịn ngang/dọc dọc theo đường viền[cite: 5].

</details>

### Câu 144
Nguồn PDF: trang 20

Kernel nào thực hiện Identity (không thay đổi ảnh)?

- A. [1/9, 1/9, 1/9; 1/9, 1/9, 1/9; 1/9, 1/9, 1/9]
- B. [0, 0, 0; 0, 1, 0; 0, 0, 0]
- C. [0, 1, 0; 1, -4, 1; 0, 1, 0]
- D. [1, 0, -1; 2, 0, -2; 1, 0, -1]

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. [0, 0, 0; 0, 1, 0; 0, 0, 0]

**Giải thích:** Ma trận Identity (không thay đổi ảnh) tuân theo một điều luật cực kỳ đơn thuần: Chỉ sao chép pixel gốc và bỏ qua toàn bộ hoàn cảnh xung quanh[cite: 3]. Do đó, ma trận kernel $3\times3$ này chứa số 1 tại nhân lõi ở chính giữa, và được bao bọc tuyệt đối bởi các giá trị 0 ở vòng lân cận để triệt tiêu mọi phép cộng[cite: 3].

</details>

### Câu 145
Nguồn PDF: trang 20

Điều nào đúng về đạo hàm bậc 2 (Laplacian) tại biên ảnh?

- A. Đạt cực trị tại vị trí biên
- B. Bằng 0 tại vị trí biên (zero-crossing)
- C. Dương ở mọi nơi
- D. Không liên quan đến biên

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Bằng 0 tại vị trí biên (zero-crossing)

**Giải thích:** Dưới ánh sáng của bộ lọc Laplacian, đạo hàm bậc 2 không vọt lên đỉnh mà tập trung vào việc dò tìm điểm đảo chiều[cite: 5]. Ngay tại vị trí giữa tâm (điểm dốc nhất) của sườn đồi mức xám tạo ra một đường biên, gia tốc biến đổi của ánh sáng rơi đột ngột, khiến đồ thị đạo hàm bậc hai bắt buộc phải cắt ngang qua vành đai giá trị 0. Kỹ thuật lần theo các đường đứt gãy này được định danh là Zero-crossing[cite: 5].

</details>

### Câu 146
Nguồn PDF: trang 20

Trong xử lý ảnh, "border handling" (xử lý biên ảnh) khi thực hiện convolution có các phương pháp nào? (Chọn tất cả đúng)

- A. Zero-padding (thêm cột/hàng 0)
- B. Đối xứng gương (mirror)
- C. Replicate (lặp giá trị biên)
- D. Bỏ qua các pixel biên

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Zero-padding (thêm cột/hàng 0); B. Đối xứng gương (mirror); C. Replicate (lặp giá trị biên); D. Bỏ qua các pixel biên

**Giải thích:** Việc mảng mặt nạ kernel vượt ra khỏi phạm vi tọa độ thực của bức ảnh ở sát mép viền sinh ra các điểm khuyết dữ liệu trầm trọng[cite: 3]. Giới khoa học giải quyết lỗ hổng này thông qua nhiều quy ước (Border handling) như: bọc thêm lớp đen số 0 (Zero-padding), phản xạ đối xứng quang học (Mirror/Reflect), kéo dãn lặp lại pixel ranh giới (Replicate), hoặc đơn giản là cắt bỏ và bỏ mặc (Ignore/Crop) phần vành đai gây lỗi[cite: 3].

</details>

### Câu 147
Nguồn PDF: trang 20

Image multiplication S(x,y) = f(x,y) × ratio dùng để làm gì?

- A. Phát hiện cạnh
- B. Tăng tương phản hoặc độ sáng
- C. Lọc nhiễu
- D. Phân vùng ảnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Tăng tương phản hoặc độ sáng

**Giải thích:** Phép nhân một ma trận ảnh với một tham số đại số cố định (factor/ratio) là một công cụ can thiệp mạnh bạo trên toàn dải động của mức xám ($S(x,y) = f(x,y) \times ratio$)[cite: 3]. Nếu hệ số $> 1$, điểm ảnh sẽ được kích sáng, dải phân bố bị giãn ra, mang lại sự thay đổi rõ nét và gia tăng mạnh mẽ (increase) cấp độ sáng chói (luminosity) lẫn mức tương phản (contrast)[cite: 3].

</details>

### Câu 148
Nguồn PDF: trang 21

Bộ lọc nào dùng trong Matlab cho phép correlation (không convolution)?

- A. conv2
- B. filter2
- C. imfilter
- D. fspecial

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. filter2

**Giải thích:** Việc tính toán Tương quan (Correlation) có cấu trúc y hệt Nhân chập (Convolution), điểm duy nhất ngăn cách là có hay không bước lật ngược ma trận kernel $180^\circ$[cite: 3]. Nền tảng phần mềm Matlab định hướng rạch ròi quy ước này: hàm `filter2` được phân bổ để thực thi toán tử Correlation nguyên bản (dùng nhiều trong template matching), trong khi `conv2` mặc định xử lý phép Convolution chuẩn[cite: 3].

</details>

### Câu 149
Nguồn PDF: trang 21

Bộ lọc trung bình có trọng số (weighted mean) có trọng số cao hơn ở vị trí nào?

- A. Các pixel góc
- B. Pixel trung tâm
- C. Phân bố đều
- D. Pixel biên

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Pixel trung tâm

**Giải thích:** Tư duy của bộ lọc trung bình trọng số (weighted mean filter) bác bỏ việc gán giá trị cào bằng (phân bố đều) ở mọi pixel[cite: 3]. Nó tin rằng một pixel càng nằm xa lõi trung tâm thì sự đồng điệu (correlation) với pixel cốt lõi càng nhỏ dần đi. Hệ quả tất yếu là thiết kế ma trận luôn bơm cho pixel trung tâm ở chính giữa khối (center of the mask) những hệ số trọng số cao ngất ngưởng so với các vị trí biên rào ngoài cùng[cite: 3].

</details>

### Câu 150
Nguồn PDF: trang 21

Đặc điểm nào của bộ lọc Gaussian làm nó phù hợp cho việc làm trơn ảnh trước khi phát hiện cạnh?

- A. Nhanh hơn Mean filter
- B. Làm trơn tự nhiên theo phân phối Gaussian, giảm nhiễu mà ít mất chi tiết cạnh
- C. Không thay đổi kích thước ảnh
- D. Có thể phát hiện cạnh trực tiếp

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Làm trơn tự nhiên theo phân phối Gaussian, giảm nhiễu mà ít mất chi tiết cạnh

**Giải thích:** Các mô hình đạo hàm tìm cạnh rất mỏng manh và dễ phát sinh "viền rác" nếu gặp phải tín hiệu nhiễu cực đoan[cite: 5]. Bộ lọc Gaussian được xem là "giải pháp vàng" bảo vệ (tiền xử lý) nhờ trọng số hình chuông thoai thoải[cite: 3],[cite: 5]. Tính chất này cung cấp sự dung hòa tuyệt vời: nó đủ sức nghiền nát nhiễu ngẫu nhiên, mô phỏng sự nhòe của mắt người một cách mềm mại nhưng lại không ăn mòn phá nát các thông tin cấu trúc viền góc như Mean filter[cite: 3],[cite: 5].

</details>

### Câu 151
Nguồn PDF: trang 21

Khi áp dụng Gaussian filter với σ lớn, điều gì xảy ra?

- A. Ảnh ít bị mờ hơn
- B. Ảnh bị mờ nhiều hơn
- C. Cạnh được tăng cường
- D. Nhiễu tăng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Ảnh bị mờ nhiều hơn

**Giải thích:** Đại lượng $\sigma$ (độ lệch chuẩn) kiểm soát biên độ phình ra của đồ thị phân phối năng lượng Gaussian[cite: 3]. Khi ta đẩy $\sigma$ lên một chỉ số rất lớn, bộ lọc vươn rộng xúc tu, pha trộn và nhào lộn giá trị của một quần thể pixel rộng lớn xung quanh điểm lõi. Hệ quả nhãn tiền là diện tích bị trung bình hóa lan quá lớn, khiến toàn bộ bức ảnh bị lu mờ (blur) và mờ nhạt đi một cách nặng nề (mờ nhiều hơn)[cite: 3].

</details>

### Câu 152
Nguồn PDF: trang 21

Histogram matching (histogram specification) là gì?

- A. So sánh hai histogram
- B. Biến đổi histogram ảnh đầu vào để khớp với histogram mục tiêu
- C. Cân bằng histogram tự động
- D. Vẽ histogram của ảnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Biến đổi histogram ảnh đầu vào để khớp với histogram mục tiêu

**Giải thích:** Trong khi Histogram Equalization là một quy trình cứng nhắc ép đồ thị thành một khối phẳng đều vô cảm, thì Histogram Matching (hay còn gọi là Histogram Specification) linh động hơn rất nhiều[cite: 3]. Nó tiếp nhận một biểu đồ mong muốn (desired histogram/target) từ bên ngoài, sau đó tính toán một hàm chuyển tiếp để uốn nắn và gò ép đường bao phân bố điểm ảnh của ảnh đầu vào sao cho khi xuất ra, nó mô phỏng trùng khớp với biểu đồ mục tiêu đã chọn[cite: 3].

</details>

### Câu 153
Nguồn PDF: trang 21

Trong Matlab, hàm nào thực hiện convolution 2D?

- A. filter2
- B. conv2
- C. imfilter
- D. fconv

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. conv2

**Giải thích:** Để phục vụ các hệ thống thị giác máy tính và phân tích tín hiệu trên những mảng ma trận điểm ảnh không gian 2D, bộ engine cốt lõi của Matlab đã cung cấp hàm hàm lệnh (function) mang tên `conv2`[cite: 3]. Lệnh này chuyên trị các tác vụ thực hiện thuật toán tính toán tích chập hai chiều (2D Convolution) một cách toàn diện[cite: 3].

</details>

### Câu 154
Nguồn PDF: trang 21

AND operation trên ảnh nhị phân dùng để làm gì?

- A. Kết hợp thông tin của hai ảnh
- B. Tạo mask để chọn vùng quan tâm
- C. Đảo bit (negate)
- D. Tính độ khác biệt

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Tạo mask để chọn vùng quan tâm

**Giải thích:** Lệnh AND vận hành dưới góc độ mệnh đề giao nhau (chỉ trả về 1 khi cả hai bên đều bằng 1)[cite: 3]. Trong ứng dụng ảnh, khi ta đưa một ảnh nhị phân chập lên một khung hình đầy đủ, những phần màu đen (0) của ảnh nhị phân sẽ tiêu diệt tất cả các điểm ảnh tương ứng, trong khi phần màu trắng (1) sẽ mở cửa "cứu vớt" khu vực đối tượng. Nhờ vậy, toán tử này sinh ra với công dụng rạch ròi để định hình Mặt nạ (And mask), che giấu phần thừa và chọn lọc vùng quan tâm (ROI)[cite: 3].

</details>

### Câu 155
Nguồn PDF: trang 21

OR operation trên hai ảnh nhị phân cho kết quả nào?

- A. Giao (intersection) của hai ảnh
- B. Hợp (union) của hai ảnh
- C. Hiệu của hai ảnh
- D. Tích của hai ảnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Hợp (union) của hai ảnh

**Giải thích:** Trong logic nhị phân, toán tử OR (Hoặc) có chức năng gộp dồn dữ liệu, nó sẽ thắp sáng một điểm thành giá trị 1 miễn là có ít nhất một trong hai ảnh đầu vào mang giá trị 1 tại vị trí đó[cite: 3]. Hiệu ứng tổng hợp này trên hai tấm ảnh mặt nạ phân cực sẽ sinh ra một mặt nạ to lớn hơn, chứa mọi đối tượng có mặt ở ảnh 1 và mọi đối tượng có mặt ở ảnh 2, tương đồng với phép Hợp (Union) trong lý thuyết tập hợp[cite: 3].

</details>

### Câu 156
Nguồn PDF: trang 22

Structuring element trong morphological operations là gì?

- A. Kernel tuyến tính
- B. Mask có hình dạng xác định dùng để quét qua ảnh
- C. Bộ nhớ đệm
- D. Histogram đặc biệt

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Mask có hình dạng xác định dùng để quét qua ảnh

**Giải thích:** Thế giới Xử lý hình thái học (Morphological operations) không dùng thuật ngữ "hạt nhân" (kernel) hay hệ số trọng số tuyến tính, mà thay bằng cấu trúc Phần tử cấu trúc (Structuring element)[cite: 3]. Đây là những khối mặt nạ logic vô hình mang hình hài cụ thể (như khối vuông, thanh dọc, chữ thập, hay đĩa tròn) được máy tính dùng như một khuôn đúc để quét dọc (scan mask) theo từng pixel của bức ảnh và ra quyết định biến đổi theo nguyên tắc giao/hợp[cite: 3].

</details>

### Câu 157
Nguồn PDF: trang 22

Phép Opening (Erosion → Dilation) bảo toàn điều gì?

- A. Các lỗ hổng nhỏ
- B. Hình dạng ban đầu của các đối tượng sau khi loại bỏ chi tiết nhỏ
- C. Tất cả các pixel
- D. Màu sắc của ảnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Hình dạng ban đầu của các đối tượng sau khi loại bỏ chi tiết nhỏ

**Giải thích:** Chuỗi hành động kết hợp của phép Opening bắt đầu bằng một sự thanh lọc tàn bạo: Erosion cào xé toàn bộ các đốm nhiễu, các nhánh mỏng manh cho đến khi chúng bay màu hoàn toàn[cite: 3]. Tuy nhiên, các vùng khối vật thể khổng lồ thì không bị gặm thủng mà chỉ bị gọt viền; để sau đó, cú bồi tiếp theo của Dilation sẽ tái tạo phần viền này, khôi phục lại nguyên trạng (giữ hình dạng ban đầu) cho các khối u lớn đáng giá đó (keep original shape)[cite: 3].

</details>

### Câu 158
Nguồn PDF: trang 22

Phép Closing (Dilation → Erosion) bảo toàn điều gì?

- A. Các đối tượng nhỏ
- B. Hình dạng ban đầu sau khi lấp đầy các lỗ nhỏ
- C. Tất cả các pixel
- D. Histogram gốc

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Hình dạng ban đầu sau khi lấp đầy các lỗ nhỏ

**Giải thích:** Tiến trình Closing khai mào bằng sức ép giãn nở cực mạnh từ Dilation, khiến các mảng màu trắng dâng lên và dập tắt hoàn toàn các lằn nứt, đứt gãy, và những cái lỗ nhỏ (fill holes) cắm bên trong vật thể[cite: 3]. Phép toán ăn mòn Erosion bọc hậu sau đó sẽ gặm sạch phần rìa biên vừa bị phình ra của tổng thể khối lượng, gọt nó về tỷ lệ gần như ban đầu (keep original shape) mà không làm rách lại những cái lỗ đã hàn[cite: 3].

</details>

### Câu 159
Nguồn PDF: trang 22

Trong connected component labeling, vòng lặp đầu tiên qua ảnh làm gì?

- A. Tính toán diện tích từng vùng
- B. Gán nhãn nhỏ nhất từ các hàng xóm trên và trái
- C. Xóa các vùng nhỏ
- D. Tính biên của từng vùng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Gán nhãn nhỏ nhất từ các hàng xóm trên và trái

**Giải thích:** Thuật toán phân vùng liên thông (Connected component labeling) thường triển khai cơ chế làm việc quét tuần tự hai lượt từ góc trên bên trái xuống[cite: 3]. Tại nhịp đập của vòng lặp đầu tiên (First loop), hệ thống chưa thể nắm bắt toàn cảnh bức ảnh, do đó nó thực thi luật "kế thừa ngắn hạn": gán cho pixel hiện tại cái nhãn có ID số nhỏ nhất (smallest label) tìm thấy từ các pixel lân cận đã quét ở bên trái và phía trên nó (top or left neighbors)[cite: 3].

</details>

### Câu 160
Nguồn PDF: trang 22

Adaptive thresholding khác Global thresholding ở điểm nào?

- A. Nhanh hơn
- B. Ngưỡng được tính riêng cho từng vùng nhỏ của ảnh
- C. Cho kết quả ít chính xác hơn
- D. Chỉ áp dụng được cho ảnh màu

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Ngưỡng được tính riêng cho từng vùng nhỏ của ảnh

**Giải thích:** Thuật toán Global Thresholding khá bảo thủ vì nó áp dụng thiết quân luật bằng một hằng số giới hạn duy nhất cho toàn cõi không gian bức ảnh, dễ sụp đổ khi ánh sáng chập chờn[cite: 7]. Adaptive thresholding (Ngưỡng thích nghi) đã lật ngược thế cờ bằng cách băm nát bức ảnh ra thành các khu vực ô vuông nhỏ, đo lường và cấp riêng cho mỗi phân khu một định mức độc lập (its own threshold), chống lại hiện tượng bóng đổ cục bộ một cách tối ưu[cite: 7].

</details>

### Câu 161
Nguồn PDF: trang 22

Khi kích thước filter tăng lên, điều gì xảy ra với ảnh sau lọc?

- A. Ảnh ít bị mờ hơn
- B. Ảnh bị mờ nhiều hơn
- C. Ảnh sắc nét hơn
- D. Không thay đổi

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Ảnh bị mờ nhiều hơn

**Giải thích:** Cơ chế cào bằng và làm mịn của các bộ lọc thông thấp (như Average hay Gaussian) phụ thuộc hoàn toàn vào vùng phủ sóng của mặt nạ[cite: 3]. Bằng cách cưỡng bức kéo giãn kích thước chiều dài cạnh của ô filter (box size), ta đã vô tình đẩy một lượng khổng lồ các pixel lân cận vào chung một rổ để trộn lẫn trung bình, làm nhòe nghiêm trọng sự phân tán cường độ và nhấn chìm ảnh trong trạng thái mờ sương, mất chi tiết (mờ nhiều hơn)[cite: 3].

</details>

### Câu 162
Nguồn PDF: trang 22

Trong xử lý ảnh, phép lọc nào cho kết quả tốt nhất khi loại bỏ nhiễu Gaussian?

- A. Median filter
- B. Max filter
- C. Gaussian filter
- D. Min filter

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** C. Gaussian filter

**Giải thích:** Nhiễu Gaussian bám rễ vào không gian tín hiệu bằng cách thêu dệt các độ lệch cộng dồn xung quanh điểm ảnh tạo nên hình chuông[cite: 3]. Việc dùng các bộ lọc nhặt mảnh như Median filter là quá thô bạo với loại nhiễu rải đều này. Sự lựa chọn hoàn mỹ và phù hợp về mặt cấu trúc toán học nhất chính là dùng một hàm Gaussian (Gaussian filter) khác để tiến hành tích chập, giúp triệt tiêu phương sai rác rưởi một cách mượt mà nhất[cite: 3].

</details>

### Câu 163
Nguồn PDF: trang 23

Loại nhiễu nào đặc trưng bởi các pixel trắng và đen ngẫu nhiên xuất hiện trong ảnh?

- A. Gaussian noise
- B. Salt and pepper noise
- C. Poisson noise
- D. Uniform noise

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Salt and pepper noise

**Giải thích:** Sự xuất hiện đốm bất thình lình của các cực trị biên độ sáng chói (255) và đen kịt (0) xen kẽ rải rác trên bề mặt khung hình là dấu hiệu nhận diện độc quyền của một loại nhiễu do lỗi cảm biến truyền dẫn tín hiệu[cite: 3]. Do tính chất tương phản như vãi hạt gia vị lên bàn ăn, giới chuyên môn đã trìu mến định danh cho hiệu ứng nhiễu xung dị biệt này bằng một thuật ngữ kinh điển: Nhiễu muối tiêu (Salt and pepper noise)[cite: 3].

</details>

### Câu 164
Nguồn PDF: trang 23

Sharpening filter sử dụng Unsharp Masking hoạt động theo nguyên lý nào?

- A. f' = f × (blur mask)
- B. f' = f + k × (f - f_smooth)
- C. f' = f - k × f
- D. f' = k × f_smooth

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. f' = f + k × (f - f_smooth)

**Giải thích:** Kỹ thuật Unsharp Masking khôi phục độ phân giải bằng một cú trick toán học thông minh[cite: 3]. Nó chế tạo ra một mặt nạ tín hiệu thông cao (high-pass signal) bằng cách lấy tín hiệu gốc $f$ bóc tách trừ đi chính phiên bản bị làm nhòe mờ của nó là $f_{smooth}$[cite: 3]. Sau đó, hệ thống bơm lượng viền dư thừa này nhân với một cường độ $k$ nhất định, rồi đắp ngược trở lại vào bức ảnh thô ($f' = f + k \times (f - f_{smooth})$) để tăng cường gờ mép (sharpened)[cite: 3].

</details>

### Câu 165
Nguồn PDF: trang 23

Tại sao cần xử lý biên ảnh (border handling) khi thực hiện convolution?

- A. Để tăng tốc độ tính toán
- B. Vì kernel không thể hoàn toàn chồng lên vùng biên
- C. Để tăng độ chính xác
- D. Để giảm kích thước ảnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Vì kernel không thể hoàn toàn chồng lên vùng biên

**Giải thích:** Cơ chế nhân chập (Convolution) bắt buộc tâm của kernel phải đóng đinh chính giữa từng tọa độ pixel để quét[cite: 3]. Rắc rối sẽ phát sinh ngay lập tức khi kernel dạt về khu vực sát ranh giới ảnh, bởi một nửa thân hình ma trận của nó bị lòi ra ngoài rìa, đâm vào khoảng không vô hình không chứa bất kỳ dữ liệu pixel nào để nhân[cite: 3]. Đây là lý do sống còn buộc ta phải có các thuật toán nội suy hoặc cắt tỉa chắp vá (border handling) để hoàn thiện phép toán[cite: 3].

</details>

### Câu 166
Nguồn PDF: trang 23

Gamma correction trong displays thực hiện điều gì?

- A. Bù cho đặc tính phi tuyến của màn hình
- B. Tăng độ sáng màn hình
- C. Giảm độ phân giải
- D. Thay đổi màu sắc

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Bù cho đặc tính phi tuyến của màn hình

**Giải thích:** Do hạn chế của công nghệ vật lý và thiết bị phần cứng, phản xạ ánh sáng phóng ra trên các màn hình hiển thị (displays, điển hình như bóng đèn hình CRT) không bao giờ diễn ra theo tỷ lệ tuyến tính 1:1 với điện áp được cấp[cite: 3]. Phép hiệu chỉnh Gamma (Gamma correction) thông qua biến đổi hàm lũy thừa Power-Law ra đời như một hệ số tinh chỉnh trung gian, đóng vai trò kéo bù trừ lại các hiện tượng đường cong phi tuyến này để hiển thị chuẩn độ sáng[cite: 3].

</details>

### Câu 167
Nguồn PDF: trang 23

Phép lọc trung bình (Average/Mean) của ảnh g(x,y) = f(x,y) + noise giúp làm gì?

- A. Tăng noise
- B. Giảm noise bằng cách lấy trung bình nhiều observations
- C. Làm sắc nét cạnh
- D. Phát hiện đối tượng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Giảm noise bằng cách lấy trung bình nhiều observations

**Giải thích:** Bất kỳ cảm biến máy ảnh nào cũng ghi nhận tín hiệu thực tế dưới định dạng bị nhiễu: $g(x,y) = f(x,y) + \eta(x,y)$[cite: 3]. Nếu ta cố định máy quay và ghi nhận hàng chục khung hình (observations) của cùng một bối cảnh tĩnh, sau đó tiến hành phép cộng dồn (addition) và chia lấy trung bình (average), các phân phối dương và âm của nhiễu ngẫu nhiên sẽ triệt tiêu dần nhau, giúp làm xẹp đi cường độ nhiễu (lower the noise)[cite: 3].

</details>

### Câu 168
Nguồn PDF: trang 23

Điều nào đúng về phép nhân chập có tính kết hợp?

- A. I * (h + g) = (I * h) + g
- B. I * (h * g) = (I * h) * g
- C. I * h = I + h
- D. Convolution không có tính kết hợp

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. I * (h * g) = (I * h) * g

**Giải thích:** Phép toán nhân chập (Convolution) hoạt động trong một hệ thống bất biến theo thời gian tuyến tính, thừa hưởng một đặc trưng toán học vô cùng giá trị là tính chất kết hợp (associative)[cite: 3]. Định lý này thể hiện ở công thức $I * h * g = I * (h * g)$ hoặc $(I * h) * g$, có nghĩa là bạn hoàn toàn được quyền nhân chập các ma trận kernel ($h$ và $g$) nhỏ với nhau thành một mặt nạ lớn trước khi quét lên bức ảnh gốc $I$ để rút ngắn thời gian[cite: 3].

</details>

### Câu 169
Nguồn PDF: trang 23

Tại sao bộ lọc Median tốt hơn Mean trong việc bảo toàn cạnh?

- A. Vì Median nhanh hơn
- B. Vì Median không tính trung bình mà chọn giá trị có thứ tự giữa, không bị kéo bởi outlier
- C. Vì Median có kích thước nhỏ hơn
- D. Vì Median là bộ lọc tuyến tính

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Vì Median không tính trung bình mà chọn giá trị có thứ tự giữa, không bị kéo bởi outlier

**Giải thích:** Cạnh (edge) là một đường ranh giới nơi cường độ sáng sụp đổ đột ngột. Bộ lọc Mean tính trung bình cộng nên sẽ bóp vụn và hòa tan các điểm ảnh ở mép sườn này lại, gây mờ ảnh hưởng[cite: 3]. Trái lại, Median (trung vị) chỉ sắp xếp đội hình pixel để tìm ra vị trí đứng giữa, khiến nó miễn nhiễm (không bị kéo lùi) trước các giá trị ngoại lai (outlier), qua đó duy trì được sự trong suốt và bảo tồn vẹn nguyên hình khối của các đường nét sắc lẹm[cite: 3].

</details>

### Câu 170
Nguồn PDF: trang 23

Bộ lọc Sobel theo chiều x (Gx) phát hiện loại biên nào?

- A. Biên nằm ngang
- B. Biên nằm dọc
- C. Biên theo đường chéo
- D. Tất cả các loại biên

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Biên nằm dọc

**Giải thích:** Ma trận nhân chập của bộ lọc Sobel theo trục x ($G_x$) được cấu tạo với một cột số âm ở bên trái và cột số dương bên phải (hoặc ngược lại)[cite: 5]. Cấu trúc thiết kế này đảm bảo nó chỉ tính mức độ chênh lệch hiệu số ánh sáng dọc theo phương ngang[cite: 5]. Khi ánh sáng bị cắt ngang đột ngột theo phương x, điều đó báo hiệu sự đứt gãy không gian sinh ra do sự hiện diện của một bờ viền hình trụ thẳng đứng, tức là biên nằm dọc (vertical edge)[cite: 5].

</details>

### Câu 171
Nguồn PDF: trang 24

Local histogram equalization khác Global histogram equalization ở điểm nào?

- A. Local equalize từng pixel riêng lẻ
- B. Local tính toán và áp dụng equalization trong từng vùng nhỏ của ảnh
- C. Local không thay đổi histogram
- D. Local chỉ dùng cho ảnh màu

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Local tính toán và áp dụng equalization trong từng vùng nhỏ của ảnh

**Giải thích:** Global histogram equalization gộp chung 100% tài nguyên dữ liệu điểm ảnh để uốn nắn một lược đồ phân phối duy nhất, đôi khi khiến cho một số tiểu tiết chìm khuất vì nhiễu cục bộ[cite: 3]. Phương pháp Local (cục bộ) chia để trị bằng việc đóng khung thuật toán vào trong những cửa sổ quét siêu nhỏ (ví dụ $7\times7$), tính toán lại CDF và cân bằng độc lập cho từng vùng không gian, giúp "hồi sinh" chi tiết với độ tương phản tuyệt đỉnh tại từng ngóc ngách[cite: 3].

</details>

### Câu 172
Nguồn PDF: trang 24

Inverse Log transformation (s = c × 10^r - c) có tác dụng gì?

- A. Kéo giãn mức xám thấp
- B. Nén mức xám thấp, kéo giãn mức xám cao
- C. Đảo ngược ảnh
- D. Tăng độ tương phản đều

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Nén mức xám thấp, kéo giãn mức xám cao

**Giải thích:** Hàm Logarithm nghịch đảo (Inverse Log/Exponential transformation) có đồ thị cong vút ngược lại với biến đổi Log[cite: 3]. Khi các điểm ảnh đi qua đường hầm tính toán này, sự nhích lên của hàm số diễn ra rất chậm chạp ở dải dưới khiến các điểm ảnh có mức xám cực thấp bị dìm và ép chặt nén lại[cite: 3]. Trong khi đó, phần dải xám phía cao lại được kéo vọt lên để giãn nở mạnh, giúp phân biệt rõ các chi tiết bị chìm trong vùng cường độ sáng[cite: 3].

</details>

### Câu 173
Nguồn PDF: trang 24

Khi áp dụng Erosion với structuring element hình tròn, đối tượng trong ảnh bị ảnh hưởng như thế nào?

- A. Lớn hơn đều theo mọi hướng
- B. Nhỏ hơn đều theo mọi hướng
- C. Chỉ thay đổi theo chiều ngang
- D. Không thay đổi

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Nhỏ hơn đều theo mọi hướng

**Giải thích:** Bản năng của toán tử Erosion (Ăn mòn) là gặm mòn lớp vỏ ngoài biên giới của phần foreground (đối tượng) trên mặt phẳng 2D[cite: 3]. Cấu trúc của một hình tròn mang tính đối xứng tỏa tròn đẳng hướng, do đó, khi dùng nó làm lưỡi dao quét qua vật thể, toàn bộ chu vi đường biên xung quanh sẽ bị bào gọt với tỷ lệ như nhau, làm cho kích thước của đối tượng đồng loạt nhỏ hơn đều theo mọi phía (shrink uniformly)[cite: 3].

</details>

### Câu 174
Nguồn PDF: trang 24

Kết quả của Dilation với structuring element hình vuông 3×3 trên pixel đơn là gì?

- A. Pixel đơn đó biến mất
- B. Pixel đơn biến thành một hình vuông 3×3
- C. Pixel đơn giữ nguyên
- D. Pixel đơn nhân đôi

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Pixel đơn biến thành một hình vuông 3×3

**Giải thích:** Theo lý thuyết không gian của phép toán Dilation (Giãn nở), mỗi khi cái tâm của phần tử cấu trúc (structuring element) đè trúng một pixel đang "sống" (giá trị 1) trên ảnh gốc, toàn bộ cái khuôn của phần tử đó sẽ được chép và dập in vào ảnh kết quả[cite: 3]. Vậy nên, nếu ta thả một ma trận phần tử có dạng hình vuông $3\times3$ lên một điểm pixel trắng bé tẹo duy nhất, nó sẽ ngay lập tức lan tỏa nở rộ và hóa thành một khối hình vuông $3\times3$ khổng lồ[cite: 3].

</details>

### Câu 175
Nguồn PDF: trang 24

Trong thực tế, phương pháp nào phổ biến để áp dụng Laplacian filter mà không bị ảnh hưởng bởi nhiễu?

- A. Áp dụng trực tiếp Laplacian
- B. LoG (Laplacian of Gaussian): làm mờ Gaussian trước rồi mới áp dụng Laplacian
- C. Áp dụng Sobel trước
- D. Chỉ áp dụng Gaussian

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. LoG (Laplacian of Gaussian): làm mờ Gaussian trước rồi mới áp dụng Laplacian

**Giải thích:** Do bản chất là một phép lấy đạo hàm bậc 2 tính gia tốc, Laplacian cực kỳ hung hãn trong việc phát giác các điểm tần số cao, dẫn đến kết cục bị các hạt nhiễu (noise) xé toạc ra nhiều tín hiệu giả[cite: 5]. Cách duy nhất để sử dụng nó trong thế giới thực là bọc nó lại bằng một lớp đệm tiền xử lý Gaussian (làm mờ và xẹp nhiễu). Sự kết hợp thông minh này sinh ra mặt nạ kinh điển Laplacian of Gaussian (LoG), dò cạnh không độ ồn[cite: 5].

</details>

### Câu 176
Nguồn PDF: trang 24

Phép threshold tạo ra ảnh nhị phân theo quy tắc nào?

- A. Pixel > threshold → 0, ngược lại → 1
- B. Pixel >= threshold → 1, ngược lại → 0 (hoặc ngược lại tùy định nghĩa foreground)
- C. Pixel = threshold → 1, còn lại → 0
- D. Không có quy tắc cố định

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Pixel >= threshold → 1, ngược lại → 0 (hoặc ngược lại tùy định nghĩa foreground)

**Giải thích:** Chức năng trọng tâm của Phân ngưỡng (Thresholding) là cưa đôi thế giới của mức xám làm hai nửa rạch ròi bằng một bức tường ngưỡng (Threshold value $T$)[cite: 3],[cite: 7]. Nó hành động dựa trên quy tắc toán học đơn giản: bất kỳ pixel nào mạnh hơn (có cường độ $\ge T$) sẽ được đôn lên mốc vinh quang 1 (màu trắng - foreground), còn phần yếu thế ($< T$) sẽ bị nhấn chìm xuống 0 (màu đen - background)[cite: 7]. (Cũng có thể gán ngược lại nếu yêu cầu làm nổi bật màu tối).

</details>

### Câu 177
Nguồn PDF: trang 24

Ứng dụng nào của Image subtraction trong thực tế?

- A. Tăng độ phân giải ảnh
- B. Background subtraction để phát hiện chuyển động trong video
- C. Cân bằng màu sắc
- D. Loại bỏ nhiễu Gaussian

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Background subtraction để phát hiện chuyển động trong video

**Giải thích:** Việc đặt hai bức ảnh lên nhau và trừ đi các giá trị pixel (Image subtraction) sẽ "tàng hình" tất cả những cảnh vật đứng yên do hiệu số của chúng bằng 0[cite: 3],[cite: 8]. Trong thực tiễn phân tích chuỗi video (camera an ninh, giám sát), kỹ thuật trừ ảnh nền (background subtraction) được sử dụng để triệt tiêu tĩnh vật xung quanh, làm nổi lên các bóng ma tín hiệu (silhouette) của những đối tượng xâm nhập hay phương tiện đang chuyển động (detect motion)[cite: 8].

</details>

### Câu 178
Nguồn PDF: trang 25

Tại sao cần dùng LoG (Laplacian of Gaussian) thay vì chỉ dùng Laplacian?

- A. Vì Laplacian không tìm được biên
- B. Vì Laplacian rất nhạy với nhiễu; LoG làm mờ trước để giảm nhiễu
- C. Vì LoG nhanh hơn
- D. Vì Laplacian chỉ hoạt động trong miền tần số

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Vì Laplacian rất nhạy với nhiễu; LoG làm mờ trước để giảm nhiễu

**Giải thích:** Bộ lọc đạo hàm bậc hai Laplacian phô diễn năng lực kinh ngạc trong việc khoanh vùng chính xác điểm uốn của biên, nhưng rào cản chí mạng là nó quá mong manh và phản ứng mất kiểm soát (rất nhạy) với các hạt nhiễu[cite: 5]. Thuật toán LoG (Laplacian of Gaussian) đã chắp vá được yếu điểm này nhờ áp dụng phép làm trơn hình chuông (Gaussian Blur) lên ảnh để khóa chặt nhiễu trước khi Laplacian tiến hành khai phá đường biên[cite: 5].

</details>

### Câu 179
Nguồn PDF: trang 25

Điều nào đúng về kernel của bộ lọc Laplacian?

- A. Tổng các hệ số = 1
- B. Tổng các hệ số = 0
- C. Tổng các hệ số > 0
- D. Không xác định được tổng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Tổng các hệ số = 0

**Giải thích:** Một đặc trưng cơ hữu phải có đối với mọi bộ lọc đạo hàm vi phân (đặc biệt là Laplacian dò mốc zero-crossing) là chúng không được có phản ứng với những vùng bề mặt ảnh tĩnh lặng, màu mè trơn tru không thay đổi (flat region)[cite: 5]. Yêu cầu thiết kế khắt khe này ép buộc rằng tổng đại số của mọi con số trên ma trận kernel Laplacian luôn luôn phải cân bằng triệt để và bị triệt tiêu về đúng số 0[cite: 5].

</details>

### Câu 180
Nguồn PDF: trang 25

Khi Piecewise-linear transformation có s1=0, s2=L-1 với r1=r2=m (m là mean), nó trở thành phép gì?

- A. Linear stretching
- B. Thresholding
- C. Gamma correction
- D. Histogram equalization

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Thresholding

**Giải thích:** Cấu hình tham số của biến đổi tuyến tính theo đoạn (Piecewise-linear) chứa đựng một biến thể cực đoan[cite: 3]. Bằng cách chập hai mốc cắt $r_1$ và $r_2$ lại thành một điểm duy nhất (giá trị $m$), đồng thời kéo dãn khoảng biên độ mức sáng ra hai thái cực trắng/đen ($s_1=0$ và $s_2=L-1$), đường đồ thị sẽ hóa thành một bờ vực thẳng đứng[cite: 3]. Tại ranh giới này, chức năng đã thoái hóa hoàn toàn và trở thành hàm phân ngưỡng (Thresholding)[cite: 3].

</details>

### Câu 181
Nguồn PDF: trang 25

Tại sao Image addition của nhiều ảnh cùng cảnh giúp giảm nhiễu?

- A. Vì tổng các ảnh lớn hơn
- B. Vì signal cộng lại trong khi noise (random) bị trung bình hóa về 0
- C. Vì kích thước ảnh tăng lên
- D. Vì màu sắc trở nên đậm hơn

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Vì signal cộng lại trong khi noise (random) bị trung bình hóa về 0

**Giải thích:** Máy móc coi một bức ảnh thu nhận là tổng hòa của cảnh vật thực tế mang tính xác định (signal) và lượng nhiễu mang tính ngẫu nhiên bất định[cite: 3]. Bằng cách cộng dồn (Image addition) hàng loạt các bức ảnh chụp lặp lại của cùng một vị trí rồi lấy tỷ lệ trung bình, tín hiệu thực sẽ được cộng gộp tuyến tính và củng cố vững chắc, trong khi hạt nhiễu (noise) lộn xộn sẽ bù trừ âm/dương cho nhau và cạn kiệt dạt về số 0[cite: 3].

</details>

### Câu 182
Nguồn PDF: trang 25

Structuring element dạng "que" (elongated) dùng trong Morphology dùng để làm gì?

- A. Phát hiện điểm
- B. Phát hiện đường thẳng theo hướng cụ thể
- C. Làm trơn ảnh
- D. Phân vùng màu

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Phát hiện đường thẳng theo hướng cụ thể

**Giải thích:** Hiệu quả của phép toán hình thái học (Morphology) được quyết định hoàn toàn bởi kiến trúc hình dáng của cái rập (Structuring element - phần tử cấu trúc)[cite: 3]. Bằng cách rèn đúc một phần tử có ngoại hình dẹp và dài ra như hình một cái "que" (elongated) đặt theo một góc nghiêng nào đó, ta tạo ra một công cụ cực kỳ tinh vi giúp định vị và phát hiện (trích xuất) những mảng vật thể hay đường chỉ có quỹ đạo kéo dài trùng với hướng đó[cite: 3].

</details>

### Câu 183
Nguồn PDF: trang 25

Sau khi Erosion, các đối tượng nào biến mất?

- A. Đối tượng lớn hơn structuring element
- B. Đối tượng nhỏ hơn structuring element
- C. Tất cả đối tượng
- D. Không đối tượng nào

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Đối tượng nhỏ hơn structuring element

**Giải thích:** Bộ lọc ăn mòn (Erosion) quét đi các phần da thịt ngoại biên của hình dáng vật thể[cite: 3]. Bởi thuật toán này chỉ cho phép khối pixel sống sót nếu bộ rập mặt nạ (structuring element) có thể nằm lọt thỏm hoàn toàn bên trong nó; hệ lụy đau đớn là tất cả những cấu trúc lấm tấm, hoặc các đối tượng (như rác) sở hữu diện tích nhỏ hơn và hẹp hơn vùng giới hạn của phần tử cấu trúc đó sẽ bị gọt đẽo đến mức tan biến không còn một dấu vết[cite: 3].

</details>

### Câu 184
Nguồn PDF: trang 25

Công thức Dilation là gì?

- A. A ⊕ S: tập hợp tất cả các điểm mà khi đặt S vào, không phần nào của S thuộc A
- B. A ⊕ S: tập hợp tất cả tâm của S mà khi đặt S, có ít nhất 1 pixel của S gặp A
- C. A ⊕ S = A ∩ S
- D. A ⊕ S = A ∪ S chuyển dịch

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. A ⊕ S: tập hợp tất cả tâm của S mà khi đặt S, có ít nhất 1 pixel của S gặp A

**Giải thích:** Toán tử giãn nở hình học (Dilation), được thể hiện qua ký hiệu biểu tượng $A \oplus S$, mang một luật chơi mang tính xâm lấn[cite: 3]. Khi ta cầm bộ khuôn của phần tử cấu trúc $S$ rà trên bức ảnh, miễn là có bất kỳ một pixel móng chân nào của $S$ khẽ chạm vào (giao cắt khác rỗng) các pixel thuộc về khối ảnh gốc $A$, thì ngay lập tức điểm tâm của khuôn $S$ đó sẽ được đóng đinh và thuộc về biên chế của đối tượng[cite: 3].

</details>

### Câu 185
Nguồn PDF: trang 25

Erosion được định nghĩa là gì?

- A. A ⊝ S: tập hợp tất cả tâm của S mà khi đặt S, ít nhất 1 pixel của S gặp A
- B. A ⊝ S: tập hợp tất cả tâm của S mà khi đặt S, toàn bộ S thuộc A
- C. Giao điểm của A và S
- D. Hợp điểm của A và S

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. A ⊝ S: tập hợp tất cả tâm của S mà khi đặt S, toàn bộ S thuộc A

**Giải thích:** Ngược dòng với sự bành trướng của giãn nở, phép ăn mòn (Erosion, $A \ominus S$) vận hành theo tư duy thu hẹp nghiêm ngặt[cite: 3]. Thuật toán bắt buộc phải xét vị trí trung tâm của phần tử hình thái $S$. Pixel trung tâm này chỉ được cấp "visa" để bám trụ lại trên tấm ảnh thu được cuối cùng nếu và chỉ nếu, khi đặt tại tọa độ đó, 100% vóc dáng của $S$ bị bao phủ và nằm trọn vẹn ở bên trong lãnh thổ của các pixel vật thể $A$[cite: 3].

</details>

### Câu 186
Nguồn PDF: trang 26

Điều nào đúng về Gaussian filter và Sobel filter?

- A. Cả hai đều là low-pass filter
- B. Gaussian là low-pass, Sobel tính gradient (high-pass cho một hướng)
- C. Cả hai đều phát hiện cạnh
- D. Sobel là low-pass, Gaussian là high-pass

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Gaussian là low-pass, Sobel tính gradient (high-pass cho một hướng)

**Giải thích:** Hai bộ lọc này thực thi các sứ mệnh ngược chiều nhau trong vũ trụ tần số[cite: 3],[cite: 5]. Bộ lọc Gaussian hoạt động như một cỗ máy nghiền tần số cao (low-pass filter) bằng cách lấy trung bình có trọng số, giúp tản mát sự nhiễu loạn[cite: 3]. Trong khi đó, hạt nhân Sobel lại là vũ khí khai thác sự thay đổi đột biến (gradient) để phác họa biên, tức là nó đang đảm trách công việc lọc thông cao (high-pass filter) ưu tiên phát hiện sự biến thiên mạnh mẽ của một trục[cite: 5].

</details>

### Câu 187
Nguồn PDF: trang 26

Khi kích thước kernel của Mean filter tăng, ảnh bị ảnh hưởng thế nào?

- A. Ảnh sắc nét hơn
- B. Ảnh mờ hơn, mất chi tiết nhiều hơn
- C. Nhiễu tăng
- D. Không thay đổi

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Ảnh mờ hơn, mất chi tiết nhiều hơn

**Giải thích:** Tác động của bộ lọc trung bình (Mean filter) là xoa dịu đi các đỉnh nhọn bằng cách dàn đều (lấy trung bình cộng) cường độ pixel xung quanh[cite: 3]. Khi ta đẩy kích thước của mảng ma trận kernel phình to ra, diện tích tham chiếu để chia trung bình càng bành trướng, khiến nhiều cấu trúc không liên quan bị nhào trộn chung, dẫn đến hậu quả là bức ảnh bị kéo xuống bùn mờ sương (blur) và mất tiêu các chi tiết sắc sảo vốn có[cite: 3].

</details>

### Câu 188
Nguồn PDF: trang 26

Điều nào KHÔNG đúng về histogram equalization?

- A. Không có tham số cần chỉnh
- B. Luôn cải thiện chất lượng ảnh trong mọi trường hợp
- C. Hướng đến phân phối đều
- D. Không thể áp dụng trực tiếp trên 3 kênh RGB

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Luôn cải thiện chất lượng ảnh trong mọi trường hợp

**Giải thích:** Cân bằng Histogram (Histogram Equalization) dàn phân phối đều trên dải mức xám một cách tự động và cứng nhắc mà không có sự linh hoạt phân khu[cite: 3]. Phép biến đổi vô tri này sẽ dẫn đến những thất bại bi thảm (không phải lúc nào cũng tốt), ví dụ như khuếch đại vô tội vạ các điểm nhiễu (noise) yếu ớt ở vùng nền tối thành các hạt sáng chói, bóp méo hình ảnh thay vì cải thiện nó trong một số trường hợp thực tế[cite: 3].

</details>

### Câu 189
Nguồn PDF: trang 26

Tại sao Gaussian filter được ưu tiên hơn Mean filter trong nhiều ứng dụng?

- A. Gaussian nhanh hơn
- B. Gaussian mô phỏng cách mắt người mờ ảnh tự nhiên, giảm hiệu ứng blocky
- C. Gaussian dễ cài đặt hơn
- D. Gaussian ít tốn bộ nhớ hơn

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Gaussian mô phỏng cách mắt người mờ ảnh tự nhiên, giảm hiệu ứng blocky

**Giải thích:** Cả hai đều thuộc họ bộ lọc làm trơn, nhưng phân phối trọng số của Gaussian tụt dần về 0 theo hình chuông, tạo ra một ranh giới mượt mà hòa quyện[cite: 3]. Sự mềm mại này phản chiếu chính xác cấu trúc thấu kính quang học làm nhòe hình ảnh của con mắt sinh học, qua đó Gaussian filter khắc phục hoàn toàn hiện tượng tạo hình cắt lớp ô vuông thô cứng (hiệu ứng blocky) thường thấy ở cách lấy trung bình phẳng lì của Mean filter[cite: 3].

</details>

### Câu 190
Nguồn PDF: trang 26

OR operation trên hai ảnh nhị phân A và B có thể dùng để làm gì?

- A. Loại bỏ vùng chung giữa A và B
- B. Kết hợp (hợp) hai ảnh, giữ lại pixel thuộc A hoặc B
- C. Chỉ giữ pixel thuộc cả A lẫn B
- D. Đảo ngược ảnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Kết hợp (hợp) hai ảnh, giữ lại pixel thuộc A hoặc B

**Giải thích:** Theo lý thuyết cơ sở đại số Boole, thao tác toán học logic OR (Hoặc) giữa hai tập hợp pixel sẽ đóng vai trò như một bộ cộng dồn thông tin[cite: 3]. Nếu áp nó vào hệ hai bức ảnh nhị phân A và B, nó sẽ chưng cất và hợp nhất lại (phép Hợp/Union), nghĩa là thắp sáng bất kỳ một tọa độ pixel nào miến là nó thuộc vùng chứa của vật thể trên ảnh A, hay trên ảnh B, hoặc nằm ở phần giao lấp[cite: 3].

</details>

### Câu 191
Nguồn PDF: trang 26

Khi áp dụng Min filter 3×3, giá trị mới của pixel trung tâm được tính là?

- A. Trung bình của cửa sổ 3×3
- B. Giá trị nhỏ nhất trong cửa sổ 3×3
- C. Giá trị trung vị của cửa sổ 3×3
- D. Giá trị lớn nhất trong cửa sổ 3×3

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Giá trị nhỏ nhất trong cửa sổ 3×3

**Giải thích:** Bộ lọc cực tiểu (Min filter) vận hành theo cơ chế phân tích lựa chọn giá trị thay vì các phép cộng nhân tuyến tính[cite: 3]. Khi một vùng không gian ma trận (ví dụ cửa sổ $3\times3$) được chỉ định để lọc, thuật toán sẽ sàng lọc qua toàn bộ 9 điểm ảnh hiện tại, rút ra giá trị mang mức xám tăm tối nhất (giá trị nhỏ nhất/cực tiểu) để chèn lại vào tọa độ của pixel đang chiếm giữ vị trí cốt lõi (trung tâm)[cite: 3].

</details>

### Câu 192
Nguồn PDF: trang 26

Phép Dilation có thể ứng dụng trong thực tế để làm gì? (Chọn đúng nhất)

- A. Loại bỏ đối tượng nhỏ
- B. Kết nối các đường đứt, lấp đầy lỗ hổng
- C. Phát hiện biên
- D. Nén ảnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Kết nối các đường đứt, lấp đầy lỗ hổng

**Giải thích:** Bằng cách áp sát và chèn thêm lớp vỏ ngoài (khi tâm quét đụng phải mép viền), Phép toán Giãn nở (Dilation) đã phóng đại mạnh mẽ hình chiếu biên cương của đối tượng ra các khu vực lân cận[cite: 3]. Nhờ sự phình to này, không chỉ các nét vẽ đứt khúc được vá dính lại với nhau, mà vô số những khe rãnh nhỏ bé bị kẹt trong thân vật thể cũng bị lấn lướt và lấp đầy một cách hoàn hảo[cite: 3].

</details>

### Câu 193
Nguồn PDF: trang 27

Khi chuyển ảnh grayscale sang ảnh nhị phân bằng ngưỡng T, pixel nào được gán foreground?

- A. f(x,y) < T
- B. f(x,y) >= T (hoặc > T tùy định nghĩa)
- C. f(x,y) = T
- D. f(x,y) ≤ T

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. f(x,y) >= T (hoặc > T tùy định nghĩa)

**Giải thích:** Các thuật toán phân tách nhị phân (Thresholding) chẻ bức ảnh ra theo cấu trúc phân ranh bằng cách thiết lập một hàng rào tham chiếu gọi là Threshold ($T$)[cite: 3]. Mọi pixel $f(x,y)$ nào có sức mạnh cường độ sáng vượt trên (hoặc chạm tới, $\ge T$) hàng rào này sẽ lọt qua cánh cửa kiểm duyệt để được gán biến thành phần cốt lõi (foreground, giá trị 1), những kẻ yếu hơn sẽ bị loại bỏ thành phông nền (background, 0)[cite: 3],[cite: 7].

</details>

### Câu 194
Nguồn PDF: trang 27

Điều nào đúng về kỹ thuật Histogram Matching (Specification)?

- A. Chỉ dùng được khi có 2 ảnh giống nhau
- B. Biến đổi histogram ảnh nguồn để giống histogram mục tiêu cho trước
- C. Luôn cho kết quả tốt hơn Histogram Equalization
- D. Không có tham số đầu vào

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Biến đổi histogram ảnh nguồn để giống histogram mục tiêu cho trước

**Giải thích:** Kỹ thuật Histogram Matching (hay còn được biết dưới cái tên Histogram Specification) là phiên bản có định hướng của cân bằng histogram[cite: 3]. Nó sử dụng một quy trình nội suy phức tạp nhằm ánh xạ và bóp méo đường nét phân phối mức xám của bức ảnh đầu vào, cố gắng lái kết quả đó áp sát và hòa hợp hoàn hảo với một đồ thị histogram cụ thể (mục tiêu - target) đã được khai báo trước[cite: 3].

</details>

### Câu 195
Nguồn PDF: trang 27

Điều nào là đặc điểm của bộ lọc làm trơn ảnh (smoothing filter)? (Chọn tất cả đúng)

- A. Còn gọi là low-pass filter
- B. Giảm nhiễu trong ảnh
- C. Làm mờ các cạnh sắc
- D. Tổng hệ số kernel = 1

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Còn gọi là low-pass filter; B. Giảm nhiễu trong ảnh; C. Làm mờ các cạnh sắc; D. Tổng hệ số kernel = 1

**Giải thích:** Các thuật toán làm trơn ảnh (smoothing filter) như Mean và Gaussian đều có khả năng kìm hãm và chặn lại các biến đổi chênh lệch đột ngột, nên chúng thuộc họ bộ lọc thông thấp (low-pass filter)[cite: 3]. Chúng xuất sắc trong việc vò nát các điểm nhiễu lấm tấm (giảm nhiễu) nhưng hệ lụy là cũng làm xẹp luôn chi tiết đường biên (mờ các cạnh)[cite: 3]. Đồng thời, tổng các hệ số nhân của ma trận bắt buộc phải bằng 1 để bảo toàn dòng năng lượng ánh sáng[cite: 3].

</details>


## CHƯƠNG 3.2: Biến đổi ảnh - Miền tần số

### Câu 196
Nguồn PDF: trang 27

Ý tưởng cơ bản của Fourier Transform là gì?

- A. Biến đổi ảnh sang không gian màu khác
- B. Bất kỳ hàm nào đều có thể biểu diễn như tổng có trọng số của các sin/cos tần số khác nhau
- C. Nén dữ liệu ảnh
- D. Phát hiện cạnh ảnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Bất kỳ hàm nào đều có thể biểu diễn như tổng có trọng số của các sin/cos tần số khác nhau

**Giải thích:** Ý tưởng cốt lõi của Biến đổi Fourier dựa trên Chuỗi Fourier, cho rằng bất kỳ hàm số hoặc tín hiệu nào (bao gồm cả ảnh) đều có thể được phân rã và biểu diễn lại dưới dạng một tổng có trọng số của các hàm lượng giác cơ bản là sine và cosine ở nhiều tần số khác nhau[cite: 5].

</details>

### Câu 197
Nguồn PDF: trang 27

Joseph Fourier đề xuất ý tưởng Fourier Series vào năm nào?

- A. 1750
- B. 1807
- C. 1850
- D. 1900

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. 1807

**Giải thích:** Nhà toán học người Pháp Jean Baptiste Joseph Fourier đã đưa ra một ý tưởng mang tính đột phá (a bold idea) về chuỗi Fourier vào năm 1807[cite: 5].

</details>

### Câu 198
Nguồn PDF: trang 27

Trong ảnh số, tần số cao (high frequency) tương ứng với vùng nào?

- A. Vùng đồng nhất, thay đổi chậm
- B. Cạnh, nhiễu, chi tiết sắc nét có sự thay đổi đột ngột
- C. Nền của ảnh
- D. Vùng màu tối

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Cạnh, nhiễu, chi tiết sắc nét có sự thay đổi đột ngột

**Giải thích:** Trong miền không gian của ảnh số, tần số thể hiện mức độ thay đổi của cường độ sáng[cite: 5]. Các thành phần tần số cao (high frequency) đặc trưng cho những sự biến thiên nhanh và đột ngột, tương ứng trực tiếp với các đường cạnh, chi tiết sắc nét và các hạt nhiễu (noise) trên hình ảnh[cite: 5].

</details>

### Câu 199
Nguồn PDF: trang 27

Low frequency trong ảnh tương ứng với điều gì?

- A. Biên và chi tiết sắc nét
- B. Vùng đồng nhất, thay đổi chậm, màu sắc cơ bản
- C. Nhiễu
- D. Các điểm cô lập

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Vùng đồng nhất, thay đổi chậm, màu sắc cơ bản

**Giải thích:** Ngược lại với tần số cao, các thành phần tần số thấp (low frequency) đại diện cho những khu vực mà cường độ ánh sáng biến đổi rất chậm rãi và mượt mà[cite: 5]. Trong thực tế ảnh chụp, chúng phản ánh các vùng nền đồng nhất, bị mờ (blur), hoặc các mảng màu sắc cơ bản trải rộng[cite: 5].

</details>

### Câu 200
Nguồn PDF: trang 28

Trong phổ Fourier (Fourier spectrum), phần lớn năng lượng của ảnh tự nhiên nằm ở đâu?

- A. Tần số cao
- B. Tần số thấp
- C. Phân bố đều
- D. Tần số trung bình

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Tần số thấp

**Giải thích:** Đối với một bức ảnh tự nhiên thông thường (natural image), phần lớn các vùng trên ảnh là các mặt phẳng mượt mà có ít sự thay đổi sáng tối gắt gao[cite: 5]. Do đó, khi biểu diễn dưới dạng phổ Fourier, cấu trúc năng lượng của ảnh sẽ hội tụ và tập trung dày đặc nhất ở khu vực tần số thấp nằm ngay trung tâm phổ[cite: 5].

</details>

### Câu 201
Nguồn PDF: trang 28

Convolution Theorem phát biểu điều gì?

- A. Convolution trong miền không gian tương đương phép nhân trong miền tần số
- B. Convolution trong miền tần số tương đương phép nhân trong miền không gian
- C. Convolution và phép nhân là như nhau
- D. Convolution không thể thực hiện trong miền tần số

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Convolution trong miền không gian tương đương phép nhân trong miền tần số

**Giải thích:** Định lý Convolution (Tích chập) cung cấp một cầu nối toán học quan trọng giữa miền không gian và miền tần số[cite: 5]. Nó khẳng định rằng phép toán tính tích chập (convolution, ký hiệu *) phức tạp giữa một bức ảnh và một bộ lọc trong không gian 2D, hoàn toàn có thể được thay thế tương đương bằng một phép nhân điểm (point multiplication, ký hiệu $\cdot$) đơn giản giữa hai ma trận phổ Fourier của chúng trong miền tần số ($G(u,v) = F(u,v) \cdot H(u,v)$)[cite: 5].

</details>

### Câu 202
Nguồn PDF: trang 28

FFT (Fast Fourier Transform) có ưu điểm gì so với DFT thông thường?

- A. Cho kết quả chính xác hơn
- B. Tính toán nhanh hơn nhiều (O(N log N) thay vì O(N²))
- C. Hoạt động với ảnh màu trực tiếp
- D. Không cần bộ nhớ

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Tính toán nhanh hơn nhiều (O(N log N) thay vì O(N²))

**Giải thích:** Fast Fourier Transform (FFT) là một thuật toán tối ưu hóa của Discrete Fourier Transform (DFT)[cite: 5]. Thuật toán gốc DFT có độ phức tạp tính toán đa thức tỷ lệ với $O(N^2)$, gây cản trở rất lớn về mặt thời gian, trong khi FFT giảm mạnh chi phí toán học xuống mức logarithm $O(N \log N)$, biến quá trình chuyển đổi phổ trở nên đủ nhanh cho các ứng dụng thực tế[cite: 5].

</details>

### Câu 203
Nguồn PDF: trang 28

Bộ lọc Low-pass trong miền tần số làm gì với ảnh?

- A. Giữ lại tần số cao, loại bỏ tần số thấp
- B. Giữ lại tần số thấp, loại bỏ tần số cao → làm mờ ảnh
- C. Khuếch đại tất cả tần số
- D. Không thay đổi ảnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Giữ lại tần số thấp, loại bỏ tần số cao → làm mờ ảnh

**Giải thích:** Bộ lọc thông thấp (Low-pass filter) hoạt động như một cái phễu chặn dải tần[cite: 5]. Nó cho phép các dữ liệu chứa tần số thấp (màu sắc mảng lớn, mượt mà) đi qua và loại bỏ đi toàn bộ các tín hiệu tần số cao (chứa thông tin nhiễu hoặc đường nét cắt ngang gắt gao)[cite: 5]. Kết quả của sự thiếu hụt chi tiết này là bức ảnh được làm trơn và trở nên mờ (blurring) đi[cite: 5].

</details>

### Câu 204
Nguồn PDF: trang 28

Bộ lọc High-pass trong miền tần số có tác dụng gì?

- A. Làm mờ ảnh
- B. Giữ lại tần số cao → làm sắc nét cạnh, tăng chi tiết
- C. Không thay đổi ảnh
- D. Giảm tất cả tần số

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Giữ lại tần số cao → làm sắc nét cạnh, tăng chi tiết

**Giải thích:** Bộ lọc thông cao (High-pass filter) hành xử đối lập hoàn toàn với lọc thông thấp[cite: 5]. Bằng cách chặn lại các năng lượng tần số thấp (phẳng, đồng nhất) và chỉ giữ lại những dao động tần số cao, bộ lọc này trích xuất ra các thành phần thay đổi cường độ nhanh, từ đó cô lập và làm sắc nét (sharpening) các cấu trúc biên viền (edge) cũng như chi tiết cực nhỏ trên hình ảnh[cite: 5].

</details>

### Câu 205
Nguồn PDF: trang 28

Trong Fourier Transform 2D, kết quả F(u,v) lưu trữ những thông tin nào?

- A. Chỉ biên độ
- B. Biên độ (magnitude) và pha (phase)
- C. Chỉ pha
- D. Chỉ tần số

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Biên độ (magnitude) và pha (phase)

**Giải thích:** Kết quả của phép biến đổi Fourier là một hàm ma trận số phức $F(u,v) = R(u,v) + iI(u,v)$[cite: 5]. Trong xử lý ảnh, hàm số phức này được phân tách và lưu trữ để diễn giải thành hai thành phần thông tin mang ý nghĩa vật lý cốt lõi: Biên độ (Magnitude, độ dài vector) và Góc pha (Phase, góc của vector)[cite: 5].

</details>

### Câu 206
Nguồn PDF: trang 28

Phase trong Fourier Transform ảnh chứa thông tin gì?

- A. Thông tin về tần số
- B. Thông tin vị trí không gian (gián tiếp)
- C. Thông tin màu sắc
- D. Thông tin về độ sáng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Thông tin vị trí không gian (gián tiếp)

**Giải thích:** Góc pha (Phase) trong miền Fourier đóng vai trò mã hóa sự phân bố và cấu trúc sắp xếp[cite: 5]. Nếu biên độ cho biết sức mạnh của một sóng, thì góc pha lưu giữ thông tin gián tiếp về tọa độ vị trí không gian (spatial information) của các chi tiết đó trên bức ảnh, và có vai trò quyết định trong việc bảo toàn hình dạng khi phục dựng lại ảnh[cite: 5].

</details>

### Câu 207
Nguồn PDF: trang 28

Magnitude (biên độ) trong Fourier spectrum |F(u,v)| cho biết gì?

- A. Vị trí của các feature trong ảnh
- B. Mức độ đóng góp của mỗi tần số trong ảnh
- C. Màu sắc tại từng điểm
- D. Thông tin về nhiễu

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Mức độ đóng góp của mỗi tần số trong ảnh

**Giải thích:** Phổ biên độ (Magnitude, ký hiệu là $|F(u,v)|$) đại diện cho cường độ của sóng[cite: 5]. Thông số này đo lường và phản ánh chính xác khối lượng hoặc mức độ đóng góp (sức mạnh) của mỗi một dải tần số cụ thể vào tổng thể cấu tạo tín hiệu của bức ảnh[cite: 5]. Vị trí không gian bị chi phối bởi Góc pha[cite: 5].

</details>

### Câu 208
Nguồn PDF: trang 29

Biểu diễn Fourier của ảnh thực (real image) có đặc tính nào?

- A. Phổ biên độ không đối xứng
- B. Phổ biên độ đối xứng qua gốc tọa độ (Hermitian symmetry)
- C. Phổ pha luôn bằng 0
- D. Phổ biên độ luôn thực

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Phổ biên độ đối xứng qua gốc tọa độ (Hermitian symmetry)

**Giải thích:** Vì ảnh kỹ thuật số gốc là một tập hợp các giá trị không gian thực (real image), kết quả chuyển đổi phổ Fourier của nó sở hữu một đặc điểm toán học bắt buộc: tính đối xứng Hermitian[cite: 5]. Định lý này bảo đảm rằng phổ biên độ của ảnh luôn luôn có cấu trúc đối xứng nghịch đảo (conjugate symmetric) hoàn hảo qua trục gốc tọa độ trung tâm: $F(-u,-v) = F^*(u,v)$[cite: 5].

</details>

### Câu 209
Nguồn PDF: trang 29

Bộ lọc Ideal Low-pass có nhược điểm gì?

- A. Chậm hơn Gaussian
- B. Gây ra hiệu ứng ringing (Gibbs phenomenon)
- C. Không thể cài đặt
- D. Không hoạt động với ảnh màu

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Gây ra hiệu ứng ringing (Gibbs phenomenon)

**Giải thích:** Bộ lọc thông thấp lý tưởng (Ideal Low-pass filter) được định nghĩa là một hình trụ tròn cắt cụt dải tần số một cách cực kỳ đột ngột[cite: 5]. Tuy nhiên, theo toán học, khi áp dụng IFFT để đưa một mặt nạ cắt gắt như vậy về lại không gian 2D, kernel sinh ra sẽ có hình gợn sóng $sinc(x)$ vô tận. Khi chập kernel này vào ảnh, nó tạo ra các quầng sóng ảo bao quanh vật thể, được gọi là hiệu ứng ringing artifacts (hay hiện tượng Gibbs)[cite: 5].

</details>

### Câu 210
Nguồn PDF: trang 29

Bộ lọc Gaussian trong miền tần số cho kết quả gì trong miền không gian sau khi inverse?

- A. Laplacian filter
- B. Gaussian filter (biến đổi Fourier của Gaussian là Gaussian)
- C. Sobel filter
- D. Median filter

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Gaussian filter (biến đổi Fourier của Gaussian là Gaussian)

**Giải thích:** Hàm phân phối chuẩn Gaussian có một tính chất hình học đặc biệt là dạng sóng của nó tự đồng dạng qua phép biến đổi[cite: 5]. Bất kỳ một hàm Gaussian nào trong miền không gian, khi đưa qua phép biến đổi Fourier, sẽ cho ra kết quả vẫn là một hình dạng nón Gaussian trong miền tần số và ngược lại[cite: 5]. Điều này khiến bộ lọc Gaussian làm mờ êm dịu, không bị gợn sóng ringing[cite: 5].

</details>

### Câu 211
Nguồn PDF: trang 29

Để tính DFT của ảnh kích thước N×N, cần bao nhiêu phép nhân phức?

- A. O(N)
- B. O(N²)
- C. O(N² log N)
- D. O(N⁴)

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** D. O(N⁴)

**Giải thích:** Trong công thức trực tiếp của DFT 2D cho ảnh kích thước $N \times M$, mỗi điểm trên miền phổ đòi hỏi một chuỗi vòng lặp tích phân hai chiều để tính toán[cite: 5]. Đối với ảnh vuông lưới $N \times N$, hệ thống sẽ cần thực hiện một khối lượng công việc khổng lồ, yêu cầu tổng cộng $O(N^4)$ phép tính nhân số phức, khiến thuật toán trở nên quá chậm với ảnh lớn[cite: 5].

</details>

### Câu 212
Nguồn PDF: trang 29

Inverse DFT (IDFT) dùng để làm gì?

- A. Chuyển ảnh từ miền không gian sang miền tần số
- B. Chuyển từ miền tần số về miền không gian
- C. Tính gradient ảnh
- D. Lọc nhiễu trực tiếp

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Chuyển từ miền tần số về miền không gian

**Giải thích:** Quá trình xử lý tín hiệu hoàn chỉnh đòi hỏi một chu trình khép kín[cite: 5]. Sau khi ta biến đổi dữ liệu bằng (Forward) Fourier Transform và nhân sửa chữa xong ma trận trong miền tần số, phép biến đổi Fourier nghịch đảo (Inverse Fourier Transform - IDFT) được thi hành để tái cấu trúc và đưa phổ ảnh quay ngược trở lại hình dạng quen thuộc hiển thị trong miền không gian (spatial domain)[cite: 5].

</details>

### Câu 213
Nguồn PDF: trang 29

PCA (Principal Component Analysis) trong xử lý ảnh dùng để làm gì? (Chọn tất cả đúng)

- A. Giảm chiều dữ liệu
- B. Trích xuất đặc trưng quan trọng nhất
- C. Nén ảnh
- D. Tăng độ phân giải

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Giảm chiều dữ liệu; B. Trích xuất đặc trưng quan trọng nhất; C. Nén ảnh

**Giải thích:** Trong lý thuyết máy học và nhận dạng mẫu, Phân tích thành phần chính (PCA) là một biến đổi tuyến tính chiếu dữ liệu sang một không gian phụ[cite: 5]. Mục tiêu thiết kế của thuật toán là tìm ra các trục chứa phương sai biến đổi lớn nhất (trích xuất đặc trưng), từ đó loại bỏ các trục thừa để giảm chiều không gian bộ nhớ (giảm chiều) và cô đọng dữ liệu gốc (nén ảnh)[cite: 5].

</details>

### Câu 214
Nguồn PDF: trang 29

Bộ lọc Band-pass trong miền tần số giữ lại gì?

- A. Chỉ tần số thấp
- B. Chỉ tần số cao
- C. Dải tần số nằm trong một khoảng nhất định
- D. Tất cả tần số

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** C. Dải tần số nằm trong một khoảng nhất định

**Giải thích:** Khác với High-pass hay Low-pass lấy một ngưỡng cắt từ gốc, bộ lọc thông dải (Band-pass filter) được định hình bởi hình khối chiếc bánh donut[cite: 5]. Về mặt toán học, bộ lọc này được thiết kế dựa trên sự giao thoa (phép nhân mặt nạ) giữa một Low-pass và một High-pass, khiến nó chỉ cho phép tín hiệu trong một khoảng băng thông hẹp (band-width $w$) ở khoảng cách $D_0$ đi qua và loại bỏ mọi thứ khác[cite: 5].

</details>

### Câu 215
Nguồn PDF: trang 29

Khi xem phổ Fourier của ảnh tự nhiên (natural image), đặc điểm nào thường thấy?

- A. Năng lượng phân bố đều
- B. Năng lượng tập trung ở tần số thấp (vùng trung tâm phổ)
- C. Năng lượng tập trung ở tần số cao
- D. Không có đặc điểm rõ ràng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Năng lượng tập trung ở tần số thấp (vùng trung tâm phổ)

**Giải thích:** Tính chất cố hữu của hình ảnh thực là các vùng vật thể thường liên tục và thay đổi chuyển màu mượt mà, chỉ bị đứt đoạn ở các đường viền[cite: 5]. Do quy luật này, khi được soi chiếu dưới phổ Fourier, đại đa số năng lượng vật lý (trên 90%) của các bức ảnh tự nhiên luôn bị hút dồn và cô đặc lại ở khu vực tần số thấp, tức là vùng đốm sáng nằm ngay tại trung tâm của mặt phẳng tần số[cite: 5].

</details>

### Câu 216
Nguồn PDF: trang 30

Biến đổi Fourier rời rạc 2D (2D DFT) của ảnh I(x,y) cho ra hàm nào?

- A. F(x,y) - phổ trong không gian
- B. F(u,v) - phổ trong miền tần số
- C. G(t) - phổ theo thời gian
- D. H(k) - phổ theo kênh màu

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. F(u,v) - phổ trong miền tần số

**Giải thích:** Dưới góc nhìn quy ước toán học của môn học, một bức ảnh gốc được ký hiệu bởi hệ trục không gian (spatial domain) 2D là biến $x$ và $y$ ($I(x,y)$ hoặc $f(x,y)$)[cite: 5]. Khi đi qua bộ chuyển đổi 2D DFT, tín hiệu được ánh xạ và trả ra dưới dạng một hàm phổ sóng nằm trên trục hệ tọa độ tương ứng của miền tần số (frequency domain), được định danh bởi cặp biến $u$ và $v$ thành $F(u,v)$[cite: 5].

</details>

### Câu 217
Nguồn PDF: trang 30

Tại sao khi hiển thị phổ Fourier thường dùng log(1 + |F(u,v)|)?

- A. Để tăng tốc độ tính toán
- B. Vì phổ có dải động rất lớn; log giúp thấy rõ cả tần số thấp lẫn cao
- C. Vì phổ có giá trị âm
- D. Để chuẩn hóa về [0,1]

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Vì phổ có dải động rất lớn; log giúp thấy rõ cả tần số thấp lẫn cao

**Giải thích:** Do 90-99% năng lượng ảnh tập trung ở đỉnh trung tâm (DC), phổ Fourier $|F(u,v)|$ gốc có dải động biên độ biến thiên khổng lồ, khiến các điểm tần số cao xung quanh gần như chìm vào bóng tối tuyệt đối nếu chỉ render cường độ tuyến tính[cite: 5]. Việc phủ thêm hàm nén logarit $\log(1 + |F(u,v)|)$ (Enhanced Spectra) sẽ ép giảm cái đỉnh chói lóa ở giữa và nâng độ sáng cho các đốm mờ xung quanh, giúp mắt người có thể quan sát được cấu trúc đồ thị[cite: 5].

</details>

### Câu 218
Nguồn PDF: trang 30

Butterworth Low-pass Filter có ưu điểm gì so với Ideal Low- pass?

- A. Nhanh hơn
- B. Không gây hiệu ứng ringing
- C. Đơn giản hơn
- D. Không cần chỉ định frequency cutoff

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Không gây hiệu ứng ringing

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* Butterworth có đáp ứng chuyển tiếp liên tục H(D) = 1 / [1 + (D/D0)^(2n)], nên thường giảm ringing so với bộ lọc Ideal cắt đột ngột tại D0. **Lưu ý:** B diễn đạt quá tuyệt đối: khi bậc n cao, Butterworth tiến gần dạng cắt sắc và vẫn có thể gây ringing; lợi thế đúng là giảm hiện tượng này với lựa chọn bậc phù hợp. Nó vẫn cần cutoff và bậc lọc, không mặc nhiên nhanh hay đơn giản hơn Ideal. Đối chiếu: [ghi chú về Butterworth](https://www.math.cuhk.edu.hk/~lmlui/suppnote8.pdf).

</details>

### Câu 219
Nguồn PDF: trang 30

Ứng dụng của lọc trong miền tần số là gì? (Chọn tất cả đúng)

- A. Loại bỏ nhiễu tuần hoàn (periodic noise)
- B. Làm mờ ảnh
- C. Làm sắc nét ảnh
- D. Phát hiện hướng của feature

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Loại bỏ nhiễu tuần hoàn (periodic noise); B. Làm mờ ảnh; C. Làm sắc nét ảnh

**Giải thích:** Việc thao túng trực tiếp phổ ma trận trong không gian tần số cho phép người kỹ sư thực thi nhiều tác vụ kinh điển[cite: 5]. Bằng cách áp dụng các tấm mặt nạ (masks), ta có thể nhân lọc thông thấp (để làm mờ), lọc thông cao (để làm sắc nét/tìm cạnh), và đặc biệt hữu ích là dùng Notched filter để triệt tiêu và loại bỏ sạch sẽ các đốm nhiễu lặp lại có chu kỳ (periodic/sinus noise)[cite: 5].

</details>

### Câu 220
Nguồn PDF: trang 30

Ảnh sau khi biến đổi Fourier thuận và ngay sau đó biến đổi Fourier nghịch là gì?

- A. Ảnh bị thay đổi
- B. Ảnh gốc (không thay đổi, miễn là không lọc ở giữa)
- C. Ảnh bị nhân đôi
- D. Ảnh grayscale

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Ảnh gốc (không thay đổi, miễn là không lọc ở giữa)

**Giải thích:** Cặp biến đổi Fourier được xây dựng dựa trên nguyên lý chu trình thuận nghịch khép kín và không gây mất mát thông tin (lossless)[cite: 5]. Do đó, nếu ta phân rã một hình ảnh thành hàm ma trận bằng DFT, rồi lập tức áp dụng hàm nghịch đảo IDFT lên kết quả đó mà không cài cắm bất kỳ bộ lọc can thiệp (multiply by filter) nào xen giữa, tín hiệu trả về sẽ phục hồi nguyên trạng 100% giống hệt như ảnh gốc[cite: 5].

</details>

### Câu 221
Nguồn PDF: trang 30

Trong lọc ảnh miền tần số, bước nào sau đây là đúng theo thứ tự?

- A. Filter → DFT → Multiply → IDFT
- B. DFT → Multiply by filter → IDFT
- C. IDFT → Multiply → DFT
- D. DFT → Add filter → IDFT

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. DFT → Multiply by filter → IDFT

**Giải thích:** Một quy trình ứng dụng thao tác lọc phổ ảnh chuẩn xác (Pipeline) bắt buộc tuân theo ba mắt xích tuần tự[cite: 5]. Đầu tiên, ảnh không gian vật lý phải được di chuyển qua cổng lượng tử bằng phép biến đổi DFT. Tại buồng tần số, ta thực hiện phép toán cốt lõi là Nhân điểm (Multiply) ma trận phổ với bộ lọc $H$. Bước kết thúc là đưa sản phẩm đi qua cổng IDFT để hiện hình trở lại thế giới thực[cite: 5]. Phép tính trong tần số là nhân (Multiply) chứ không phải là cộng (Add).

</details>

### Câu 222
Nguồn PDF: trang 30

Nhiễu tuần hoàn (periodic noise) trong ảnh xuất hiện như thế nào trong phổ Fourier?

- A. Phân tán rộng khắp phổ
- B. Dưới dạng các điểm sáng (spikes) ở vị trí tương ứng với tần số nhiễu
- C. Tập trung ở tần số thấp
- D. Không thể phát hiện

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Dưới dạng các điểm sáng (spikes) ở vị trí tương ứng với tần số nhiễu

**Giải thích:** Nhiễu sóng sin hoặc nhiễu sọc tuần hoàn (periodic noise) trên ảnh thực chất là dao động của một dải sóng đơn lẻ rất mạnh bị xếp đè lên không gian[cite: 5]. Nhờ năng lực bóc tách của Fourier, sóng đơn này sẽ bị lật tẩy và hiển thị rõ ràng trên đồ thị phổ dưới hình dạng hai đốm sáng đối xứng sắc nét (spikes), nổi bật và nằm xa trung tâm phổ tương ứng với hướng quét của nó[cite: 5].

</details>

### Câu 223
Nguồn PDF: trang 31

Để loại bỏ nhiễu tuần hoàn, kỹ thuật nào trong miền tần số được dùng?

- A. Low-pass filter
- B. Notch filter (lọc loại dải hẹp tại tần số nhiễu)
- C. High-pass filter
- D. Gaussian filter

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Notch filter (lọc loại dải hẹp tại tần số nhiễu)

**Giải thích:** Nhiễu tuần hoàn dạng sọc hoặc sóng tập trung năng lượng ở một số vị trí trong phổ Fourier, thay vì phân bố đều trên mọi tần số. Notch filter giảm những vùng phổ hẹp chứa nhiễu và, với ảnh thực, thường xử lý cả cặp vị trí đối xứng để giữ tính đối xứng liên hợp. Nhờ nhắm vào tần số nhiễu, nó giữ được nhiều thông tin ảnh hơn một low-pass loại rộng các chi tiết; high-pass cũng không bảo đảm loại đúng thành phần tuần hoàn. Tham chiếu: `IT5409 L3.2-ImageTransformFrequency.pdf`, trang 30.

</details>

### Câu 224
Nguồn PDF: trang 31

2D DFT có tính đối xứng nào đặc biệt?

- A. Phổ biên độ đối xứng 2 lần
- B. Phổ biên độ đối xứng 4 lần (đối xứng qua cả 2 trục)
- C. Phổ pha đối xứng
- D. Không có tính đối xứng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Phổ biên độ đối xứng 4 lần (đối xứng qua cả 2 trục)

**Giải thích:** Cấu trúc phổ tạo ra bởi 2D DFT của một hình ảnh luôn mang tính phân phối Hermitian[cite: 5]. Tính chất toán học liên hợp này tạo ra một hiện tượng thị giác là mảng phổ biên độ sẽ xuất hiện các chùm sao băng đối xứng lặp lại nhau, dẫn đến kết quả phản chiếu hình học đặc thù là đối xứng tuyệt đối qua cả hai trục (4 lần đối xứng)[cite: 5].

</details>

### Câu 225
Nguồn PDF: trang 31

Dịch chuyển trung tâm phổ Fourier (fftshift) dùng để làm gì?

- A. Tăng độ phân giải phổ
- B. Đưa tần số thấp (DC) về trung tâm ảnh phổ để dễ quan sát và xử lý
- C. Tính nhanh DFT
- D. Lọc tần số cao

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Đưa tần số thấp (DC) về trung tâm ảnh phổ để dễ quan sát và xử lý

**Giải thích:** Khi thực thi bằng máy tính, ma trận đầu ra ban đầu của DFT xếp thành phần cực đại DC (tần số 0) rúc vào góc tư trên cùng bên trái, khiến việc hình dung phổ 2D bị đứt gãy và rất khó cấu hình tâm bộ lọc[cite: 5]. Lệnh hoán đổi góc tư `fftshift` là một thủ thuật dịch chuyển nhằm kéo phần tử DC về yên vị đúng tại trung tâm vật lý của bức ảnh, trả lại sự trực quan quan sát theo hệ tọa độ Decartes[cite: 5].

</details>

### Câu 226
Nguồn PDF: trang 31

Phổ Fourier của hàm delta Dirac δ(x,y) là gì?

- A. Hàm Gaussian
- B. Hằng số (tất cả tần số đều bằng nhau)
- C. Hàm sin
- D. Hàm cos

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Hằng số (tất cả tần số đều bằng nhau)

**Giải thích:** Xung Delta Dirac ($\delta$) là một hàm cực điểm lý tưởng, chỉ bùng nổ tại một tọa độ không gian độc nhất và vô hiệu tại mọi nơi khác[cite: 5]. Khi đối chiếu sang cặp biến đổi Fourier, năng lượng vô hạn của hạt không gian này được dàn mỏng và trải phẳng tắp ra mọi chân trời, khiến phổ biên độ trở thành một đường hằng số thẳng băng (constant), tức là chứa năng lượng như nhau ở tất cả các tần số[cite: 5].

</details>

### Câu 227
Nguồn PDF: trang 31

PCA giảm chiều dữ liệu bằng cách nào?

- A. Loại bỏ các pixel không quan trọng
- B. Tìm các hướng (principal components) có phương sai lớn nhất và chiếu dữ liệu lên đó
- C. Nén ảnh theo JPEG
- D. Lấy mẫu lại ảnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Tìm các hướng (principal components) có phương sai lớn nhất và chiếu dữ liệu lên đó

**Giải thích:** Cốt lõi của thuật toán PCA là đi tìm một hệ trục tọa độ mới (các eigenvector/principal components) sao cho khi áp mảng dữ liệu phân tán lên đó, nó bộc lộ được lượng thông tin khác biệt mạnh mẽ nhất[cite: 5]. Các trục này được sắp xếp theo mức độ phương sai lớn nhất (greatest variability), sau đó PCA ép phẳng dữ liệu xuống (chiếu - project) và chỉ giữ lại vài trục top đầu để hoàn thành nhiệm vụ giảm số chiều[cite: 5].

</details>

### Câu 228
Nguồn PDF: trang 31

Tại sao Fourier Transform quan trọng trong xử lý ảnh?

- A. Vì nó chỉ hoạt động với ảnh đen trắng
- B. Vì nó cho phép phân tích và lọc theo tần số, giúp xử lý nhiều loại nhiễu và đặc trưng
- C. Vì nó tính toán histogram
- D. Vì nó chỉ dùng cho ảnh lớn

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Vì nó cho phép phân tích và lọc theo tần số, giúp xử lý nhiều loại nhiễu và đặc trưng

**Giải thích:** Sự ra đời của nền tảng Fourier mở ra một chiều không gian tư duy mới cho thị giác máy tính thay vì chỉ sửa pixel[cite: 5]. Quyền năng của nó nằm ở việc chuyển dịch tín hiệu để tạo ra năng lực phân tích cấu trúc theo phổ tần số, từ đó cung cấp phương tiện hoàn hảo để triệt tiêu các mẫu nhiễu phức tạp, phân tách biên và trích xuất đặc điểm (texture/feature) một cách dễ dàng và hiệu quả bằng kỹ thuật lọc (filter)[cite: 5].

</details>

### Câu 229
Nguồn PDF: trang 31

Real part và Imaginary part trong DFT lưu trữ thông tin gì?

- A. Thông tin biên độ và pha riêng biệt
- B. Các thành phần của số phức, kết hợp tính được biên độ và pha
- C. Thông tin màu sắc
- D. Thông tin không gian

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Các thành phần của số phức, kết hợp tính được biên độ và pha

**Giải thích:** Kết xuất thô của quá trình chuyển đổi Fourier Discrete là một mạng lưới các biến số toán học phức bao gồm phần Thực (Real part - $R$) và phần Ảo (Imaginary part - $I$)[cite: 5]. Bản thân chúng khi đứng độc lập không mang ý nghĩa hiển thị, nhưng thông qua phép lượng giác kết hợp lại, chúng đóng vai trò là chìa khóa để nội suy ra Biên độ ánh sáng ($A = \sqrt{R^2 + I^2}$) và tọa độ Góc Pha ($\phi = \tan^{-1}(I/R)$)[cite: 5].

</details>

### Câu 230
Nguồn PDF: trang 31

Khi lấy absolute value của DFT (|F(u,v)|), ta thu được gì?

- A. Phase của ảnh
- B. Magnitude spectrum (phổ biên độ)
- C. Ảnh trong miền không gian
- D. Gradient ảnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Magnitude spectrum (phổ biên độ)

**Giải thích:** Vector trong ma trận DFT mang thành phần ảo[cite: 5]. Để đo lường chiều dài thực tế biểu thị năng lượng của vector này, kỹ sư phần mềm áp dụng phép tính lấy giá trị tuyệt đối (Absolute value, $|F(u,v)|$). Hàm độ lớn Euclidean này lập tức tạo ra một bản đồ sóng phản chiếu cường độ năng lượng, và đó chính là Phổ Biên độ (Magnitude Spectrum)[cite: 5].

</details>

### Câu 231
Nguồn PDF: trang 32

Âm nhạc (music) liên quan đến Fourier Transform như thế nào?

- A. Âm nhạc không liên quan
- B. Âm nhạc là tín hiệu thời gian; DFT cho thấy phổ tần số (các nốt nhạc) trong tín hiệu
- C. DFT chỉ dùng cho tín hiệu hình ảnh
- D. Âm nhạc dùng DCT, không dùng DFT

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Âm nhạc là tín hiệu thời gian; DFT cho thấy phổ tần số (các nốt nhạc) trong tín hiệu

**Giải thích:** Các luồng âm thanh kỹ thuật số hay âm nhạc thực chất là những dao động tín hiệu hỗn mang thu thập dọc theo miền thời gian (time-domain)[cite: 5]. Khi chạy bộ FFT qua các clip nhạc này, hệ thống sẽ bóc tách mớ hỗn độn đó và bày ra một đồ thị dải phổ đo lường từng nấc sức mạnh của các tần số cụ thể (hertz), tương ứng chính xác với các nốt nhạc trầm bổng cấu thành bài hát[cite: 5].

</details>

### Câu 232
Nguồn PDF: trang 32

Bộ lọc High-pass trong miền tần số thu được bằng cách nào?

- A. H_HP = H_LP
- B. H_HP = 1 - H_LP
- C. H_HP = H_LP + 1
- D. H_HP = H_LP × 2

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. H_HP = 1 - H_LP

**Giải thích:** Bộ lọc thông thấp (LP) giữ phần trung tâm, còn bộ lọc thông cao (HP) thì chặn khuếch đại tâm và giữ vùng viền ngoài[cite: 5]. Do tổng bảo toàn của không gian ma trận lý tưởng là 1, hình học của màng lọc High-pass được chế tác cực kỳ dễ dàng thông qua thuật toán đảo nghịch: lấy ma trận đơn vị toàn phần trừ đi bóng chiếu của một Low-pass filter với cùng đường kính (bán kính cắt $D_0$), tương đương phương trình: $H_{HP} = 1 - H_{LP}$[cite: 5].

</details>

### Câu 233
Nguồn PDF: trang 32

Định lý dịch chuyển Fourier (Shift Theorem) phát biểu gì?

- A. Dịch chuyển trong miền không gian → Nhân với hàm mũ phức trong miền tần số
- B. Dịch chuyển tương đương với scaling
- C. Không có mối quan hệ giữa dịch chuyển và Fourier
- D. Dịch chuyển trong miền không gian → Dịch chuyển trong miền tần số

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Dịch chuyển trong miền không gian → Nhân với hàm mũ phức trong miền tần số

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* Theo quy ước Fourier dùng số mũ âm, dịch ảnh đi (x0, y0) nhân phổ với exp[-i*2*pi*(u*x0/M + v*y0/N)]. Thừa số này có độ lớn bằng 1 nên làm đổi pha, không làm dịch các vị trí tần số hoặc đổi phổ biên độ. Với DFT hữu hạn, tính chất chính xác áp dụng cho dịch vòng; dịch ảnh rồi cắt mất nội dung ở biên không còn giữ nguyên mọi hệ số theo quy tắc đó. Đối chiếu: [định lý dịch của DFT](https://www.dsprelated.com/freebooks/mdft/Fourier_Theorems_DFT.html).

</details>

### Câu 234
Nguồn PDF: trang 32

Khi muốn làm mờ ảnh trong miền tần số, cần thực hiện gì?

- A. Nhân phổ với High-pass filter
- B. Nhân phổ với Low-pass filter
- C. Cộng hằng số vào phổ
- D. Đảo ngược phổ

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Nhân phổ với Low-pass filter

**Giải thích:** Trạng thái sắc nét của ảnh xuất phát từ những đường ranh giới thay đổi đột biến tương ứng với các hạt năng lượng nhảy múa ở vùng ngoài rìa phổ[cite: 5]. Để đập tan sự gai góc này nhằm tạo hiệu ứng phủ sương (làm mờ / blurring), thuật toán xử lý là dùng một màng lọc Low-pass filter (chỉ mở lỗ thủng trung tâm) áp vào và nhân đè lên bức phổ, cạo sạch toàn bộ rác tần số cao trước khi trả ảnh về miền không gian[cite: 5].

</details>

### Câu 235
Nguồn PDF: trang 32

Bộ lọc nào trong miền tần số tương đương với phép lấy trung bình (Mean filter) trong miền không gian?

- A. Ideal High-pass
- B. Ideal Low-pass (gần như, do Mean filter là low-pass đơn giản)
- C. Band-pass
- D. Notch filter

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Ideal Low-pass (gần như, do Mean filter là low-pass đơn giản)

**Giải thích:** Mean filter lấy trung bình trong một cửa sổ, tức nhân chập với kernel hình hộp đã chuẩn hóa, và có tác dụng thông thấp. **Lưu ý:** B chỉ là lựa chọn gần nhất về nhóm chức năng, không phải tương đương toán học với Ideal Low-pass: Fourier của kernel hộp có dạng sinc hoặc sinc rời rạc với các thùy phụ, không phải mặt nạ cắt tần số dạng bậc thang. Slide minh họa trực tiếp cặp averaging và sinc, nên không nên học rằng hai bộ lọc tạo cùng kết quả. Tham chiếu: `IT5409 L3.2-ImageTransformFrequency.pdf`, trang 23, 26.

</details>

### Câu 236
Nguồn PDF: trang 32

Ứng dụng thực tế của lọc High-pass trong ảnh y tế là gì?

- A. Làm mờ nền
- B. Làm nổi bật các cấu trúc sắc nét như xương, mô
- C. Giảm nhiễu
- D. Tăng độ sáng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Làm nổi bật các cấu trúc sắc nét như xương, mô

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* High-pass ưu tiên những biến thiên cường độ nhanh, vì vậy có thể làm nổi bật ranh giới cấu trúc trong ảnh y tế khi ranh giới có đủ tương phản. B nói về tăng khả năng quan sát chi tiết, không có nghĩa bộ lọc biết đâu là xương hay mô hoặc tự thực hiện phân đoạn giải phẫu. Nhiễu cũng thường có thành phần tần số cao, nên lọc này có thể khuếch đại nhiễu và không được coi là một phép giảm nhiễu hay chẩn đoán.

</details>

### Câu 237
Nguồn PDF: trang 32

Nếu ảnh có kích thước M×N, DFT cho ra ảnh phổ có kích thước bao nhiêu?

- A. M/2 × N/2
- B. M × N (cùng kích thước)
- C. 2M × 2N
- D. sqrt(M) × sqrt(N)

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. M × N (cùng kích thước)

**Giải thích:** Phép toán phân rã sóng DFT ánh xạ cấu trúc tín hiệu 2D sang một hệ quy chiếu dạng chuỗi khác nhưng tuân thủ nguyên tắc bảo toàn tính liên hợp của dữ liệu điểm ảnh[cite: 5]. Kết quả của định lý chuyển đổi này là mảng lưới ma trận lưu trữ số phức xuất ra ở miền tần số (Fourier Spectrum) sẽ giữ nguyên vẹn chiều dài và chiều rộng ($M \times N$), khớp hoàn toàn với số lượng pixel của bức ảnh không gian ban đầu[cite: 5].

</details>

### Câu 238
Nguồn PDF: trang 32

Circular convolution (nhân chập vòng) xuất hiện như thế nào khi làm việc trong miền tần số?

- A. Không xuất hiện
- B. Khi nhân phổ của hai tín hiệu, IDFT cho convolution vòng; cần zero- padding để tránh wrap-around
- C. Luôn cho kết quả giống linear convolution
- D. Chỉ xảy ra với ảnh màu

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Khi nhân phổ của hai tín hiệu, IDFT cho convolution vòng; cần zero- padding để tránh wrap-around

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* Nhân hai DFT cùng kích thước rồi IDFT tạo nhân chập vòng vì DFT xem dữ liệu như một chu kỳ của tín hiệu tuần hoàn. Phần kết quả vượt biên sẽ quấn về đầu mảng, tạo wrap-around nếu muốn tính nhân chập tuyến tính. Với hai mảng dài M và K trên một trục, padding tới ít nhất M + K - 1 mẫu cho phép lấy kết quả tuyến tính; ảnh 2D cần đủ padding trên cả hai trục. Đối chiếu: [định lý nhân chập DFT](https://www.dsprelated.com/freebooks/mdft/Fourier_Theorems_DFT.html).

</details>

### Câu 239
Nguồn PDF: trang 33

Trong xử lý ảnh y tế, biến đổi Wavelet khác DFT ở điểm nào?

- A. Wavelet không thể áp dụng cho ảnh 2D
- B. Wavelet phân tích đồng thời theo cả tần số và vị trí; DFT chỉ phân tích tần số toàn cục
- C. DFT cho kết quả tốt hơn trong mọi trường hợp
- D. Không có sự khác biệt

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Wavelet phân tích đồng thời theo cả tần số và vị trí; DFT chỉ phân tích tần số toàn cục

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* DFT toàn ảnh dùng các hàm cơ sở trải rộng trên ảnh, còn wavelet phân tích bằng những hàm được dịch và co giãn để giữ thông tin vị trí ở nhiều mức độ chi tiết. DWT 2D tạo các thành phần xấp xỉ và chi tiết theo nhiều hướng, giúp mô tả cấu trúc cục bộ ở các scale khác nhau. B đúng về kiểu biểu diễn, nhưng DFT vẫn chứa thông tin vị trí qua pha và có thể dùng theo cửa sổ; không nên hiểu rằng Fourier hoàn toàn mất vị trí. Đối chiếu: [DWT hai chiều](https://pywavelets.readthedocs.io/en/latest/ref/2d-dwt-and-idwt.html).

</details>

### Câu 240
Nguồn PDF: trang 33

Thành phần DC của DFT (F(0,0)) biểu diễn điều gì?

- A. Gradient cao nhất trong ảnh
- B. Giá trị trung bình (mean) của tất cả pixel trong ảnh
- C. Pixel sáng nhất
- D. Pixel tối nhất

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Giá trị trung bình (mean) của tất cả pixel trong ảnh

**Giải thích:** Tại gốc tọa độ trung tâm của ma trận tần số ($u=0, v=0$), phổ biến đổi Fourier $F(0,0)$ không dao động[cite: 5]. Biến số này được định danh là thành phần tần số 0 hay tín hiệu dòng điện một chiều (DC component)[cite: 5]. Do công thức loại trừ hàm mũ $e^0$, sức mạnh biên độ tại đỉnh hạt nhân này đại diện trực tiếp cho tổng năng lượng không gian, tỷ lệ thuận với giá trị sáng tối trung bình cộng (mean value) của toàn bộ bức ảnh[cite: 5].

</details>

### Câu 241
Nguồn PDF: trang 33

Khi tăng cutoff frequency của Low-pass filter, điều gì xảy ra với ảnh?

- A. Ảnh mờ hơn
- B. Ảnh ít mờ hơn (giữ lại nhiều chi tiết hơn)
- C. Không thay đổi
- D. Ảnh tối hơn

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Ảnh ít mờ hơn (giữ lại nhiều chi tiết hơn)

**Giải thích:** Tần số cắt (cutoff frequency, $D_0$) là bán kính vòng tròn quyết định giới hạn chặn năng lượng của Low-pass filter[cite: 5]. Việc kỹ sư mở rộng ranh giới này (tăng $D_0$) tương đương với việc đục một cái lỗ thủng to hơn ở giữa màng lọc[cite: 5]. Do băng thông cho qua được nới rộng, một lượng lớn các dải tần số cao hơn mang theo đặc tính đường viền sẽ lọt lưới và hồi sinh, giúp kết quả ít bị nhòe và sắc bén hơn (ít mờ hơn)[cite: 5].

</details>

### Câu 242
Nguồn PDF: trang 33

Biến đổi Fourier và biến đổi Hartley (Hartley Transform) khác nhau như thế nào?

- A. Không có sự khác biệt
- B. Hartley cho kết quả thực, trong khi DFT cho kết quả phức
- C. DFT luôn nhanh hơn
- D. Hartley chỉ dùng cho âm thanh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Hartley cho kết quả thực, trong khi DFT cho kết quả phức

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* Hartley dùng hàm cơ sở thực cas(t) = cos(t) + sin(t), nên biến đổi dữ liệu thực thành hệ số thực. DFT dùng số mũ phức, do đó biểu diễn thông tin qua phần thực và phần ảo, dù một số dữ liệu đặc biệt có thể cho hệ số hoàn toàn thực. Hai biến đổi có quan hệ với nhau và đều áp dụng được cho ảnh; dạng hệ số thực không tự bảo đảm Hartley nhanh hơn FFT hoặc chỉ phù hợp với âm thanh. Đối chiếu: [Discrete Hartley Transform của FFTW](https://www.fftw.org/doc/The-Discrete-Hartley-Transform.html).

</details>

### Câu 243
Nguồn PDF: trang 33

Ảnh nhiễu tuần hoàn có phổ Fourier nổi bật ở vị trí nào?

- A. Ở trung tâm phổ (tần số 0)
- B. Ở các điểm sáng ngoài trung tâm tương ứng với tần số và hướng của nhiễu
- C. Ở khắp phổ đều nhau
- D. Không có vị trí đặc biệt

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Ở các điểm sáng ngoài trung tâm tương ứng với tần số và hướng của nhiễu

**Giải thích:** Do có tính chất dao động lập lại lặp đi lặp lại rất mạnh của một bước sóng đều đặn, Nhiễu hình rèm (Periodic noise / sinus noise) không hòa tan thành sương mù ở giữa tâm phổ[cite: 5]. Khi nội suy trên ma trận Fourier, nguồn năng lượng đột biến này dội lên thành những cặp điểm sao băng phát quang chói lóa (spikes)[cite: 5]. Chúng đâm ra ở các cụm vị trí đối xứng rời xa nhân trung tâm tương thích trực tiếp với hướng góc của họa tiết nhiễu[cite: 5].

</details>

### Câu 244
Nguồn PDF: trang 33

Để đo phổ tần số của một âm thanh hoặc ảnh, công cụ toán học nào được dùng?

- A. Phép tích phân thông thường
- B. Biến đổi Fourier
- C. Phép đạo hàm
- D. Ma trận chuyển đổi

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Biến đổi Fourier

**Giải thích:** Từ những năm đầu thế kỷ 19, phương thức duy nhất và cũng là chuẩn mực cốt lõi (The basic tool) để đo lường, bóc tách và tạo ra một biểu đồ tần số dao động (frequency graphic) nhằm phân tích các dải sóng bên trong một tín hiệu âm nhạc, giọng nói hay khung hình tĩnh chính là vận dụng thuật toán vĩ đại Biến đổi Fourier (Fourier Transform)[cite: 5].

</details>

### Câu 245
Nguồn PDF: trang 33

Điều nào đúng về độ phức tạp tính toán của FFT so với DFT thông thường?

- A. FFT nhanh hơn O(N log N) vs O(N²)
- B. DFT nhanh hơn
- C. Chúng có cùng độ phức tạp
- D. FFT chỉ nhanh hơn khi N lớn

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. FFT nhanh hơn O(N log N) vs O(N²)

**Giải thích:** Fast Fourier Transform (FFT) cải thiện sức mạnh tính toán kinh khủng[cite: 5]. Bằng cách chia để trị, FFT phân tách quy trình để tái tạo kết quả phổ giống hệt Discrete Fourier Transform (DFT), nhưng với tốc độ cực nhanh vì nó kéo sập độ phức tạp giải thuật lũy thừa bình phương khổng lồ $O(N^2)$ của thế hệ cũ xuống quy mô tối ưu logarithm $O(N \log N)$[cite: 5].

</details>

### Câu 246
Nguồn PDF: trang 34

Signal có thể decompose thành tổng các sóng sin/cos theo Fourier series. Đây là khả năng áp dụng cho loại signal nào?

- A. Chỉ signal tuần hoàn
- B. Mọi loại signal (khi dùng Fourier Transform tổng quát, không chỉ Fourier Series)
- C. Chỉ signal audio
- D. Chỉ signal 1D

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Mọi loại signal (khi dùng Fourier Transform tổng quát, không chỉ Fourier Series)

**Giải thích:** Định luật nguyên thủy Fourier Series đưa ra cơ chế phân rã tổng trọng số (weighted sum) nhưng có một hạn chế chết người là nó yêu cầu tính lặp lại chu kỳ của hàm[cite: 5]. Tuy nhiên, phiên bản nâng cấp tích phân toàn diện Fourier Transform tổng quát (với chu kỳ kéo dài đến vô cực) đã giải quyết hạn chế này, cho phép hệ thống phân rã thành công mọi dạng tín hiệu đồ thị vật lý (bất kể chu kỳ hay 1D, 2D) để tìm phổ (Any univariate function)[cite: 5].

</details>

### Câu 247
Nguồn PDF: trang 34

Khi lọc High-pass trong miền tần số, đặc điểm của ảnh kết quả là gì?

- A. Ảnh mờ, ít chi tiết
- B. Chỉ còn lại các cạnh, biên và chi tiết sắc nét; vùng đồng nhất trở nên tối
- C. Không có cạnh
- D. Ảnh sáng đồng đều

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Chỉ còn lại các cạnh, biên và chi tiết sắc nét; vùng đồng nhất trở nên tối

**Giải thích:** Toán tử thông cao (High-pass filter) được sử dụng để bắt và duy trì sự chuyển động dữ dội[cite: 5]. Khi quét bộ lọc này, nó cắt bứt đứt toàn bộ cục u ánh sáng tần số thấp (DC) điều tiết nền, dẫn đến các bức tường và bầu trời vùng đồng nhất bị xóa sổ (phẳng về 0 thành tối đen)[cite: 5]. Trên màn hình chỉ hiển thị leo lét lại tàn tích ánh sáng của các đường đứt gãy, đó chính là các cạnh (edges) và điểm mốc (fine details)[cite: 5].

</details>

### Câu 248
Nguồn PDF: trang 34

Trong ứng dụng xử lý tín hiệu âm thanh, equalizer (EQ) hoạt động theo nguyên lý nào?

- A. Thay đổi biên độ tín hiệu tổng thể
- B. Khuếch đại hoặc giảm các dải tần số cụ thể (High-pass, Low-pass, Band- pass)
- C. Thêm tiếng vang
- D. Nén tín hiệu

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Khuếch đại hoặc giảm các dải tần số cụ thể (High-pass, Low-pass, Band- pass)

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* Equalizer điều chỉnh gain theo từng dải tần, chẳng hạn tăng dải bass nhưng giảm một vùng treble, nên đáp ứng tổng không nhất thiết là khuếch đại đều mọi thành phần. Bộ lọc có thể là shelving, peaking hoặc các bộ lọc chọn dải, vì vậy B mô tả đúng nguyên lý lựa chọn tần số dù danh sách trong ngoặc chưa đầy đủ. Thêm tiếng vang làm thay đổi tín hiệu theo cơ chế trễ, còn compressor chủ yếu điều khiển mức tín hiệu theo động học biên độ. Đối chiếu: [nguyên lý equalization](https://www.mathworks.com/help/audio/ug/equalization.html).

</details>

### Câu 249
Nguồn PDF: trang 34

Ứng dụng DCT (Discrete Cosine Transform) trong ảnh số là gì?

- A. Phát hiện biên ảnh
- B. Nén ảnh (ví dụ JPEG dùng DCT)
- C. Tăng tương phản
- D. Phân vùng ảnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Nén ảnh (ví dụ JPEG dùng DCT)

**Giải thích:** Discrete Cosine Transform (DCT) không tạo ra một ma trận số phức dư thừa như DFT mà chỉ xuất ra hệ số dạng thực (cosine)[cite: 5]. Việc này khiến DCT cực kỳ ăn khớp với bài toán nén tín hiệu số; đây là công nghệ nền tảng đóng vai trò làm trái tim nội suy và loại bỏ thông tin cao tần để thu nhỏ dung lượng tệp lưu trữ trong tiêu chuẩn nén ảnh công nghiệp JPEG[cite: 5].

</details>

### Câu 250
Nguồn PDF: trang 34

Gibbs phenomenon xảy ra khi nào?

- A. Khi dùng Gaussian filter
- B. Khi dùng Ideal Low-pass filter (cắt đột ngột), gây ringing artifacts
- C. Khi dùng Butterworth filter
- D. Khi ảnh có noise nhiều

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Khi dùng Ideal Low-pass filter (cắt đột ngột), gây ringing artifacts

**Giải thích:** Hiện tượng Gibbs (hay ringing problem) được gây ra bởi sự giới hạn của các thuật toán toán học[cite: 5]. Nó sẽ lập tức tàn phá hình ảnh (gây ringing artifacts) mỗi khi ta dại dột cài cắm một bộ lọc cắt đứt dải tần sắc lẹm và đột ngột như một cái ống bơ (Ideal Low-pass filter), sinh ra các dợn sóng nhòe $sinc(x)$ đập vào mép hình vật thể[cite: 5].

</details>

### Câu 251
Nguồn PDF: trang 34

Autocorrelation của ảnh trong miền tần số tương đương với?

- A. |F(u,v)|²
- B. F(u,v) × F*(u,v) = |F(u,v)|²
- C. F(u,v) + F*(u,v)
- D. F(u,v) / F*(u,v)

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. F(u,v) × F*(u,v) = |F(u,v)|²

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* Tích F*F_conjugate = |F|² là phổ công suất hoặc năng lượng tương ứng, còn autocorrelation trong miền không gian thu được bằng biến đổi Fourier ngược của tích đó với hệ số chuẩn hóa thích hợp. **Lưu ý:** câu hỏi nói 'trong miền tần số' nên B có thể hiểu là phổ của autocorrelation, không phải chính hàm tương quan theo độ dịch. A và B cũng tương đương toán học, khiến câu một đáp án này chưa chặt chẽ; không có căn cứ xem A sai. Đối chiếu: [quan hệ Wiener-Khinchin](https://www.stat.cmu.edu/~cshalizi/dst/18/lectures/10/lecture-10.html).

</details>

### Câu 252
Nguồn PDF: trang 34

Lọc ảnh trong miền tần số có lợi thế gì so với miền không gian cho kernel lớn?

- A. Cho kết quả khác nhau
- B. Nhanh hơn đáng kể khi kernel lớn vì O(N² log N) thay vì O(N² × K²)
- C. Chính xác hơn
- D. Ít tốn bộ nhớ hơn

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Nhanh hơn đáng kể khi kernel lớn vì O(N² log N) thay vì O(N² × K²)

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* Với ảnh N x N và kernel K x K, nhân chập trực tiếp cần khoảng K² phép tính cho mỗi pixel, cho chi phí O(N²*K²). FFT thay phép nhân chập bằng biến đổi, nhân phổ và biến đổi ngược, với chi phí gần O(P²*log P) trên kích thước P đã padding. B đúng về lợi thế thường gặp khi kernel lớn, nhưng chi phí chuẩn bị, bộ nhớ và padding khiến FFT không luôn nhanh hơn cho kernel nhỏ; nó cũng không tự tạo kết quả chính xác hơn. Đối chiếu: [FFT convolution](https://docs.scipy.org/doc/scipy/reference/generated/scipy.signal.fftconvolve.html).

</details>

### Câu 253
Nguồn PDF: trang 35

Biến đổi Hadamard (Hadamard Transform) khác DFT ở điểm nào?

- A. Không có sự khác biệt
- B. Hadamard chỉ dùng ±1 (không cần số phức), tính toán đơn giản hơn
- C. DFT nhanh hơn trong mọi trường hợp
- D. Hadamard chỉ dùng cho ảnh nhị phân

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Hadamard chỉ dùng ±1 (không cần số phức), tính toán đơn giản hơn

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* Ma trận Hadamard chưa chuẩn hóa có các phần tử +1 và -1, nên nhân với dữ liệu thực có thể thực hiện bằng các phép cộng và trừ thay vì hệ số phức của DFT. Các hàng trực giao giúp biểu diễn tín hiệu bằng tổ hợp những mẫu dấu khác nhau; bản chuẩn hóa thêm một hệ số để bảo toàn chuẩn. B vì vậy đúng về cấu trúc tính toán, nhưng đầu vào không bị giới hạn ở ảnh nhị phân và tốc độ thực tế còn phụ thuộc kích thước, thuật toán, triển khai. Đối chiếu: [ma trận Hadamard](https://docs.scipy.org/doc/scipy/reference/generated/scipy.linalg.hadamard.html).

</details>

### Câu 254
Nguồn PDF: trang 35

Khi biến đổi Fourier, thành phần pha (phase) quan trọng hơn biên độ (magnitude) trong việc giữ cấu trúc ảnh như thế nào?

- A. Magnitude quan trọng hơn hoàn toàn
- B. Nếu hoán đổi phase của hai ảnh, ảnh kết quả trông giống ảnh gốc có phase đó hơn là ảnh có magnitude
- C. Chúng quan trọng như nhau
- D. Phase không quan trọng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Nếu hoán đổi phase của hai ảnh, ảnh kết quả trông giống ảnh gốc có phase đó hơn là ảnh có magnitude

**Giải thích:** Các mô phỏng phòng thí nghiệm (hybrid images) lật tẩy được tầm quan trọng cốt lõi của không gian Pha (phase)[cite: 5]. Khi lấy phần biên độ của một bức ảnh này (ví dụ: Cheetah) chắp vá nhân chéo với phần góc pha của bức ảnh khác (ví dụ: ngựa vằn), sản phẩm hình thái IFFT được sinh ra cuối cùng sẽ hiển thị các sọc ngựa vằn, chứng tỏ góc pha là kẻ nắm giữ mã khóa bảo lưu cấu trúc và định hình sự nhận diện[cite: 5].

</details>

### Câu 255
Nguồn PDF: trang 35

Điều nào KHÔNG đúng về DFT?

- A. Là biến đổi thuận nghịch (invertible)
- B. Cho phép phân tích tần số
- C. Cho phép lọc ảnh dễ dàng hơn
- D. Luôn tốt hơn lọc trong miền không gian với mọi kernel

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** D. Luôn tốt hơn lọc trong miền không gian với mọi kernel

**Giải thích:** Dù giải quyết gọn ghẽ bài toán phân tích với ma trận kernel khổng lồ, DFT đòi hỏi sự cồng kềnh là phải thực thi 2 lượt chuyển đổi (Fourier thuận để sang tần số, Fourier nghịch để về lại hình ảnh)[cite: 5]. Với các hệ thống ứng dụng thời gian thực chỉ sử dụng những ô mask kernel siêu bé gọn nhẹ (như bộ dò góc $3\times3$ Sobel), việc lọc đè trực tiếp trong không gian điểm ảnh không gian (spatial) lại là lợi thế (nhanh hơn DFT)[cite: 5]. Do vậy, nói DFT luôn ưu việt với "mọi kernel" là một định kiến sai.

</details>

### Câu 256
Nguồn PDF: trang 35

Spectral analysis (phân tích phổ) của ảnh giúp phát hiện điều gì? (Chọn đúng nhất)

- A. Số lượng đối tượng trong ảnh
- B. Các tần số và hướng chủ đạo trong texture và cấu trúc ảnh
- C. Màu sắc của đối tượng
- D. Vị trí của đối tượng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Các tần số và hướng chủ đạo trong texture và cấu trúc ảnh

**Giải thích:** Việc mổ xẻ một bức ảnh bằng phân tích phổ sóng tần (Spectral Analysis) không nhằm đi tìm những thuộc tính cao cấp như mảng màu sắc hay ngữ nghĩa có bao nhiêu vật thể[cite: 5]. Đồ thị hình chóp tia nhô lên trong Fourier Spectrum hé lộ một cách rõ nét (detect orientation and features) về cấu hình phương vị và những họa tiết đứt gãy lặp lại, định vị các dải tần số chủ đạo đại diện cho kết cấu bề mặt ảnh (texture) (như vân tay, đường sọc)[cite: 5].

</details>

### Câu 257
Nguồn PDF: trang 35

Khi muốn làm sắc nét ảnh bằng High-pass filter trong miền tần số, cần thực hiện gì sau khi lọc?

- A. Lấy giá trị tuyệt đối
- B. Cộng kết quả với ảnh gốc (Unsharp Masking: f' = f + α × HP_filtered)
- C. Nhân với hằng số
- D. Áp dụng thêm một lần Low-pass

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Cộng kết quả với ảnh gốc (Unsharp Masking: f' = f + α × HP_filtered)

**Giải thích:** Chạy qua bộ lọc High-pass tần số, hình ảnh sẽ chỉ còn lại những nét gờ viền vỡ nát màu đen tối vì phần nền ánh sáng DC đã bị dìm chết[cite: 5]. Do đó, để tạo ra một bức ảnh thành phẩm sắc sảo trọn vẹn, người ta ứng dụng kĩ xảo Unsharp Masking: tiến hành phép cộng khuếch đại lớp cạnh vừa trích xuất đó ($HP\_filtered$) chập lên trên nền móng của khung ảnh gốc ban đầu[cite: 5].

</details>

### Câu 258
Nguồn PDF: trang 35

Biến đổi nào không được dùng trong JPEG compression (nén ảnh)?

- A. DCT
- B. Quantization
- C. Huffman coding
- D. FFT

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** D. FFT

**Giải thích:** Tiêu chuẩn nén ảnh kỹ thuật số phổ biến nhất JPEG được dệt nên bởi chuỗi ba bộ lọc: Biến đổi Cosine rời rạc (DCT) để nén tín hiệu thực; Lượng tử hóa mảng ma trận (Quantization) để lược bỏ tần số yếu; và nén từ điển (Huffman coding) cho dải bit[cite: 5]. Không hề có sự xuất hiện của hệ thống Fast Fourier Transform (FFT) do nó dính líu đến tính toán số phức không tối ưu dung lượng[cite: 5].

</details>

### Câu 259
Nguồn PDF: trang 35

Điều nào đúng về mối quan hệ giữa kích thước bộ lọc và miền tần số?

- A. Bộ lọc nhỏ trong không gian → dải thông rộng trong tần số
- B. Bộ lọc lớn trong không gian → dải thông rộng trong tần số
- C. Không có mối quan hệ
- D. Bộ lọc nhỏ → tần số cao, bộ lớn → tần số thấp

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Bộ lọc nhỏ trong không gian → dải thông rộng trong tần số

**Giải thích:** Hai miền này chia sẻ nguyên tắc không gian đảo nghịch (Scaling property). Một hàm hình chuông rất tù, chiếm diện tích cửa sổ trải rộng dàn trải (bộ lọc lớn) ở bề mặt không gian vật lý sẽ bị bóp nén lại thành một dải đỉnh chóp đâm vút hẹp ở miền tần số[cite: 5]. Trái lại, nếu ta vo viên bộ lọc đó thành một xung hạt bé xíu trên không gian 2D, khi chuyển vào thế giới Fourier nó sẽ nổ tung và trôi dạt phủ kín thành một băng dải thông rộng mênh mông (đồ thị dàn mỏng)[cite: 5].

</details>

### Câu 260
Nguồn PDF: trang 35

Phép nhân hai ảnh trong miền không gian tương đương với phép gì trong miền tần số?

- A. Nhân phổ của hai ảnh
- B. Convolution (tích chập) phổ của hai ảnh
- C. Cộng phổ của hai ảnh
- D. Không có phép tương đương

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Convolution (tích chập) phổ của hai ảnh

**Giải thích:** Định luật biến đổi Fourier tuân thủ tính thuận nghịch tuyệt đối trong lý thuyết Tích Chập (Convolution Theorem)[cite: 5]. Khi việc lấy Tích Chập trong miền thời gian/không gian song hành với Phép nhân (Multiplication) trong phổ tần số, thì phép toán được chiếu theo chiều ngược lại cũng phải đúng: Phép Nhân điểm của hai ma trận ảnh sẽ gây ra hiệu ứng đan chéo Tích Chập lên phổ năng lượng trong chiều Fourier[cite: 5].

</details>

### Câu 261
Nguồn PDF: trang 36

Khi hiển thị phổ Fourier của ảnh, tại sao tần số thấp thường hiển thị ở trung tâm?

- A. Vì đó là cách tính DFT
- B. Vì đã áp dụng fftshift để dịch thành phần DC về trung tâm, tiện cho quan sát
- C. Vì tần số thấp luôn nằm ở trung tâm
- D. Vì đây là quy ước tùy ý

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Vì đã áp dụng fftshift để dịch thành phần DC về trung tâm, tiện cho quan sát

**Giải thích:** Lõi tính toán mặc định của mô-đun DFT luôn đặt chỉ số tọa độ (0,0) (thành phần năng lượng lớn nhất DC) nằm vắt vẻo sát mép trái đỉnh cùng của khung nhìn, khiến ma trận bị chia làm 4 mảnh ảo ảnh[cite: 5]. Để người kỹ sư máy tính có một góc độ trung tâm trực diện quan sát được sự tỏa đều của hạt nhân ánh sáng, hệ thống phải thực thi một lệnh bắt buộc là `fftshift` nhằm hoán đổi 4 cụm khối, dịch chuyển đỉnh núi ánh sáng về vùng giữa màn hình[cite: 5].

</details>

### Câu 262
Nguồn PDF: trang 36

Điều nào đúng về Zero-padding trong FFT?

- A. Giảm chất lượng phổ
- B. Thêm zeros vào tín hiệu trước DFT để tăng độ phân giải phổ và tránh circular convolution
- C. Tăng noise
- D. Không ảnh hưởng đến kết quả

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Thêm zeros vào tín hiệu trước DFT để tăng độ phân giải phổ và tránh circular convolution

**Giải thích:** Tính hữu hạn của viền ảnh gây đứt đoạn và vỡ vụn vòng lặp vô tận của sóng trong chuỗi biến đổi IDFT Fourier, sinh ra hiện tượng wrap-around (nhân chập vòng - circular convolution) làm rách mép ảnh[cite: 5]. Thuật toán độn thêm một lớp viền pixel số 0 (Zero-padding) quanh chu vi ảnh thô trước khi ném vào FFT sẽ lấp đầy chỗ trống, phá vỡ liên kết vòng, và đóng vai trò nội suy để làm đặc điểm ảnh hiển thị, nâng cấp độ nét mịn của phổ[cite: 5].

</details>

### Câu 263
Nguồn PDF: trang 36

Ứng dụng nào sau đây dùng phân tích tần số Fourier? (Chọn tất cả đúng)

- A. Lọc nhiễu âm thanh
- B. Nén ảnh JPEG
- C. Phân tích texture trong ảnh
- D. Loại bỏ nhiễu tuần hoàn trong ảnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Lọc nhiễu âm thanh; B. Nén ảnh JPEG; C. Phân tích texture trong ảnh; D. Loại bỏ nhiễu tuần hoàn trong ảnh

**Giải thích:** Công cụ Fourier cung cấp nền móng cho các hệ thống viễn thông và số hóa[cite: 5]. Nó nắm giữ vai trò trái tim trong thuật toán san phẳng (Low-pass) để gọt giũa và Lọc nhiễu âm thanh, biến đổi ma trận để thu gọn nén định dạng JPEG, và cung cấp đồ thị cho kỹ thuật nhặt sao băng (Notch) nhằm phân tích hướng vân texture và loại bỏ nhiễu sóng sọc tuần hoàn ra khỏi bức ảnh vệ tinh[cite: 5].

</details>

### Câu 264
Nguồn PDF: trang 36

Điều nào đúng về việc dùng Fourier Transform trong phân tích âm nhạc?

- A. Cho thấy biên độ theo thời gian
- B. Cho thấy tần số (nốt nhạc) và cường độ của chúng trong tín hiệu âm nhạc
- C. Không thể dùng cho âm nhạc
- D. Chỉ phân tích được âm thanh đơn âm

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Cho thấy tần số (nốt nhạc) và cường độ của chúng trong tín hiệu âm nhạc

**Giải thích:** Âm nhạc là giao thoa phức tạp của đa tín hiệu[cite: 5]. Các hàm của Fourier Transform giải phẫu chuỗi dữ liệu rãnh âm thanh này không theo trục thời gian tuyến tính, mà bóc tách chúng thành các nấc phổ (Spectrum), giúp thợ chỉnh nhạc định vị được chính xác các sóng hertz ứng với tần số nốt nhạc riêng biệt cùng cường độ vọt lên của chúng (magnitudes)[cite: 5].

</details>

### Câu 265
Nguồn PDF: trang 36

Short-Time Fourier Transform (STFT) giải quyết hạn chế nào của DFT?

- A. DFT quá chậm
- B. DFT cho thấy tần số toàn cục nhưng không biết khi nào tần số đó xuất hiện; STFT phân tích tần số theo từng cửa sổ thời gian
- C. DFT không hoạt động với ảnh
- D. STFT chính xác hơn

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. DFT cho thấy tần số toàn cục nhưng không biết khi nào tần số đó xuất hiện; STFT phân tích tần số theo từng cửa sổ thời gian

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* STFT nhân tín hiệu với một cửa sổ cục bộ, tính Fourier của đoạn đó rồi trượt cửa sổ để thu phổ theo thời gian. Nhờ vậy có thể biết một thành phần tần số xuất hiện ở giai đoạn nào, khác với một DFT toàn đoạn chỉ tổng hợp các thành phần trên cả khoảng quan sát. Cửa sổ ngắn tăng khả năng định vị thời gian nhưng giảm phân giải tần số, còn cửa sổ dài tạo đánh đổi ngược lại; STFT không đơn giản là một DFT luôn chính xác hơn. Đối chiếu: [Short-Time Fourier Transform](https://docs.scipy.org/doc/scipy/reference/generated/scipy.signal.stft.html).

</details>

### Câu 266
Nguồn PDF: trang 36

DCT (Discrete Cosine Transform) khác DFT ở điểm chính nào?

- A. DCT chậm hơn DFT
- B. DCT chỉ dùng cosines (kết quả thực), không cần số phức; phù hợp nén ảnh
- C. DFT cho kết quả thực
- D. DCT không thể xử lý ảnh 2D

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. DCT chỉ dùng cosines (kết quả thực), không cần số phức; phù hợp nén ảnh

**Giải thích:** Thay vì bao hàm cả biến cố $sine$ sinh ra cấu trúc phần Ảo (số phức) như DFT gây lãng phí bộ nhớ, thuật toán Biến đổi Cosine rời rạc (DCT) được thiết kế tối giản chỉ sử dụng trục sóng chẵn $cosine$[cite: 5]. Sự gọn nhẹ này cho phép kết xuất ra một ma trận giá trị toàn là số thực (real number), đóng đinh vị trí ưu việt của DCT cho kỹ thuật gọt nén dữ liệu hình ảnh (Nén JPEG)[cite: 5].

</details>

### Câu 267
Nguồn PDF: trang 36

Khi phân tích texture của ảnh bằng Fourier, điều gì có thể nhận biết từ phổ?

- A. Màu sắc chủ đạo
- B. Hướng và tần số lặp của texture
- C. Số lượng đối tượng
- D. Vị trí của cạnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Hướng và tần số lặp của texture

**Giải thích:** Texture thường mang đặc tính là những mẫu vân rãnh (như sọc vằn, đường thẳng song song) phân bố dầy đặc[cite: 5]. Khi chụp bằng kính hiển vi Fourier, tính tuần hoàn lặp lại đó nảy sinh thành các chuỗi đốm sáng xa tâm[cite: 5]. Bằng cách đo đạc các đường tạo thành từ dãy đốm sáng này, hệ thống sẽ xác nhận được chính xác trục hướng chéo vuông góc (orientations) và mật độ nhịp độ (tần số) của cái texture đó trên ảnh thật[cite: 5].

</details>

### Câu 268
Nguồn PDF: trang 37

Trong nén JPEG, sau DCT, bước tiếp theo là gì?

- A. IDCT ngay lập tức
- B. Quantization (làm tròn các hệ số DCT về giá trị ít chính xác hơn)
- C. Zero-padding
- D. Gaussian filtering

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Quantization (làm tròn các hệ số DCT về giá trị ít chính xác hơn)

**Giải thích:** Để vắt kiệt dung lượng hình ảnh trong dây chuyền Nén JPEG, ngay sau khi bộ phận DCT khai thác ra ma trận tần số, toàn bộ ma trận này phải bị tống qua một màng lọc Lượng tử hóa (Quantization)[cite: 5]. Đây là bước hủy diệt thông tin (lossy), nó chia rải và làm tròn gọt đi các số liệu dư thừa thuộc hệ số tần số cao xuống mức ít chính xác, giúp triệt tiêu dung lượng để lưu mã bit[cite: 5].

</details>

### Câu 269
Nguồn PDF: trang 37

Bộ lọc Homomorphic (homomorphic filter) trong miền tần số được dùng để làm gì?

- A. Loại bỏ nhiễu tuần hoàn
- B. Chuẩn hóa chiếu sáng đồng đều qua ánh xạ log → lọc tần số → exp
- C. Phát hiện cạnh
- D. Tăng độ bão hòa màu

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Chuẩn hóa chiếu sáng đồng đều qua ánh xạ log → lọc tần số → exp

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* Mô hình homomorphic xem ảnh dương như tích của chiếu sáng và phản xạ, rồi lấy log để chuyển hai thành phần thành tổng. Dưới giả thiết chiếu sáng biến thiên chậm, lọc trong miền log giảm các thành phần tần số thấp tương ứng và giữ hoặc tăng chi tiết phản xạ trước khi lấy exp trở lại. B đúng về quy trình, nhưng đây là mô hình xấp xỉ: không thể bảo đảm loại mọi bóng hoặc làm chiếu sáng hoàn toàn đồng đều trong mọi cảnh. Đối chiếu: [homomorphic filtering](https://blogs.mathworks.com/steve/2013/06/25/homomorphic-filtering-part-1/).

</details>

### Câu 270
Nguồn PDF: trang 37

Ảnh hưởng của lọc Ideal High-pass trên ảnh là gì?

- A. Chỉ thấy vùng đồng nhất
- B. Chỉ thấy cạnh và chi tiết (vùng thay đổi nhanh), vùng phẳng về 0
- C. Ảnh tối đồng đều
- D. Không thay đổi

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Chỉ thấy cạnh và chi tiết (vùng thay đổi nhanh), vùng phẳng về 0

**Giải thích:** Do hình dáng đĩa thủng trung tâm, ma trận lọc thông cao Ideal High-pass Filter ($H_{HP}$) xén mất 100% cột sóng DC (tần số 0) tại nhân đồ thị[cite: 5]. Hệ quả là sau khi thu phóng lại (IFFT), những mảng không gian bầu trời yên ắng bị xóa sạch và rớt thẳng xuống vực hố đen (về 0), chỉ còn chừa lại bộ xương (chi tiết sắc nét và đường biên) đang phát sáng le lói nhợt nhạt và bị vây quanh bởi lớp sóng ringing tàn phá của nó[cite: 5].

</details>

### Câu 271
Nguồn PDF: trang 37

Khi đứng trước lựa chọn lọc trong miền không gian hay miền tần số, yếu tố nào ảnh hưởng đến quyết định?

- A. Loại ảnh (màu hay đen trắng)
- B. Kích thước kernel: kernel nhỏ → miền không gian nhanh hơn; kernel lớn → miền tần số nhanh hơn
- C. Chỉ màu sắc ảnh
- D. Chỉ tốc độ máy tính

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Kích thước kernel: kernel nhỏ → miền không gian nhanh hơn; kernel lớn → miền tần số nhanh hơn

**Giải thích:** Đây là một bài toán quyết định lựa chọn độ phức tạp giải thuật tối ưu[cite: 5]. Nếu bạn muốn xài một cái kính lúp (kernel) cực nhỏ bé (ví dụ $3\times3$), chạy tích chập thẳng hàng (convolution) trên mặt phẳng không gian (spatial) tốn cực kì ít sức kéo $O(N^2 K^2)$[cite: 5]. Nhưng khi kích thước ống kính (kernel $K$) phình khổng lồ, thuật toán tích chập bị quá tải, buộc ta phải kích hoạt đường truyền Fourier Frequency có tốc độ $O(N^2 \log N)$ để tính nhân ma trận[cite: 5].

</details>

### Câu 272
Nguồn PDF: trang 37

Phổ tần số của ảnh có cạnh nằm ngang sẽ có đặc điểm gì?

- A. Năng lượng tập trung ở tần số nằm dọc (perpendicular to the edge)
- B. Năng lượng phân bố đều
- C. Không thể phân tích
- D. Năng lượng ở tất cả hướng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Năng lượng tập trung ở tần số nằm dọc (perpendicular to the edge)

**Giải thích:** Bất kỳ dao động nhiễu hay đường ranh giới thẳng nào trên mặt ảnh vật lý đều phóng ra một vector biến thiên[cite: 5]. Trên màn hình phổ tần số, vệt tín hiệu phản hồi này (phân bổ năng lượng) sẽ không song hành mà bẻ góc đâm thẳng một đường vạch sáng vuông góc (perpendicular) cắt góc $90^\circ$ với hướng của đường vạch trong mặt phẳng không gian (nghĩa là viền ngang sẽ xé ra phổ dọc)[cite: 5].

</details>

### Câu 273
Nguồn PDF: trang 37

Trong ảnh số, "spatial frequency" cao có nghĩa là gì?

- A. Ảnh có nhiều pixel
- B. Có sự thay đổi cường độ nhanh và dày đặc trong ảnh (như texture mịn, cạnh sắc)
- C. Ảnh có kích thước lớn
- D. Ảnh có nhiều màu sắc

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Có sự thay đổi cường độ nhanh và dày đặc trong ảnh (như texture mịn, cạnh sắc)

**Giải thích:** Tần số trong nhiếp ảnh số (spatial frequency) là thước đo độ chập chùng của tín hiệu sáng[cite: 5]. Khái niệm Tần số cao (High spatial frequency) chỉ mức dao động lên xuống một cách điên loạn, liên tục (thay đổi nhanh) với chu kỳ vắn tắt của ma trận cường độ[cite: 5]. Chúng thường cấu trúc nên họa tiết vải (texture), các hạt sạn noise nhỏ và các nếp gấp đường biên gắt gao (cạnh sắc)[cite: 5].

</details>

### Câu 274
Nguồn PDF: trang 37

Bộ lọc Ideal Band-pass giữ lại gì?

- A. Tất cả tần số
- B. Chỉ các tần số nằm trong dải [f_low, f_high]
- C. Chỉ tần số thấp
- D. Chỉ tần số cao

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Chỉ các tần số nằm trong dải [f_low, f_high]

**Giải thích:** Bộ lọc thông dải lý tưởng (Ideal Band-pass filter) được miêu tả bởi một vùng ranh giới khuyên tròn như bánh Donut[cite: 5]. Bằng việc khoanh mốc và đánh dấu hai bức tường ranh giới tần số $f_{low}$ và $f_{high}$, màng lọc này khóa hoàn toàn (giá trị 0) tất cả các tín hiệu từ gốc tọa độ tới $f_{low}$ cũng như từ $f_{high}$ ra ngoài, và chỉ xả luồng (giá trị 1) cho những dải sóng dao động nằm gọn trong băng hẹp khe giữa (dải [f_low, f_high])[cite: 5].

</details>

### Câu 275
Nguồn PDF: trang 38

Khi nói phổ Fourier của ảnh là "hermitian symmetric," điều đó có nghĩa gì?

- A. Phổ đối xứng qua trục x
- B. F(-u,-v) = F*(u,v) (conjugate symmetric)
- C. Magnitude = Phase
- D. Phổ luôn thực

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. F(-u,-v) = F*(u,v) (conjugate symmetric)

**Giải thích:** Sự kiện đầu vào là một ma trận dữ liệu chỉ chứa các số thực (không mang thành phần ảo) tạo ra một ma trận Fourier $F(u,v)$ số phức bị ràng buộc[cite: 5]. Trạng thái bị "khóa" này được quy chuẩn hóa bằng thuật ngữ đối xứng Hermitian (Hermitian symmetric), trong đó thành phần ở tọa độ đối ngẫu âm $-u,-v$ luôn có giá trị liên hợp phức với thành phần ở $u,v$ ($F(-u,-v) = F^*(u,v)$), dẫn tới hiện tượng đối xứng nhân bản của phổ[cite: 5].

</details>

### Câu 276
Nguồn PDF: trang 38

Điều nào đúng về việc dùng Wavelet thay vì Fourier cho phân tích ảnh y tế?

- A. Fourier luôn tốt hơn
- B. Wavelet phù hợp hơn vì phân tích đa phân giải, phân tích cả tần số lẫn vị trí
- C. Wavelet chỉ dùng cho 1D
- D. Không có sự khác biệt

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Wavelet phù hợp hơn vì phân tích đa phân giải, phân tích cả tần số lẫn vị trí

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* Wavelet đa phân giải có thể giữ đồng thời cấu trúc lớn và chi tiết cục bộ trong ảnh, nhờ các hệ số xấp xỉ và chi tiết ở nhiều mức. Đặc tính này hữu ích khi nhiệm vụ cần định vị một mẫu texture hoặc ranh giới thay vì chỉ đo thành phần tần số toàn ảnh. B nêu một lý do chọn wavelet, không phải bằng chứng wavelet luôn tốt hơn Fourier trên mọi ảnh y tế; lựa chọn còn phụ thuộc mục tiêu, dữ liệu và phép đánh giá. Đối chiếu: [phân rã wavelet 2D](https://pywavelets.readthedocs.io/en/latest/ref/2d-dwt-and-idwt.html).

</details>

### Câu 277
Nguồn PDF: trang 38

Kết quả DFT của ảnh grayscale N×N có bao nhiêu giá trị phức?

- A. N
- B. N×N
- C. N²/2
- D. 2N

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. N×N

**Giải thích:** Phép toán của mô hình biến đổi DFT rời rạc hai chiều chuyển hóa từng nguyên tử pixel của ảnh gốc ($M \times N$) sang một thành phần phổ phức tương ứng[cite: 5]. Do tính chất nội suy toán học duy trì bảo toàn quy mô, một bức ảnh có định dạng vuông $N \times N$ sẽ xuất ra một mảng phổ Fourier chứa chính xác số ô cấu trúc $N \times N$ phần tử (giá trị phức)[cite: 5].

</details>

### Câu 278
Nguồn PDF: trang 38

Chức năng của Inverse Fourier Transform là gì trong pipeline xử lý ảnh miền tần số?

- A. Tính phổ biên độ
- B. Chuyển ảnh đã lọc từ miền tần số về miền không gian để xem kết quả
- C. Tăng resolution
- D. Phân tích tần số

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Chuyển ảnh đã lọc từ miền tần số về miền không gian để xem kết quả

**Giải thích:** Phép chuyển tiếp Fourier thuận kéo bức ảnh đi vào bóng tối của ma trận sóng để phân tích[cite: 5]. Ống dẫn cuối cùng của chuỗi phản ứng là bộ giải mã biến đổi Fourier ngược (Inverse Fourier Transform - IFFT), đảm nhận trọng trách tái lập và đảo ngược mọi thứ (dịch ngược mã phổ đã bị biến tấu lại) thành dạng pixel màu/xám dễ hiểu (miền không gian) để người dùng thưởng thức (xem kết quả)[cite: 5].

</details>

### Câu 279
Nguồn PDF: trang 38

Điều nào sau đây là ứng dụng của PCA trong nhận dạng khuôn mặt?

- A. Phân vùng khuôn mặt
- B. Eigenfaces: biểu diễn khuôn mặt bằng các principal components để nhận dạng hiệu quả
- C. Phát hiện vị trí khuôn mặt
- D. Lọc nhiễu trên khuôn mặt

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Eigenfaces: biểu diễn khuôn mặt bằng các principal components để nhận dạng hiệu quả

**Giải thích:** Thuật toán phân rã Phương sai lớn nhất PCA nén một bức ảnh 10.000 chiều xuống thành một khối dữ liệu nhỏ dại diện cho cấu trúc mặt (các điểm sáng tối cốt lõi)[cite: 5]. Hệ quy chiếu các vector trục chính (Principal Components) này vạch ra một không gian không mặt người, nơi mỗi khuôn mặt được mô phỏng bằng một tổ hợp các bóng ma mờ (Eigenfaces), cung cấp sức mạnh tuyệt đối để so khớp và nhận dạng người (Face Recognition)[cite: 5].

</details>

### Câu 280
Nguồn PDF: trang 38

Điều gì xảy ra khi áp dụng Gaussian Low-pass filter với σ rất lớn?

- A. Ảnh không thay đổi
- B. Ảnh gần như hoàn toàn mờ, chỉ còn màu trung bình
- C. Ảnh sắc nét hơn
- D. Noise tăng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Ảnh gần như hoàn toàn mờ, chỉ còn màu trung bình

**Giải thích:** Thông số độ lệch chuẩn $\sigma$ tỷ lệ nghịch với bán kính lọt khe của bộ lọc Gaussian trong miền tần số[cite: 5]. Khi ép giá trị $\sigma$ lên cực kì cao, bộ lọc co cụm và khép chặt lại như một lỗ kim chỉ chừa hở hạt đậu ở lõi (thành phần năng lượng DC của tâm phổ)[cite: 5]. Mọi vết đường viền đều bị chặn, khiến ảnh IFFT tái sinh ra chỉ còn lưu lại một bãi đầm lầy đục ngầu, mờ mịt hoàn toàn với sắc điệu màu trung bình của toàn khung cảnh[cite: 5].

</details>


## CHƯƠNG 4.1: Phát hiện biên

### Câu 281
Nguồn PDF: trang 38

Biên (edge) trong ảnh được định nghĩa là gì?

- A. Đường bao quanh toàn bộ ảnh
- B. Vị trí có sự thay đổi nhanh về cường độ sáng
- C. Vùng có cường độ sáng thấp nhất
- D. Ranh giới giữa màu đỏ và xanh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Vị trí có sự thay đổi nhanh về cường độ sáng

**Giải thích:** Biên là nơi cường độ ảnh biến thiên nhanh theo vị trí, chẳng hạn khi đường lấy mẫu đi từ nền tối sang đối tượng sáng. Vì vậy B mô tả dấu hiệu trên dữ liệu ảnh, không phải đường viền ngoài của cả khung hình hoặc chỉ một cặp màu cố định. Biến thiên đó có thể do vật thể, vật liệu hay chiếu sáng, nên một pixel tối nhất chưa đủ chứng minh có biên nếu các pixel xung quanh cũng tối tương tự. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 2, 6.

</details>

### Câu 282
Nguồn PDF: trang 39

Biên trong ảnh tồn tại do những nguyên nhân nào? (Chọn tất cả đúng)

- A. Sự thay đổi chiều sâu (depth discontinuity)
- B. Thay đổi hướng bề mặt
- C. Thay đổi reflectance (màu sắc vật liệu)
- D. Thay đổi điều kiện chiếu sáng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Sự thay đổi chiều sâu (depth discontinuity); B. Thay đổi hướng bề mặt; C. Thay đổi reflectance (màu sắc vật liệu); D. Thay đổi điều kiện chiếu sáng

**Giải thích:** Gián đoạn độ sâu có thể tạo ranh giới che khuất, còn đổi hướng bề mặt làm thay đổi lượng ánh sáng được phản xạ tới camera. Vật liệu hoặc màu bề mặt khác nhau cũng làm cường độ đổi, và bóng đổ hay thay đổi chiếu sáng có thể tạo biên ngay trên cùng một bề mặt. Vì thế cả A, B, C, D đều là nguyên nhân có thể tạo biên; không thể suy từ mọi biên quan sát được rằng có hai vật thể riêng. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 2.

</details>

### Câu 283
Nguồn PDF: trang 39

Loại biên nào có cường độ thay đổi đột ngột (như bậc thang)?

- A. Ramp edge
- B. Step edge
- C. Roof edge
- D. Line edge

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Step edge

**Giải thích:** Intensity profile của step edge chuyển từ một mức gần hằng sang mức khác trong một khoảng rất ngắn, giống hình bậc thang. Ramp edge có vùng chuyển tiếp trải rộng thành một đoạn dốc, còn roof edge tăng lên rồi giảm xuống tạo đỉnh. Phân biệt dựa trên hình dạng profile, không dựa vào vị trí trong ảnh; trong ảnh thực, step có thể bị làm mờ nên không còn là một bước nhảy lý tưởng hoàn toàn sắc. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 14.

</details>

### Câu 284
Nguồn PDF: trang 39

Tại vị trí biên dạng Step, đạo hàm bậc 1 có giá trị như thế nào?

- A. Bằng 0
- B. Đạt cực trị
- C. Âm
- D. Không xác định

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Đạt cực trị

**Giải thích:** Khi đi qua một step tăng cường độ, sai khác giữa các mẫu gần biên lớn hơn ở hai miền phẳng, nên đạo hàm bậc một có đáp ứng cực trị tại vùng biên. Với step giảm, đáp ứng đổi dấu, vì vậy nên xét cực trị của độ lớn thay vì cho rằng đạo hàm luôn dương. B được hiểu trong mô hình ảnh đã làm trơn hoặc đạo hàm rời rạc; bước nhảy liên tục lý tưởng có đạo hàm theo nghĩa phân phối chứ không phải một giá trị hữu hạn thông thường. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 6, 8, 15.

</details>

### Câu 285
Nguồn PDF: trang 39

Tại vị trí biên dạng Step, đạo hàm bậc 2 có giá trị như thế nào?

- A. Đạt cực trị dương
- B. Có zero-crossing (đi qua 0)
- C. Bằng 1
- D. Âm tất cả

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Có zero-crossing (đi qua 0)

**Giải thích:** Sau khi làm trơn một step, đạo hàm bậc một tăng tới đỉnh rồi giảm, nên đạo hàm bậc hai đổi dấu quanh vị trí đỉnh đó. Zero-crossing của đạo hàm bậc hai vì vậy là dấu hiệu định vị biên, thay vì chỉ chọn một cực trị dương hay mọi giá trị âm. Trong dữ liệu rời rạc, điểm đổi dấu có thể nằm giữa hai pixel và không cần có một mẫu bằng 0 chính xác; nhiễu cũng có thể tạo zero-crossing không phải biên thật. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 6, 22-23.

</details>

### Câu 286
Nguồn PDF: trang 39

Gradient của ảnh tại (x,y) biểu diễn điều gì?

- A. Giá trị cường độ tại (x,y)
- B. Hướng và độ lớn của sự thay đổi cường độ sáng lớn nhất
- C. Màu sắc tại (x,y)
- D. Khoảng cách đến biên gần nhất

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Hướng và độ lớn của sự thay đổi cường độ sáng lớn nhất

**Giải thích:** Gradient là vector gồm hai đạo hàm theo x và y, mô tả tốc độ biến thiên cường độ theo các hướng trên ảnh. Hướng vector cho hướng tăng cường độ nhanh nhất, còn độ lớn cho tốc độ tăng đó tại điểm đang xét. Vì vậy B chứa cả hướng và cường độ biến thiên; gradient không phải giá trị sáng gốc, màu của pixel hay một phép đo khoảng cách tới đường biên. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 9, 12.

</details>

### Câu 287
Nguồn PDF: trang 39

Gradient direction (hướng gradient) và hướng biên có mối quan hệ gì?

- A. Cùng hướng
- B. Vuông góc với nhau
- C. Song song với nhau
- D. Không có mối quan hệ

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Vuông góc với nhau

**Giải thích:** Dọc theo một biên cục bộ, cường độ thường thay đổi ít hơn so với khi đi từ phía này sang phía kia của biên. Gradient hướng theo biến thiên mạnh nhất nên nằm theo pháp tuyến, vuông góc với tiếp tuyến của đường biên. B mô tả quan hệ cục bộ trong mô hình biên mức cường độ; ở góc, giao điểm hoặc vùng nhiễu, hướng biên có thể không duy nhất hay không được ước lượng ổn định. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 12-13.

</details>

### Câu 288
Nguồn PDF: trang 39

Bộ lọc Robert (1965) dùng để làm gì?

- A. Làm trơn ảnh
- B. Xấp xỉ gradient bậc 1 (đầu tiên sử dụng cho phát hiện biên)
- C. Phát hiện vùng đồng nhất
- D. Tăng tương phản

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Xấp xỉ gradient bậc 1 (đầu tiên sử dụng cho phát hiện biên)

**Giải thích:** Roberts dùng các sai khác giữa pixel theo hai hướng chéo trong cửa sổ nhỏ để xấp xỉ đạo hàm bậc một. Từ hai đáp ứng có thể suy ra độ lớn biến thiên, nhờ đó phát hiện vị trí có khả năng là biên. Slide giới thiệu Robert filter với mốc 1965 như một bộ lọc xấp xỉ đạo hàm sớm; chức năng của nó không phải lấy trung bình để làm trơn hoặc xác định toàn bộ một vùng đồng nhất. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 10.

</details>

### Câu 289
Nguồn PDF: trang 39

Bộ lọc Sobel khác Prewitt ở điểm nào?

- A. Sobel dùng kernel 5×5
- B. Sobel cho trọng số cao hơn cho pixel trung tâm theo hướng ngang (tích Gaussian × gradient)
- C. Prewitt nhạy cảm hơn với nhiễu
- D. Sobel chỉ phát hiện biên ngang

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Sobel cho trọng số cao hơn cho pixel trung tâm theo hướng ngang (tích Gaussian × gradient)

**Giải thích:** Sobel kết hợp sai phân [1, 0, -1] với trọng số làm trơn [1, 2, 1] trên trục vuông góc, còn Prewitt dùng trọng số đều [1, 1, 1]. Vì vậy hàng hoặc cột giữa được nhấn mạnh hơn tùy kernel x hay y, chứ không chỉ theo một hướng ngang cố định. B là khác biệt cấu trúc được nhắm tới; trọng số làm trơn có dạng nhị thức xấp xỉ Gaussian, và C có thể đúng như một nhận xét trong một số điều kiện nhưng không phải bảo đảm tuyệt đối. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 10, 16-17.

</details>

### Câu 290
Nguồn PDF: trang 40

Bộ lọc Canny được coi là "optimal edge detector" vì lý do gì? (Chọn tất cả đúng)

- A. Good detection (ít bỏ sót và phát hiện nhầm)
- B. Good localization (biên được phát hiện gần vị trí thực)
- C. Minimal response (không có nhiều response cho 1 biên)
- D. Nhanh nhất trong các bộ phát hiện biên

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Good detection (ít bỏ sót và phát hiện nhầm); B. Good localization (biên được phát hiện gần vị trí thực); C. Minimal response (không có nhiều response cho 1 biên)

**Giải thích:** Good detection yêu cầu ít biên bị bỏ sót và ít phát hiện nhầm, good localization yêu cầu vị trí tìm được gần biên thật, còn single response hạn chế nhiều đáp ứng quanh cùng một biên. Ba tiêu chí A, B, C phản ánh đánh đổi về độ nhạy, vị trí và độ mỏng khi thiết kế Canny. 'Optimal' được đặt trong mô hình và tiêu chí cụ thể, không có nghĩa nhanh nhất hoặc luôn thắng mọi phương pháp trên mọi ảnh; D không thuộc bộ tiêu chí này. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 25.

</details>

### Câu 291
Nguồn PDF: trang 40

Các bước của Canny edge detector theo đúng thứ tự là?

- A. Gradient → Smoothing → NMS → Thresholding
- B. Gaussian smoothing → Gradient → Non-maximum suppression → Hysteresis thresholding
- C. Thresholding → Gradient → Smoothing → NMS
- D. NMS → Gradient → Smoothing → Thresholding

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Gaussian smoothing → Gradient → Non-maximum suppression → Hysteresis thresholding

**Giải thích:** Gaussian smoothing giảm nhiễu trước khi lấy đạo hàm, sau đó gradient cung cấp độ lớn và hướng biến thiên. NMS dùng hướng này để giữ cực đại cục bộ và làm mỏng dải đáp ứng, rồi hysteresis phân loại và theo dõi biên bằng hai ngưỡng. B giữ đúng quan hệ phụ thuộc giữa các bước: không thể thực hiện NMS theo hướng gradient khi chưa tính gradient, và thresholding quá sớm sẽ bỏ mất thông tin cần cho các bước sau. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 26-28.

</details>

### Câu 292
Nguồn PDF: trang 40

Non-maximum suppression (NMS) trong Canny detector làm gì?

- A. Loại bỏ tất cả biên yếu
- B. Giữ lại chỉ các điểm cực đại cục bộ dọc theo hướng gradient
- C. Làm mờ ảnh
- D. Chọn ngưỡng tự động

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Giữ lại chỉ các điểm cực đại cục bộ dọc theo hướng gradient

**Giải thích:** NMS so độ lớn gradient tại pixel với các vị trí lân cận theo hướng gradient, tức theo chiều đi qua biên. Nếu pixel không phải cực đại so với hai phía thì đáp ứng của nó bị loại, làm dải biên rộng co lại thành một đường mỏng. Thao tác này không loại mọi biên yếu: một cực đại có độ lớn thấp vẫn có thể qua NMS và được quyết định tiếp ở hysteresis; NMS cũng không tự chọn ngưỡng. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 26.

</details>

### Câu 293
Nguồn PDF: trang 40

Hysteresis thresholding trong Canny sử dụng hai ngưỡng T_low và T_high như thế nào?

- A. Chỉ dùng T_high để quyết định biên
- B. Pixel > T_high: biên mạnh; T_low < pixel < T_high: biên yếu (chỉ giữ nếu kết nối với biên mạnh)
- C. Pixel > T_low là biên
- D. Trung bình T_low và T_high làm ngưỡng duy nhất

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Pixel > T_high: biên mạnh; T_low < pixel < T_high: biên yếu (chỉ giữ nếu kết nối với biên mạnh)

**Giải thích:** Hai ngưỡng được áp dụng lên độ lớn gradient sau NMS, không phải trực tiếp lên cường độ ảnh gốc. Pixel trên ngưỡng cao là điểm biên chắc chắn; điểm giữa hai ngưỡng chỉ được giữ nếu có một chuỗi điểm biên yếu kết nối tới biên mạnh, còn điểm dưới ngưỡng thấp bị loại. B vì vậy giữ được phần yếu của đường biên nhưng tránh nhận mọi đáp ứng nhỏ; lấy trung bình hai ngưỡng sẽ làm mất cơ chế kết nối này. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 27.

</details>

### Câu 294
Nguồn PDF: trang 40

Tại sao Canny dùng Gaussian smoothing trước khi tính gradient?

- A. Để tăng tốc độ tính toán
- B. Để giảm nhiễu, tránh phát hiện biên nhầm từ noise
- C. Để tăng kích thước ảnh
- D. Để chuyển ảnh sang grayscale

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Để giảm nhiễu, tránh phát hiện biên nhầm từ noise

**Giải thích:** Đạo hàm phản ứng mạnh với những thay đổi nhanh, nên các dao động do nhiễu có thể tạo gradient lớn tương tự biên. Gaussian smoothing giảm những dao động nhỏ trước khi tính gradient, giúp hạn chế phát hiện nhầm trong khi vẫn giữ các cấu trúc ở scale phù hợp. B đúng về mục tiêu giảm nhiễu; làm trơn không làm ảnh tự chuyển sang grayscale hoặc tăng số pixel, và mức làm trơn quá mạnh có thể làm mất chi tiết thật. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 15, 19, 26.

</details>

### Câu 295
Nguồn PDF: trang 40

Khi σ của Gaussian trong Canny lớn, điều gì xảy ra?

- A. Phát hiện nhiều cạnh chi tiết hơn
- B. Phát hiện ít cạnh hơn, chỉ các cạnh lớn rõ ràng
- C. Không ảnh hưởng
- D. Chỉ phát hiện cạnh ngang

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Phát hiện ít cạnh hơn, chỉ các cạnh lớn rõ ràng

**Giải thích:** Sigma lớn làm Gaussian trung bình hóa trên phạm vi rộng hơn, giảm những biến thiên nhỏ và các biên ở scale tinh. Khi giữ cách đặt ngưỡng tương tự, kết quả thường còn các cấu trúc lớn rõ hơn và ít chi tiết hơn, đúng với ý B. Đây là xu hướng theo mức làm trơn, không phải định luật số biên luôn giảm trong mọi ảnh; vị trí và độ mạnh của biên cũng có thể thay đổi, còn hướng ngang không được ưu tiên riêng. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 15, 28-29.

</details>

### Câu 296
Nguồn PDF: trang 40

Hough Transform dùng để phát hiện gì?

- A. Điểm đặc trưng
- B. Các hình dạng hình học như đường thẳng, đường tròn
- C. Màu sắc
- D. Chuyển động

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Các hình dạng hình học như đường thẳng, đường tròn

**Giải thích:** Hough tìm các cấu trúc có thể biểu diễn bằng tham số, chẳng hạn đường thẳng theo rho, theta hoặc đường tròn theo tâm và bán kính. Mỗi điểm biên bỏ phiếu cho các bộ tham số tương thích, rồi các cực đại số phiếu biểu thị những hình dạng được hỗ trợ mạnh. Vì vậy B đúng, nhưng không phải mọi hình dạng tùy ý đều được phát hiện tự động: cần chọn mô hình tham số và không gian tìm kiếm phù hợp. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 30, 32, 37.

</details>

### Câu 297
Nguồn PDF: trang 41

Trong Hough Transform cho đường thẳng y = mx + b, mỗi điểm ảnh (xi, yi) tạo ra điều gì trong không gian Hough (m,b)?

- A. Một điểm
- B. Một đường thẳng b = yi - xi*m
- C. Một đường tròn
- D. Một mặt phẳng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Một đường thẳng b = yi - xi*m

**Giải thích:** Một điểm (xi, yi) thuộc đường y = m*x + b khi yi = m*xi + b, suy ra b = yi - xi*m. Khi m thay đổi, các cặp (m, b) thỏa điều kiện tạo thành một đường thẳng trong không gian tham số. Các điểm ảnh cùng nằm trên một đường thật sẽ tạo những đường tham số giao nhau tại cùng cặp (m, b), nên B mô tả đúng phép chuyển từ điểm ảnh sang tập giả thuyết đường thẳng. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 31-32.

</details>

### Câu 298
Nguồn PDF: trang 41

Tại sao dùng dạng cực ρ = x*cosθ + y*sinθ trong Hough Transform thay vì y = mx + b?

- A. Vì dễ tính hơn
- B. Vì dạng y=mx+b có m→∞ cho đường thẳng đứng; dạng cực xử lý mọi hướng
- C. Vì cho kết quả chính xác hơn
- D. Vì tiết kiệm bộ nhớ hơn

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Vì dạng y=mx+b có m→∞ cho đường thẳng đứng; dạng cực xử lý mọi hướng

**Giải thích:** Biểu diễn y = m*x + b không xử lý đường thẳng đứng bằng một hệ số góc hữu hạn, nên không thuận tiện để tạo một lưới tham số có giới hạn. Dạng rho = x*cos(theta) + y*sin(theta) dùng khoảng cách tới gốc và góc của pháp tuyến, mô tả được cả đường đứng lẫn đường ngang. B giải thích lý do đổi biểu diễn; độ chính xác vẫn phụ thuộc cách lượng tử hóa rho, theta, không tự tăng chỉ vì dùng tọa độ cực. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 34.

</details>

### Câu 299
Nguồn PDF: trang 41

Điểm tụ (accumulator peak) trong Hough Transform biểu diễn điều gì?

- A. Điểm đơn lẻ trong ảnh
- B. Đường thẳng (hoặc hình dạng) được nhiều điểm biên bỏ phiếu nhất
- C. Mức nhiễu trong ảnh
- D. Vùng tối nhất trong ảnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Đường thẳng (hoặc hình dạng) được nhiều điểm biên bỏ phiếu nhất

**Giải thích:** Mỗi ô accumulator đếm số điểm biên tương thích với một giả thuyết hình học, nên một peak là bộ tham số có nhiều phiếu hỗ trợ. Với Hough đường thẳng, bộ tham số ấy xác định cả một đường trong ảnh, không phải một pixel riêng lẻ. Peak mạnh chưa chắc là đối tượng mong muốn vì texture hoặc nhiễu có cấu trúc cũng có thể bỏ phiếu tập trung; thường cần ngưỡng phiếu và lọc thêm các kết quả. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 32-33, 37.

</details>

### Câu 300
Nguồn PDF: trang 41

RANSAC (Random Sample Consensus) được dùng để làm gì trong phát hiện đường thẳng?

- A. Tính gradient
- B. Fit mô hình hình học (đường thẳng) bền vững với outliers
- C. Làm mờ ảnh
- D. Cân bằng histogram

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Fit mô hình hình học (đường thẳng) bền vững với outliers

**Giải thích:** RANSAC thử các mô hình từ tập điểm nhỏ được lấy ngẫu nhiên rồi đánh giá mức đồng thuận của những điểm còn lại. Với đường thẳng, nó tìm giả thuyết được nhiều điểm nằm gần đường hỗ trợ, giảm tác động của các điểm không thuộc đường cần fit. Vì vậy B đúng về ước lượng hình học bền vững trước outliers; thuật toán không tính gradient hay cân bằng histogram và cũng không bảo đảm thành công nếu không lấy được mẫu tốt. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 38-42.

</details>

### Câu 301
Nguồn PDF: trang 41

Các bước của RANSAC theo đúng thứ tự là?

- A. Count inliers → Random sample → Fit → Iterate
- B. Random sample → Fit model → Count inliers → Iterate → Best model
- C. Fit → Sample → Count → Iterate
- D. Count → Fit → Sample → Iterate

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Random sample → Fit model → Count inliers → Iterate → Best model

**Giải thích:** RANSAC cần lấy mẫu trước để có dữ liệu tạo giả thuyết, fit mô hình từ mẫu đó rồi kiểm tra khoảng cách của các điểm còn lại để đếm inlier. Quá trình lặp lại trên những mẫu khác nhau và giữ mô hình có mức đồng thuận tốt nhất; sau đó có thể fit lại bằng toàn bộ inlier. B sắp xếp đúng luồng này, còn đếm inlier trước khi có mô hình là thiếu tiêu chuẩn để quyết định điểm nào phù hợp. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 40-45.

</details>

### Câu 302
Nguồn PDF: trang 41

RANSAC có ưu điểm gì so với Least Squares fitting?

- A. Nhanh hơn trong mọi trường hợp
- B. Bền vững với outliers (điểm ngoại lai); Least Squares bị ảnh hưởng nhiều bởi outliers
- C. Chính xác hơn
- D. Ít tham số hơn

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Bền vững với outliers (điểm ngoại lai); Least Squares bị ảnh hưởng nhiều bởi outliers

**Giải thích:** Least Squares trên toàn bộ dữ liệu tối thiểu tổng bình phương sai số, nên một số điểm nằm rất xa có thể kéo mạnh đường fit ra khỏi phần dữ liệu thật. RANSAC thay vì tin mọi điểm sẽ chọn tập đồng thuận và có thể dùng Least Squares chỉ trên tập inlier để tinh chỉnh. B vì vậy nêu lợi thế với outliers; nó không phải cam kết luôn nhanh hoặc chính xác hơn khi dữ liệu sạch, và vẫn cần các tham số như ngưỡng sai số, số vòng thử. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 39-40, 45-46.

</details>

### Câu 303
Nguồn PDF: trang 41

Trong RANSAC, "inlier" và "outlier" được phân biệt dựa trên gì?

- A. Khoảng cách từ điểm đến mô hình hiện tại so với threshold
- B. Màu sắc của điểm
- C. Vị trí của điểm trong ảnh
- D. Giá trị cường độ sáng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Khoảng cách từ điểm đến mô hình hiện tại so với threshold

**Giải thích:** Với một đường đang xét, tính sai số hình học của từng điểm, thường là khoảng cách vuông góc từ điểm tới đường. Điểm có sai số nhỏ hơn dung sai được xem là inlier, còn điểm vượt dung sai là outlier đối với giả thuyết ấy. A đúng vì nhãn này phụ thuộc mô hình và ngưỡng, không phải chỉ màu hoặc vị trí; một điểm có thể là inlier của giả thuyết khác nên không phải thuộc tính cố định của nó. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 42, 45.

</details>

### Câu 304
Nguồn PDF: trang 41

Điểm nào sau đây là nhược điểm của Hough Transform?

- A. Không phát hiện được đường thẳng
- B. Tốn bộ nhớ và thời gian tính toán cho accumulator array, nhất là với hình dạng nhiều tham số
- C. Không hoạt động với ảnh nhiễu
- D. Chỉ phát hiện được 1 đường thẳng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Tốn bộ nhớ và thời gian tính toán cho accumulator array, nhất là với hình dạng nhiều tham số

**Giải thích:** Accumulator rời rạc hóa các tham số và cần lưu số phiếu cho mọi ô được xét; thêm tham số hoặc tăng độ phân giải làm số ô tăng mạnh. Mỗi điểm biên cũng phải bỏ phiếu cho nhiều giả thuyết, tạo chi phí tính toán, đặc biệt với mô hình nhiều tham số. B vì vậy mô tả hạn chế chính; Hough vẫn có thể phát hiện nhiều đường và chịu được một mức nhiễu, nên các nhận định không tìm được đường hoặc không hoạt động khi có nhiễu đều quá tuyệt đối. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 32-33, 37.

</details>

### Câu 305
Nguồn PDF: trang 42

Hough Transform cho đường tròn cần bao nhiêu tham số?

- A. 1 (bán kính)
- B. 2 (tọa độ tâm)
- C. 3 (tâm x, tâm y, bán kính)
- D. 4

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** C. 3 (tâm x, tâm y, bán kính)

**Giải thích:** Đường tròn tổng quát thỏa (x - cx)² + (y - cy)² = r², với hai tọa độ tâm và một bán kính chưa biết. C vì vậy cho đúng ba tham số cần tìm; chỉ biết r không xác định được tâm, còn chỉ biết tâm không xác định được kích thước. Nếu bài toán đã cố định một trong các tham số thì không gian tìm kiếm có thể giảm, nhưng câu này nói tới đường tròn tổng quát. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 30, 37, về các cấu trúc tham số.

</details>

### Câu 306
Nguồn PDF: trang 42

LoG (Laplacian of Gaussian) tìm biên bằng cách nào?

- A. Tìm cực trị của đạo hàm bậc 1
- B. Tìm zero-crossing của đạo hàm bậc 2 sau khi làm mờ Gaussian
- C. Threshold trực tiếp gradient
- D. So sánh với giá trị threshold cố định

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Tìm zero-crossing của đạo hàm bậc 2 sau khi làm mờ Gaussian

**Giải thích:** LoG làm trơn ảnh bằng Gaussian rồi lấy Laplacian, tức tổng các đạo hàm bậc hai theo x và y. Ranh giới được tìm ở các vị trí đáp ứng đổi dấu, vì đạo hàm bậc hai của một chuyển tiếp cường độ đã làm trơn có zero-crossing gần tâm chuyển tiếp. B đúng về cơ chế; chỉ tìm mọi mẫu bằng 0 mà không xét đổi dấu hoặc độ mạnh có thể nhận cả vùng phẳng và nhiễu thành biên. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 22-24.

</details>

### Câu 307
Nguồn PDF: trang 42

Khi tăng kích thước kernel Gaussian trong Canny, điều gì xảy ra với số lượng biên phát hiện được?

- A. Tăng lên (phát hiện nhiều hơn)
- B. Giảm xuống (biên chi tiết nhỏ bị mất)
- C. Không thay đổi
- D. Phụ thuộc vào ngưỡng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Giảm xuống (biên chi tiết nhỏ bị mất)

**Giải thích:** B phản ánh trường hợp tăng cửa sổ Gaussian đi cùng tăng mức làm trơn, khiến những biến thiên nhỏ bị trung bình hóa và mất đáp ứng biên. **Lưu ý:** kích thước kernel và sigma không phải cùng một tham số; nếu giữ sigma cố định, tăng phần hỗ trợ của kernel chủ yếu giảm sai số cắt cụt và không bảo đảm số biên giảm. Số biên cuối còn phụ thuộc ngưỡng, nên đây là một xu hướng dưới thiết lập cụ thể chứ không phải kết luận tuyệt đối. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 28-29.

</details>

### Câu 308
Nguồn PDF: trang 42

Gradient magnitude được dùng để làm gì trong phát hiện biên?

- A. Xác định màu sắc biên
- B. Đo độ "mạnh" (strength) của biên tại mỗi điểm ảnh
- C. Xác định loại biên (step, ramp)
- D. Cân bằng histogram ảnh biên

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Đo độ "mạnh" (strength) của biên tại mỗi điểm ảnh

**Giải thích:** Độ lớn gradient kết hợp Gx và Gy thành một số đo mức biến thiên, thường dùng sqrt(Gx² + Gy²) hoặc xấp xỉ |Gx| + |Gy|. Vị trí có giá trị lớn là ứng viên biên mạnh vì cường độ thay đổi nhanh qua lân cận. B đúng về strength, nhưng độ lớn không tự cho hướng, loại hình step/ramp hoặc tên đối tượng; thông tin hướng phải tính riêng từ hai thành phần gradient. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 12, 17, 26.

</details>

### Câu 309
Nguồn PDF: trang 42

Bộ phát hiện biên Prewitt dùng để tính đạo hàm theo chiều nào?

- A. Chỉ theo chiều x
- B. Cả chiều x và chiều y (bằng 2 kernel riêng biệt)
- C. Chỉ theo chiều y
- D. Theo hướng diagonal

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Cả chiều x và chiều y (bằng 2 kernel riêng biệt)

**Giải thích:** Prewitt có hai mặt nạ: một lấy sai khác theo x kết hợp trung bình theo y, mặt nạ còn lại lấy sai khác theo y kết hợp trung bình theo x. Từ cả hai đáp ứng có thể tính vector gradient để nhận ra biên theo nhiều hướng. Vì vậy B đúng; dùng riêng một mặt nạ sẽ bỏ qua một thành phần biến thiên và không mô tả đầy đủ gradient ảnh, dù có thể đủ cho một bài toán chỉ tìm một hướng biên. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 10, 17.

</details>

### Câu 310
Nguồn PDF: trang 42

Điều gì xảy ra với Ramp edge (biên dạng dốc) khi lấy đạo hàm bậc 1?

- A. Cho xung (spike) tại vị trí biên
- B. Cho giá trị khác 0 dọc theo toàn bộ độ dốc (ramp)
- C. Cho 0 tại vị trí biên
- D. Không xác định

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Cho giá trị khác 0 dọc theo toàn bộ độ dốc (ramp)

**Giải thích:** Trong phần dốc tuyến tính của ramp, cường độ tăng hoặc giảm đều theo vị trí, nên đạo hàm bậc một khác 0 trên cả đoạn chuyển tiếp. Hai vùng phẳng trước và sau ramp có đạo hàm gần 0, khác với step sắc tạo đáp ứng tập trung ở một khoảng rất hẹp. B đúng vì biên bị trải rộng thành một dải; làm mỏng hoặc chọn vị trí đại diện cần thêm bước xử lý thay vì xem mọi pixel trên dốc như các biên riêng. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 6, 14.

</details>

### Câu 311
Nguồn PDF: trang 42

Canny edge detector tốt hơn Sobel đơn giản ở những điểm nào? (Chọn tất cả đúng)

- A. Sử dụng smoothing để giảm nhiễu
- B. NMS giúp tìm biên mỏng (thin edges)
- C. Hysteresis kết nối các đoạn biên bị ngắt
- D. Tự động chọn ngưỡng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Sử dụng smoothing để giảm nhiễu; B. NMS giúp tìm biên mỏng (thin edges); C. Hysteresis kết nối các đoạn biên bị ngắt

**Giải thích:** Làm trơn trước giúp giảm nhiễu, NMS giữ cực đại để làm mỏng đáp ứng, và hysteresis giữ những phần biên yếu có kết nối tới biên mạnh, nên A, B, C nêu các bước bổ sung của Canny. Cần hiểu C là theo dõi các ứng viên có sẵn, không phải tự vẽ qua khoảng trống bất kỳ. Sobel cũng có làm trơn theo một trục trong kernel, còn Canny chuẩn vẫn cần đặt hai ngưỡng nên D không phải đặc tính bắt buộc. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 16, 25-28.

</details>

### Câu 312
Nguồn PDF: trang 43

Trong không gian Hough (ρ, θ), một điểm tương ứng với điều gì trong không gian ảnh?

- A. Một pixel đơn lẻ
- B. Một đường thẳng trong không gian ảnh
- C. Một vùng ảnh
- D. Một đường cong

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Một đường thẳng trong không gian ảnh

**Giải thích:** Một điểm (rho, theta) chốt khoảng cách và hướng pháp tuyến của đường rho = x*cos(theta) + y*sin(theta). Tập mọi pixel (x, y) thỏa phương trình đó là một đường thẳng trong ảnh, nên B đúng. Chiều ánh xạ ngược cần phân biệt rõ: một pixel ảnh chưa chọn hướng sẽ bỏ phiếu cho một đường cong trong không gian Hough, còn một điểm tham số đã cố định mô tả một đường ảnh. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 31-34.

</details>

### Câu 313
Nguồn PDF: trang 43

Điều nào đúng về biên Roof (Roof edge)?

- A. Có cường độ thay đổi đột ngột một lần
- B. Có đỉnh nhọn (peak) trong intensity profile, đạo hàm bậc 2 có hai zero- crossing
- C. Tương tự Step edge
- D. Không có trong ảnh thực

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Có đỉnh nhọn (peak) trong intensity profile, đạo hàm bậc 2 có hai zero- crossing

**Giải thích:** Profile của roof edge tăng lên rồi giảm xuống tạo một đỉnh hẹp, đúng với phần đầu của B và hình trong slide. **Lưu ý:** số zero-crossing của đạo hàm bậc hai phụ thuộc profile và phép làm trơn: một đỉnh trơn kiểu Gaussian có thể có hai điểm đổi dấu ở hai phía, còn mái tam giác lý tưởng có đạo hàm suy rộng tại các chỗ gãy. Do đó không nên coi 'hai zero-crossing' là thuộc tính cố định của mọi roof edge. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 14; phân tích đạo hàm là kiến thức bổ sung.

</details>

### Câu 314
Nguồn PDF: trang 43

Vì sao biên không phải lúc nào cũng tương ứng với vật thể thực trong cảnh?

- A. Vì biên chỉ tồn tại trong ảnh nhân tạo
- B. Vì chiếu sáng thay đổi cũng tạo ra biên, không liên quan đến ranh giới vật thể
- C. Vì thuật toán phát hiện biên không chính xác
- D. Vì pixel không đủ độ phân giải

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Vì chiếu sáng thay đổi cũng tạo ra biên, không liên quan đến ranh giới vật thể

**Giải thích:** Một bóng đổ hoặc vùng chiếu sáng thay đổi có thể làm cường độ đổi mạnh dù bề mặt vật thể vẫn liên tục. Bộ phát hiện biên chỉ quan sát biến thiên của ảnh nên có thể đánh dấu ranh giới sáng/tối ấy giống như ranh giới giữa hai vật thể. B vì vậy nêu một nguyên nhân cơ bản, không chỉ lỗi thuật toán hoặc độ phân giải; muốn suy ra biên ngữ nghĩa cần thêm ngữ cảnh và mô hình của cảnh. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 2, 4.

</details>

### Câu 315
Nguồn PDF: trang 43

Bộ lọc nào phù hợp nhất để làm trơn ảnh trước khi phát hiện biên?

- A. Mean filter
- B. Gaussian filter
- C. Median filter
- D. Sobel filter

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Gaussian filter

**Giải thích:** Gaussian là lựa chọn chuẩn trong pipeline Canny vì làm trơn trước khi lấy đạo hàm và cho phép điều khiển scale bằng sigma. Nó giảm dao động nhiễu gây đáp ứng đạo hàm giả, đồng thời kết hợp thuận tiện với phép đạo hàm của nhân chập. B đúng trong ngữ cảnh này, không có nghĩa Gaussian luôn phù hợp nhất với mọi loại nhiễu: median có thể tốt hơn cho nhiễu xung, còn Sobel chủ yếu là bộ lọc đạo hàm chứ không phải bước làm trơn riêng. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 15-16, 26.

</details>

### Câu 316
Nguồn PDF: trang 43

Trong Canny, khi hai ngưỡng T_low và T_high quá gần nhau, điều gì xảy ra?

- A. Biên kết quả mỏng hơn
- B. Ít lợi ích của hysteresis, có thể bỏ sót biên liên tục
- C. Phát hiện nhiều biên sai hơn
- D. Không ảnh hưởng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Ít lợi ích của hysteresis, có thể bỏ sót biên liên tục

**Giải thích:** Khi hai ngưỡng gần nhau, khoảng độ lớn gradient được phân loại là biên yếu trở nên hẹp. Một đoạn biên có đáp ứng thấp hơn ngưỡng dưới sẽ bị loại ngay, dù nó nằm tiếp nối một đoạn mạnh, nên hysteresis ít có cơ hội giữ lại chuỗi biên yếu. Vì vậy B mô tả sự suy giảm lợi ích của ngưỡng kép; độ mỏng chủ yếu do non-maximum suppression quyết định, không phải do khoảng cách hai ngưỡng. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 26-27.

</details>

### Câu 317
Nguồn PDF: trang 43

Backward difference filter [0, 1, -1] tính đạo hàm hướng nào?

- A. Forward
- B. Backward (dùng pixel hiện tại và pixel trước)
- C. Central
- D. Diagonal

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Backward (dùng pixel hiện tại và pixel trước)

**Giải thích:** Theo quy ước stencil trong slide, backward difference lấy chênh lệch giữa mẫu hiện tại và mẫu đứng trước nó để xấp xỉ đạo hàm. Nó chỉ dùng thông tin ở một phía của vị trí đang xét, khác central difference dùng hai phía và forward difference dùng mẫu phía sau. Dấu của đáp ứng có thể đổi nếu triển khai bằng correlation thay cho convolution mà giữ nguyên kernel; tên backward nói về cặp vị trí lấy mẫu, không phải hướng chéo của biên. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 7-8.

</details>

### Câu 318
Nguồn PDF: trang 43

Central difference filter [1, 0, -1] có độ chính xác cao hơn Forward/Backward vì sao?

- A. Kernel nhỏ hơn
- B. Sai số xấp xỉ bậc 2 (O(h²)) thay vì bậc 1 (O(h))
- C. Không cần nhân chập
- D. Nhanh hơn

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Sai số xấp xỉ bậc 2 (O(h²)) thay vì bậc 1 (O(h))

**Giải thích:** Với hàm đủ trơn, công thức central difference chuẩn hóa là [f(x+h)-f(x-h)]/(2h); khai triển Taylor làm các số hạng sai số bậc một triệt tiêu, để lại sai số O(h²). Forward và backward difference một phía chỉ triệt tiêu ít số hạng hơn nên sai số cắt cụt là O(h). Kết luận B áp dụng cho xấp xỉ đạo hàm có chuẩn hóa và giả thiết trơn, không bảo đảm central difference luôn tốt hơn trên ảnh nhiễu hay tại điểm gián đoạn; kernel không chuẩn hóa trong câu chỉ thể hiện stencil, với dấu tùy quy ước nhân chập. *Kiến thức bổ sung (không có tham chiếu trong slide cho bậc sai số).* Tham khảo: [phân tích sai số sai phân của Langtangen và Linge](https://hplgit.github.io/fdm-book/doc/pub/book/sphinx/._book021.html).

</details>

### Câu 319
Nguồn PDF: trang 43

RANSAC cần bao nhiêu điểm tối thiểu để ước lượng đường thẳng?

- A. 1
- B. 2
- C. 3
- D. 4

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. 2

**Giải thích:** Hai điểm phân biệt xác định duy nhất một đường thẳng, nên mỗi lượt RANSAC có thể lấy mẫu tối thiểu gồm hai điểm để tạo giả thuyết. Một điểm chưa xác định được hướng đường thẳng; ba hoặc bốn điểm không cần thiết cho bước lấy mẫu tối thiểu. Sau đó thuật toán vẫn phải đánh giá nhiều điểm còn lại để tìm inliers và có thể ước lượng lại đường thẳng bằng toàn bộ tập inliers. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 40-42.

</details>

### Câu 320
Nguồn PDF: trang 44

Điều nào đúng về Sobel filter cho gradient theo chiều x (Gx)?

- A. Kernel Gx = [[1,0,-1],[2,0,-2],[1,0,-1]]
- B. Gx phát hiện biên dọc (vertical edges)
- C. Cả A và B đều đúng
- D. Chỉ A đúng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** C. Cả A và B đều đúng

**Giải thích:** Kernel đã cho lấy hiệu giữa các cột bên trái và bên phải, đồng thời dùng trọng số 1-2-1 để làm trơn theo chiều y. Vì cường độ thay đổi theo x khi đi ngang qua một biên dọc, Gx có đáp ứng mạnh với loại biên này. Do đó cả A và B đúng, chọn C; dấu của Gx phụ thuộc chiều tương phản và quy ước convolution, nhưng không đổi kết luận về hướng biên được nhấn mạnh. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 10-11, 16.

</details>

### Câu 321
Nguồn PDF: trang 44

Tại sao biên thường được phát hiện trước khi thực hiện các bước phân tích cao hơn?

- A. Vì biên tiêu tốn nhiều bộ nhớ
- B. Vì biên chứa thông tin cấu trúc quan trọng của cảnh, giúp phân vùng và nhận dạng đối tượng
- C. Vì biên dễ tính toán
- D. Vì biên là yêu cầu bắt buộc

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Vì biên chứa thông tin cấu trúc quan trọng của cảnh, giúp phân vùng và nhận dạng đối tượng

**Giải thích:** Biên biểu diễn những thay đổi cường độ có thể liên quan đến hình dạng, ranh giới và cấu trúc hình học trong cảnh. Bản đồ biên vì thế cung cấp đầu vào hữu ích cho phân vùng, tìm đường thẳng hoặc nhận dạng hình dạng ở các bước sau. B nêu đúng vai trò thông tin của biên; phát hiện biên không phải yêu cầu bắt buộc cho mọi pipeline, vì nhiều hệ thống nhận dạng có thể học trực tiếp từ ảnh. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 2, 4; `IT5409 L1-2-IntroImageFormation.pdf`, trang 3.

</details>

### Câu 322
Nguồn PDF: trang 44

Bức tranh hang động Chauvet (30,000 năm trước) liên quan gì đến nghiên cứu thị giác?

- A. Không liên quan
- B. Minh chứng rằng con người từ cổ đại đã có khả năng nhận dạng hình dạng từ đường biên đơn giản (line drawings)
- C. Nghiên cứu về màu sắc
- D. Liên quan đến thị giác lập thể

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Minh chứng rằng con người từ cổ đại đã có khả năng nhận dạng hình dạng từ đường biên đơn giản (line drawings)

**Giải thích:** Slide dùng hình vẽ hang động để minh họa rằng các nét đường có thể truyền tải hình dạng đối tượng ngay khi không có ảnh màu hay bề mặt đầy đủ. Ý nghĩa đối với bài học là thông tin cấu trúc trong line drawing đủ giúp người xem nhận ra nhiều đối tượng, tương ứng với B. Đây là minh họa về biểu diễn hình dạng, không phải bằng chứng trực tiếp về một cơ chế thần kinh cụ thể; mốc niên đại trong câu và cách ghi trên slide không hoàn toàn giống nhau nên không dùng chúng để suy luận tuổi khảo cổ chính xác. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 3-4.

</details>

### Câu 323
Nguồn PDF: trang 44

Trong phát hiện biên, Sobel cho kết quả về gì?

- A. Biên nhị phân trực tiếp
- B. Gradient magnitude và direction tại mỗi pixel
- C. Danh sách tọa độ biên
- D. Phổ tần số biên

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Gradient magnitude và direction tại mỗi pixel

**Giải thích:** Hai phép lọc Sobel theo x và y trước hết tạo ra các thành phần đạo hàm Gx và Gy tại từng pixel. Từ chúng ta tính được độ lớn gradient, chẳng hạn sqrt(Gx²+Gy²), và hướng gradient, thường bằng atan2(Gy,Gx), nên B là thông tin đặc trưng mà Sobel cung cấp. Muốn có bản đồ biên nhị phân còn phải thêm ngưỡng hoặc các bước xử lý khác; Sobel tự nó không xuất danh sách tọa độ biên hay phổ Fourier. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 9-12, 17.

</details>

### Câu 324
Nguồn PDF: trang 44

Accumulator array trong Hough Transform có kích thước phụ thuộc vào gì?

- A. Kích thước ảnh đầu vào
- B. Số tham số và độ phân giải của không gian tham số
- C. Số điểm biên
- D. Kích thước kernel

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Số tham số và độ phân giải của không gian tham số

**Giải thích:** Mỗi tham số của mô hình tạo một trục trong accumulator, còn độ phân giải quyết định số ô trên trục đó. Với đường thẳng dạng (rho, theta), số ô là số mức rho nhân số mức theta; giảm kích thước bin làm tăng bộ nhớ và độ chính xác lượng tử hóa. Kích thước ảnh có thể ảnh hưởng phạm vi rho, nhưng yếu tố mô tả trực tiếp cấu trúc accumulator là số tham số và cách rời rạc hóa chúng, nên chọn B. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 32-34, 37.

</details>

### Câu 325
Nguồn PDF: trang 44

Tìm "vanishing point" (điểm tụ) trong ảnh kiến trúc dùng kỹ thuật nào?

- A. Phát hiện màu sắc
- B. Hough Transform để phát hiện đường thẳng, sau đó tìm điểm giao của chúng
- C. Phân vùng ảnh
- D. Nhận dạng khuôn mặt

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Hough Transform để phát hiện đường thẳng, sau đó tìm điểm giao của chúng

**Giải thích:** Trong mô hình phối cảnh, ảnh của một nhóm đường thẳng song song trong không gian thường hội tụ về một điểm tụ chung. Có thể dùng Hough để lấy các đường thẳng ứng viên rồi tìm điểm giao hoặc điểm được nhiều đường cùng hỗ trợ, thay vì suy ra điểm tụ từ màu sắc. B mô tả một pipeline hình học hợp lý; trên ảnh nhiễu cần gom đúng nhóm hướng và ước lượng giao điểm robust, vì không phải mọi đường trong tòa nhà đều chung một điểm tụ. *Kiến thức bổ sung (không có tham chiếu trong slide cho toàn bộ pipeline tìm điểm tụ).*

</details>

### Câu 326
Nguồn PDF: trang 44

Điều nào đúng về so sánh giữa RANSAC và MSAC (M-estimator SAmple Consensus)?

- A. MSAC không liên quan đến RANSAC
- B. MSAC là biến thể của RANSAC với hàm cost khác, ít nhạy cảm với threshold hơn
- C. MSAC luôn chậm hơn
- D. Chúng hoàn toàn giống nhau

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. MSAC là biến thể của RANSAC với hàm cost khác, ít nhạy cảm với threshold hơn

**Giải thích:** MSAC vẫn sinh mô hình bằng lấy mẫu như RANSAC, nhưng đánh giá mô hình bằng tổng sai số được chặn thay vì chỉ đếm điểm nằm trong ngưỡng. Với residual r và ngưỡng t, dạng cost thường dùng là tổng min(r²,t²), nên hai mô hình có cùng số inliers vẫn có thể được phân biệt nhờ mức khớp của các inliers. B đúng về quan hệ biến thể và hàm cost; phần 'ít nhạy cảm với threshold hơn' là xu hướng trong một số tình huống, không có nghĩa MSAC không cần ngưỡng hoặc luôn ít nhạy hơn với mọi dữ liệu. *Kiến thức bổ sung (không có tham chiếu trong slide).* Tham khảo: [Torr và Zisserman, phần MSAC trong nghiên cứu robust estimation](https://www.robots.ox.ac.uk/~vgg/publications/2000/Torr00/torr00.pdf).

</details>

### Câu 327
Nguồn PDF: trang 45

Hough Transform cho đường tròn cần accumulator có bao nhiêu chiều?

- A. 1D
- B. 2D
- C. 3D (cx, cy, r)
- D. 4D

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** C. 3D (cx, cy, r)

**Giải thích:** Một đường tròn chưa biết được xác định bởi hai tọa độ tâm cx, cy và bán kính r. Hough cổ điển cho đường tròn phải cộng phiếu cho các bộ ba tham số này, vì một điểm biên có thể thuộc nhiều đường tròn với tâm và bán kính khác nhau. Vì vậy không gian accumulator là 3D trong bài toán tổng quát của câu hỏi; nếu cố định bán kính thì chỉ còn hai tham số tâm. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 30, 37-38.

</details>

### Câu 328
Nguồn PDF: trang 45

Khi áp dụng Canny với ngưỡng T_high quá cao, điều gì xảy ra?

- A. Phát hiện quá nhiều biên sai
- B. Bỏ sót nhiều biên thực
- C. Biên dày hơn
- D. Nhiều biên yếu được giữ lại

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Bỏ sót nhiều biên thực

**Giải thích:** T_high quyết định điểm nào đủ mạnh để làm hạt giống cho quá trình truy vết biên bằng hysteresis. Khi nó quá cao, nhiều biên thực không có điểm nào đạt ngưỡng mạnh, nên cả các đoạn yếu nối với chúng cũng có thể bị loại. Điều này gây bỏ sót biên, chọn B; tăng ngưỡng trên không làm biên dày thêm và cũng không tự động giữ được nhiều điểm yếu hơn. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 27-29.

</details>

### Câu 329
Nguồn PDF: trang 45

Điều nào là thách thức chính của phát hiện biên trong ảnh thực?

- A. Biên quá rõ ràng
- B. Nhiễu, thay đổi chiếu sáng, texture phức tạp tạo ra biên giả
- C. Ảnh quá nhỏ
- D. Kernel quá lớn

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Nhiễu, thay đổi chiếu sáng, texture phức tạp tạo ra biên giả

**Giải thích:** Các bộ phát hiện biên dựa vào biến thiên cường độ, nhưng biến thiên đó không chỉ xuất hiện ở ranh giới đối tượng. Nhiễu gây dao động cục bộ, bóng hoặc thay đổi chiếu sáng tạo chênh lệch sáng tối, còn texture tạo nhiều nét bên trong cùng một bề mặt. B vì thế nêu đúng khó khăn của ảnh thực: biên đo được có thể là biên cường độ thật nhưng không phải ranh giới đối tượng mà tác vụ cần tìm. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 2, 14-15.

</details>

### Câu 330
Nguồn PDF: trang 45

Trong thị giác thần kinh (neural visual system), tế bào thần kinh trong vỏ não thị giác (visual cortex) phát hiện điều gì?

- A. Màu sắc thuần túy
- B. Các biên và hướng cụ thể (orientation-selective cells, Hubel & Wiesel 1960s)
- C. Chuyển động
- D. Độ sâu

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Các biên và hướng cụ thể (orientation-selective cells, Hubel & Wiesel 1960s)

**Giải thích:** Ví dụ Hubel và Wiesel trong bài học nhấn mạnh các tế bào chọn lọc hướng: đáp ứng của chúng phụ thuộc hướng và vị trí của nét hoặc biên trong trường tiếp nhận. Điều này liên hệ trực tiếp với việc dùng các bộ lọc theo hướng để mô tả cấu trúc ảnh, nên B là đáp án được nhắm tới. Không nên hiểu câu này là mọi tế bào vỏ não thị giác chỉ phát hiện biên, hay hệ thị giác không xử lý màu, chuyển động và độ sâu; phát biểu chỉ nói đến lớp đáp ứng chọn lọc hướng được nêu trong ví dụ. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 3.

</details>

### Câu 331
Nguồn PDF: trang 45

Gradient ảnh được tính theo hướng nào thường cho phản ứng mạnh nhất với biên dọc?

- A. Theo chiều y (Gy)
- B. Theo chiều x (Gx)
- C. Theo cả x và y như nhau
- D. Theo đường chéo

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Theo chiều x (Gx)

**Giải thích:** Đi qua một biên dọc theo chiều ngang sẽ gặp thay đổi cường độ lớn, nên đạo hàm theo x có trị tuyệt đối lớn. Di chuyển theo y dọc theo một biên dọc lý tưởng lại không đổi cường độ, nên Gy nhỏ hoặc bằng không. Vì thế chọn Gx ở B; hướng gradient là pháp tuyến của biên, không phải hướng chạy dọc theo đường biên. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 11-12.

</details>

### Câu 332
Nguồn PDF: trang 45

Điều nào KHÔNG đúng về Canny edge detector?

- A. Dùng Gaussian smoothing
- B. Thực hiện non-maximum suppression
- C. Chỉ dùng 1 ngưỡng
- D. Thực hiện hysteresis thresholding

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** C. Chỉ dùng 1 ngưỡng

**Giải thích:** Canny chuẩn dùng hai ngưỡng để phân biệt điểm mạnh, điểm yếu và điểm bị loại. Sau đó hysteresis chỉ giữ điểm yếu có đường nối qua các điểm biên tới một điểm mạnh, nên phát biểu 'chỉ dùng 1 ngưỡng' là sai. Gaussian smoothing và non-maximum suppression đều là bước có thật trong pipeline, vì vậy A, B và D không phải lựa chọn cần tìm trong câu hỏi phủ định này. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 26-27.

</details>

### Câu 333
Nguồn PDF: trang 45

Tại sao cần đến "Hysteresis Thresholding" trong Canny?

- A. Để tăng tốc độ
- B. Để kết nối các đoạn biên bị gián đoạn do noise, tạo biên liên tục
- C. Để cân bằng histogram
- D. Để giảm kích thước ảnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Để kết nối các đoạn biên bị gián đoạn do noise, tạo biên liên tục

**Giải thích:** Đáp ứng gradient dọc một biên thực có thể lúc mạnh lúc yếu do nhiễu hoặc độ tương phản thay đổi. Hysteresis giữ các đoạn yếu nếu chúng nối được với đoạn mạnh, thay vì xóa mọi điểm dưới một ngưỡng cao duy nhất, nhờ đó biên được bảo toàn liên tục hơn. B đúng theo cơ chế này, nhưng thuật toán không tự vẽ thêm đường qua một khoảng trống tùy ý nơi mọi pixel đã bị loại; nó truy vết các ứng viên biên còn tồn tại sau NMS và ngưỡng dưới. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 26-27.

</details>

### Câu 334
Nguồn PDF: trang 46

Biên Canny cho kết quả biên dày hay mỏng?

- A. Biên dày (thick)
- B. Biên mỏng (thin), 1 pixel
- C. Phụ thuộc vào threshold
- D. Không xác định

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Biên mỏng (thin), 1 pixel

**Giải thích:** Canny dùng non-maximum suppression để chỉ giữ đỉnh đáp ứng khi xét ngang qua biên, làm dải gradient dày co về một đường mảnh. Vì vậy kết quả chuẩn được mô tả là biên mỏng, thường rộng một pixel, đúng với B. '1 pixel' là mục tiêu và mô tả điển hình chứ không phải bảo đảm hình học tuyệt đối tại mọi góc, chỗ giao nhau hay cách xử lý giá trị bằng nhau; ngưỡng chủ yếu quyết định điểm nào được giữ. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 25-27.

</details>

### Câu 335
Nguồn PDF: trang 46

Điều nào đúng về ứng dụng Hough Transform trong nhận dạng biển số xe?

- A. Phát hiện vị trí ký tự
- B. Phát hiện cạnh của biển số (hình chữ nhật) để định vị biển số
- C. Nhận dạng ký tự
- D. Phân loại biển số

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Phát hiện cạnh của biển số (hình chữ nhật) để định vị biển số

**Giải thích:** Sau khi lấy biên, Hough đường thẳng có thể tìm các cạnh dài tạo thành khung biển số và dùng quan hệ hình học của chúng để đề xuất vùng biển số. Đây là bước định vị, còn đọc từng ký tự cần các bước tách ký tự hoặc mô hình OCR riêng. Do đó B phù hợp với vai trò của Hough trong pipeline này; khung có thể bị nghiêng do phối cảnh và cần kiểm tra tỷ lệ, vị trí hoặc tính nhất quán của các cạnh để tránh nhầm với hình chữ nhật khác. *Kiến thức bổ sung (không có tham chiếu trong slide cho pipeline nhận dạng biển số).*

</details>

### Câu 336
Nguồn PDF: trang 46

RANSAC dừng lại khi nào?

- A. Khi tìm được đúng 2 inliers
- B. Khi số inliers vượt ngưỡng hoặc sau số vòng lặp tối đa
- C. Khi không còn điểm nào để lấy mẫu
- D. Sau 1 vòng lặp

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Khi số inliers vượt ngưỡng hoặc sau số vòng lặp tối đa

**Giải thích:** RANSAC thử nhiều mẫu nhỏ vì một mẫu bất kỳ có thể chứa outliers và cho mô hình sai. Có thể dừng khi đạt mức đồng thuận yêu cầu hoặc khi dùng hết số lượt cho phép; số lượt cũng có thể được cập nhật theo tỷ lệ inliers và xác suất thành công mong muốn. B nêu hai điều kiện dừng thông dụng, không phải bảo đảm đã tìm được mô hình đúng tuyệt đối; hai điểm chỉ đủ tạo đường thẳng giả thuyết, chưa đủ kiểm chứng nó. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 40, 44-45.

</details>

### Câu 337
Nguồn PDF: trang 46

Bộ phát hiện góc Harris (Harris Corner Detector) liên quan đến phát hiện biên như thế nào?

- A. Là bộ phát hiện biên tốt nhất
- B. Phát hiện góc (corner) - nơi giao của hai hoặc nhiều biên, quan trọng trong feature detection
- C. Thay thế cho Canny
- D. Không liên quan

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Phát hiện góc (corner) - nơi giao của hai hoặc nhiều biên, quan trọng trong feature detection

**Giải thích:** Harris đánh giá sự thay đổi của một cửa sổ ảnh khi dịch theo các hướng, thông qua ma trận cấu trúc xây dựng từ gradient. Trên một biên, thường chỉ có một hướng biến thiên mạnh; ở một góc, cả hai trị riêng của ma trận đều lớn nên cửa sổ thay đổi đáng kể theo nhiều hướng. B mô tả đúng vai trò phát hiện góc dùng làm đặc trưng, nhưng Harris không cần tìm giao điểm tường minh của các biên và không thay thế Canny để xuất toàn bộ đường biên. *Kiến thức bổ sung (không có tham chiếu trong slide).* Tham khảo: [OpenCV, Harris Corner Detection](https://docs.opencv.org/4.x/dc/d0d/tutorial_py_features_harris.html).

</details>

### Câu 338
Nguồn PDF: trang 46

Điều nào đúng về Sobel vs Roberts filter?

- A. Roberts là 3×3, Sobel là 2×2
- B. Roberts là 2×2 (đạo hàm theo đường chéo), Sobel là 3×3 (ít nhiễu hơn)
- C. Roberts chính xác hơn với noise
- D. Chúng giống nhau hoàn toàn

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Roberts là 2×2 (đạo hàm theo đường chéo), Sobel là 3×3 (ít nhiễu hơn)

**Giải thích:** Roberts dùng các sai phân trên cửa sổ 2×2 theo hai hướng chéo, trong khi Sobel dùng hai kernel 3×3. Thành phần làm trơn 1-2-1 của Sobel giúp giảm ảnh hưởng của dao động nhiễu trước khi lấy sai phân, nên thường ổn định hơn Roberts trong điều kiện so sánh tương tự. B đúng về cấu trúc và xu hướng chống nhiễu; không nên diễn giải thành Sobel luôn chính xác hơn trong mọi ảnh, vì scale, kiểu nhiễu và yêu cầu định vị cũng ảnh hưởng kết quả. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 10, 16.

</details>

### Câu 339
Nguồn PDF: trang 46

Intensity profile của ảnh là gì?

- A. Histogram mức xám
- B. Biểu diễn giá trị cường độ pixel dọc theo một đường trên ảnh
- C. Phổ Fourier
- D. Gradient magnitude

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Biểu diễn giá trị cường độ pixel dọc theo một đường trên ảnh

**Giải thích:** Intensity profile lấy lần lượt giá trị cường độ tại các vị trí nằm trên một đường trong ảnh và biểu diễn chúng theo tọa độ dọc đường đó. Nó giữ thứ tự không gian, nên ta có thể thấy một bước nhảy sáng tối hoặc đoạn chuyển tiếp và xác định nơi gradient lớn. Histogram chỉ đếm tần suất mức xám mà không giữ vị trí, còn gradient là đạo hàm của profile chứ không phải bản thân profile; vì vậy chọn B. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 5-6.

</details>

### Câu 340
Nguồn PDF: trang 46

Tại sao thị giác người dễ nhận ra đối tượng từ line drawing (chỉ có đường biên)?

- A. Vì line drawing có màu sắc phong phú
- B. Vì biên chứa đủ thông tin hình dạng để não nhận dạng
- C. Vì line drawing luôn đơn giản hơn
- D. Vì mắt không thể nhận biết màu sắc

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Vì biên chứa đủ thông tin hình dạng để não nhận dạng

**Giải thích:** Một hình vẽ đường nét có thể giữ đường bao, các góc và quan hệ giữa những bộ phận đặc trưng của đối tượng. Những thông tin hình dạng này giúp người xem nhận ra nhiều đối tượng dù đã bỏ màu sắc và chi tiết bề mặt, nên B giải thích đúng ví dụ trong bài học. Tuy nhiên, 'đủ thông tin' chỉ đúng với nhiều trường hợp minh họa chứ không phải mọi đối tượng: có những vật cần màu, texture hoặc ngữ cảnh để phân biệt. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 3-4.

</details>

### Câu 341
Nguồn PDF: trang 46

Điểm yếu của LoG (Laplacian of Gaussian) so với Canny là gì?

- A. LoG không phát hiện được biên
- B. LoG nhạy cảm hơn với noise và không có cơ chế kết nối biên như hysteresis
- C. LoG chậm hơn
- D. LoG không hoạt động với ảnh màu

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. LoG nhạy cảm hơn với noise và không có cơ chế kết nối biên như hysteresis

**Giải thích:** LoG làm trơn Gaussian rồi tìm zero-crossing của đạo hàm bậc hai, còn Canny dùng đỉnh gradient kết hợp NMS và hysteresis. Đạo hàm bậc hai nhạy với dao động còn lại, và zero-crossing riêng lẻ không có quy tắc giữ chuỗi biên yếu nối tới biên mạnh như Canny, nên B nêu khác biệt quan trọng. Tuy vậy LoG đã có bước Gaussian chứ không phải Laplacian thô; mức nhạy nhiễu tương đối còn phụ thuộc sigma, ngưỡng và triển khai, không có thứ hạng tuyệt đối cho mọi cấu hình. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 22-27.

</details>

### Câu 342
Nguồn PDF: trang 47

Marr và Hildreth (1980) đề xuất dùng LoG vì lý do gì?

- A. Nhanh hơn Canny
- B. LoG mô phỏng cơ chế xử lý biên trong hệ thống thị giác sinh học
- C. LoG cho biên dày hơn
- D. LoG không cần tham số

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. LoG mô phỏng cơ chế xử lý biên trong hệ thống thị giác sinh học

**Giải thích:** Marr và Hildreth xây dựng một mô hình phát hiện biến đổi cường độ ở nhiều thang đo, dùng Gaussian làm trơn và zero-crossing của Laplacian để biểu diễn vị trí biên. Cách tiếp cận gắn với các lập luận về tổ chức trường tiếp nhận và xử lý thị giác sinh học, nên B diễn đạt động cơ của mô hình. 'Mô phỏng' ở đây không có nghĩa LoG tái tạo toàn bộ hệ thị giác, và Gaussian vẫn cần tham số scale; cũng không thể xem tốc độ so với Canny là động cơ của công trình năm 1980. *Kiến thức bổ sung (slide chỉ giới thiệu tên Marr-Hildreth, chưa trình bày căn cứ sinh học).* Tham khảo: [Marr và Hildreth, Theory of edge detection (1980)](https://www.hms.harvard.edu/bss/neuro/bornlab/qmbc/beta/day4/marr-hildreth-edge-prsl1980.pdf).

</details>

### Câu 343
Nguồn PDF: trang 47

Điều nào đúng về phát hiện đường thẳng bằng RANSAC trong ảnh nhiễu?

- A. RANSAC thất bại với ảnh nhiễu
- B. RANSAC hoạt động tốt vì chọn ngẫu nhiên và đánh giá inliers, không bị dominated bởi outliers (nhiễu)
- C. RANSAC chỉ tìm được 1 đường thẳng
- D. RANSAC cần ảnh không có nhiễu

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. RANSAC hoạt động tốt vì chọn ngẫu nhiên và đánh giá inliers, không bị dominated bởi outliers (nhiễu)

**Giải thích:** RANSAC tạo giả thuyết từ mẫu nhỏ rồi kiểm tra có bao nhiêu điểm nằm đủ gần đường thẳng đó. Khi lấy được mẫu toàn inliers, mô hình thường được nhiều điểm của đường thật ủng hộ, trong khi outliers không nhất quán ít có khả năng tạo đồng thuận lớn như vậy. B mô tả ưu thế so với việc khớp bình phương tối thiểu ngay trên toàn bộ dữ liệu; tuy nhiên RANSAC không miễn nhiễm với nhiễu, vì tỷ lệ inliers thấp, ngưỡng không hợp lý hoặc cấu trúc nhiễu có đồng thuận có thể làm nó thất bại. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 39-46.

</details>

### Câu 344
Nguồn PDF: trang 47

Khi dùng Hough Transform để phát hiện đường tròn với bán kính đã biết, accumulator cần mấy chiều?

- A. 3D (cx, cy, r)
- B. 2D (cx, cy) vì r đã biết
- C. 1D
- D. 4D

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. 2D (cx, cy) vì r đã biết

**Giải thích:** Khi r đã được cho trước, mỗi ứng viên đường tròn chỉ còn cần xác định cx và cy. Mỗi điểm biên bỏ phiếu cho các tâm cách nó đúng r, và vị trí tâm nhận nhiều phiếu nhất là ứng viên tốt. Do đó accumulator chỉ cần hai trục tọa độ tâm, chọn B; chiều bán kính thứ ba chỉ cần khi phải tìm r, còn một trục không đủ biểu diễn tâm bất kỳ trên mặt phẳng ảnh. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 30, 37, kết hợp phương trình đường tròn với bán kính cố định.

</details>

### Câu 345
Nguồn PDF: trang 47

Điều nào KHÔNG là bước trong Canny edge detector?

- A. Gaussian smoothing
- B. Histogram equalization
- C. Non-maximum suppression
- D. Hysteresis thresholding

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Histogram equalization

**Giải thích:** Pipeline Canny trong slide gồm làm trơn Gaussian, tính gradient, non-maximum suppression và ngưỡng kép với hysteresis. Histogram equalization thay đổi phân bố mức xám và không nằm trong các bước chuẩn đó, nên B là đáp án của câu hỏi 'KHÔNG'. Có thể thêm cân bằng histogram như một bước tiền xử lý của ứng dụng cụ thể, nhưng điều đó không biến nó thành thành phần bắt buộc của Canny. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 26-27.

</details>

### Câu 346
Nguồn PDF: trang 47

Phát hiện biên ở mức "Level 2" (Middle vision) phục vụ mục đích gì cho các bước sau?

- A. Tạo ảnh đẹp hơn
- B. Cung cấp ranh giới đối tượng, hỗ trợ phân vùng và nhận dạng ở High- level vision
- C. Nén dữ liệu
- D. Tăng tốc xử lý

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Cung cấp ranh giới đối tượng, hỗ trợ phân vùng và nhận dạng ở High- level vision

**Giải thích:** Theo phân cấp của môn học, middle vision trích xuất các đặc trưng như biên, góc, đường và hình dạng để làm cầu nối từ ảnh sang phân tích ngữ nghĩa. Biên cung cấp ứng viên ranh giới và cấu trúc cho phân vùng hoặc nhận dạng ở high-level vision, nên B phù hợp. Đây không phải thao tác làm ảnh đẹp hơn hoặc nén dữ liệu; đồng thời biên cường độ không tự xác định đối tượng, nên các bước sau vẫn cần gom nhóm và diễn giải. Tham chiếu: `IT5409 L1-2-IntroImageFormation.pdf`, trang 3; `IT5409 L4.1-EdgeDetection.pdf`, trang 2, 4.

</details>

### Câu 347
Nguồn PDF: trang 47

Gradient direction của Sobel được tính bằng công thức nào?

- A. sqrt(Gx² + Gy²)
- B. atan2(Gy, Gx)
- C. Gx + Gy
- D. |Gx - Gy|

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. atan2(Gy, Gx)

**Giải thích:** Gx và Gy là hai thành phần của vector gradient, nên góc của vector được tính bằng atan2(Gy,Gx). Hàm atan2 dùng dấu của cả hai thành phần để xác định đúng góc phần tư và xử lý trường hợp Gx bằng không tốt hơn phép arctan(Gy/Gx) đơn giản. A là độ lớn gradient chứ không phải hướng; C và D cũng không biểu diễn góc, nên chọn B. Chiều tăng của trục y và dấu kernel phải nhất quán khi diễn giải góc trên ảnh. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 9, 12, 26.

</details>

### Câu 348
Nguồn PDF: trang 47

Khi số lượng đường thẳng trong ảnh nhiều, Hough Transform gặp khó khăn gì?

- A. Không tìm được đường nào
- B. Nhiều peak trong accumulator, khó phân biệt và chọn lọc; tăng false positives
- C. Quá nhanh
- D. Không lưu trữ được

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Nhiều peak trong accumulator, khó phân biệt và chọn lọc; tăng false positives

**Giải thích:** Mỗi đường thẳng được nhiều điểm biên hỗ trợ sẽ tạo vùng phiếu cao trong accumulator, nên ảnh nhiều đường có thể tạo nhiều peak gần nhau hoặc có độ mạnh tương tự. Khi đó cần chọn ngưỡng, tách peak và kiểm tra độ dài hoặc ngữ cảnh để tránh gộp hai đường hoặc nhận đường không mong muốn. B nói đúng khó khăn về lựa chọn mô hình; Hough vẫn có khả năng tìm nhiều đường, và nhiều peak không có nghĩa tất cả đều do nhiễu. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 32-33, 37.

</details>

### Câu 349
Nguồn PDF: trang 48

Điều nào đúng về tương quan giữa Sobel và ứng dụng CNN?

- A. Sobel thay thế hoàn toàn CNN
- B. Sobel là ví dụ về filter thủ công; CNN học filter tương tự (phát hiện biên) một cách tự động từ dữ liệu
- C. CNN không thể học phát hiện biên
- D. Sobel chỉ dùng trong CNN

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Sobel là ví dụ về filter thủ công; CNN học filter tương tự (phát hiện biên) một cách tự động từ dữ liệu

**Giải thích:** Sobel có các trọng số đạo hàm và làm trơn được ấn định trước bởi người thiết kế. Trong CNN, trọng số kernel được tối ưu từ dữ liệu và hàm mất mát; ở các lớp đầu, một số kernel có thể học đáp ứng với biên theo hướng giống vai trò của Sobel. B đúng về sự tương đồng chức năng, không có nghĩa CNN phải học đúng ma trận Sobel hoặc Sobel thay thế được cả mạng gồm nhiều tầng và đặc trưng khác. *Kiến thức bổ sung (không có tham chiếu trong slide cho so sánh trực tiếp Sobel với kernel học được).* Tham khảo: [Stanford CS231n, Convolutional Networks](https://cs231n.github.io/convolutional-networks/).

</details>

### Câu 350
Nguồn PDF: trang 48

Kết quả của Non-maximum suppression (NMS) trong Canny là gì?

- A. Ảnh grayscale bình thường
- B. Biên mỏng: chỉ giữ lại điểm cực đại cục bộ dọc theo hướng gradient
- C. Ảnh nhị phân có biên dày
- D. Histogram của biên

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Biên mỏng: chỉ giữ lại điểm cực đại cục bộ dọc theo hướng gradient

**Giải thích:** Trên ảnh độ lớn gradient, NMS so sánh mỗi điểm với hai điểm lân cận theo hướng gradient, tức hướng đi ngang qua đường biên. Điểm không phải cực đại cục bộ bị đặt về không, còn đỉnh đáp ứng được giữ để tạo đường biên mảnh, nên chọn B. Kết quả ở giai đoạn này vẫn có thể mang giá trị độ lớn gradient, chưa nhất thiết là bản đồ nhị phân cuối cùng; bước ngưỡng và hysteresis mới quyết định các ứng viên nào trở thành biên đầu ra. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 26-27.

</details>

### Câu 351
Nguồn PDF: trang 48

Tại sao Hough Transform bền vững với noise và biên bị gián đoạn?

- A. Vì nó lọc noise trước
- B. Vì mỗi điểm biên bỏ phiếu độc lập; noise ít phiếu, đường thẳng thực nhiều phiếu hơn
- C. Vì nó dùng nhiều ngưỡng
- D. Vì nó dùng kết hợp với RANSAC

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Vì mỗi điểm biên bỏ phiếu độc lập; noise ít phiếu, đường thẳng thực nhiều phiếu hơn

**Giải thích:** Các điểm thuộc cùng một đường thẳng bỏ phiếu về cùng vùng tham số, nên chúng có thể tạo peak dù bị chia thành nhiều đoạn rời rạc. Nhiễu ngẫu nhiên thường phân tán phiếu trên nhiều ô thay vì tích tụ vào một mô hình chung, đó là cơ sở của tính bền vững ở B. Hough không nhất thiết lọc nhiễu trước và không cần kết hợp RANSAC; nếu nhiễu cũng tạo cấu trúc thẳng hoặc đường thật có quá ít điểm hỗ trợ, tính bền vững này vẫn có giới hạn. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 32-37.

</details>

### Câu 352
Nguồn PDF: trang 48

Kết quả của Canny edge detector là gì?

- A. Ảnh gradient magnitude
- B. Bản đồ biên nhị phân (binary edge map), biên mỏng 1 pixel
- C. Danh sách các điểm biên
- D. Ảnh đã làm trơn

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Bản đồ biên nhị phân (binary edge map), biên mỏng 1 pixel

**Giải thích:** Sau khi tính gradient và làm mảnh, Canny dùng ngưỡng kép cùng hysteresis để quyết định pixel nào thuộc biên. Đầu ra thông dụng là một bản đồ nhị phân với pixel biên và nền, các đường biên được làm mảnh nhờ NMS, tương ứng B. Ảnh Gaussian và ảnh gradient magnitude chỉ là kết quả trung gian; có thể trích tọa độ từ bản đồ cuối nhưng danh sách tọa độ không phải dạng đầu ra chuẩn được hỏi. Độ rộng một pixel là mô tả điển hình, không bảo đảm tuyệt đối ở mọi cấu hình và vị trí giao nhau. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 25-27.

</details>

### Câu 353
Nguồn PDF: trang 48

Điều nào đúng về Roberts filter?

- A. Kích thước 3×3, ít nhạy cảm với noise
- B. Kích thước 2×2, tính đạo hàm theo đường chéo, là filter đơn giản nhất
- C. Bao gồm Gaussian smoothing
- D. Chỉ tính gradient theo chiều x

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Kích thước 2×2, tính đạo hàm theo đường chéo, là filter đơn giản nhất

**Giải thích:** Roberts tính hai sai phân giữa các cặp pixel đối diện trong cửa sổ 2×2, tương ứng hai hướng chéo. Cấu trúc nhỏ này rất ít phép toán nhưng không có bước làm trơn Gaussian, nên dễ bị ảnh hưởng bởi biến động nhiễu giữa các pixel lân cận. B đúng về kích thước và cách lấy đạo hàm; cụm 'đơn giản nhất' nên hiểu là một bộ lọc gradient rất đơn giản trong nhóm đang so sánh, không phải một định nghĩa hay thứ hạng tuyệt đối của mọi bộ lọc. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 10, 15-16.

</details>

### Câu 354
Nguồn PDF: trang 48

Khi biên trong ảnh không sắc nét (blurry edges), Canny hoạt động như thế nào?

- A. Không phát hiện được biên
- B. Vẫn phát hiện được, nhưng vị trí biên có thể kém chính xác hơn
- C. Phát hiện quá nhiều biên
- D. Crash

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Vẫn phát hiện được, nhưng vị trí biên có thể kém chính xác hơn

**Giải thích:** Biên bị nhòe trải thay đổi sáng tối trên một vùng rộng, khiến gradient thấp hơn và đỉnh đáp ứng khó định vị rõ như biên sắc. Canny vẫn có thể giữ đỉnh đó nếu độ tương phản, scale làm trơn và ngưỡng phù hợp, nên B là mô tả hợp lý. Đây không phải bảo đảm luôn phát hiện được: khi gradient bị giảm dưới ngưỡng hoặc lẫn với nhiễu, biên có thể mất hoàn toàn; các lựa chọn A và C khẳng định kết quả cố định nên quá tuyệt đối. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 14-15, 25-29.

</details>

### Câu 355
Nguồn PDF: trang 48

Điều nào đúng về tính chất của gradient ảnh?

- A. Gradient luôn dương
- B. Gradient là vector có cả hướng và độ lớn; chỉ về hướng thay đổi cường độ lớn nhất
- C. Gradient bằng 0 tại vị trí biên
- D. Gradient không liên quan đến biên

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Gradient là vector có cả hướng và độ lớn; chỉ về hướng thay đổi cường độ lớn nhất

**Giải thích:** Gradient gồm hai thành phần đạo hàm theo x và y, tạo thành vector hướng về phía cường độ tăng nhanh nhất. Mỗi thành phần có thể âm hoặc dương, trong khi độ lớn của vector là đại lượng không âm, nên A nhầm giữa thành phần gradient và magnitude. Gần biên có thay đổi cường độ nhanh, magnitude thường lớn chứ không phải bằng không; B vì vậy nêu đúng cả bản chất vector lẫn ý nghĩa hướng. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 9, 12.

</details>

### Câu 356
Nguồn PDF: trang 48

Phát hiện biên (edge detection) thuộc mức xử lý nào của Computer Vision?

- A. High-level Vision
- B. Middle-level Vision
- C. Low-level Vision
- D. Không thuộc mức nào

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Middle-level Vision

**Giải thích:** Trong sơ đồ phân cấp của IT5409, phát hiện biên được liệt kê ở middle-level vision cùng trích góc, đường, texture và hình dạng. Hoạt động này biến dữ liệu pixel thành đặc trưng cấu trúc, chưa gán nhãn ngữ nghĩa cho đối tượng nên không phải high-level vision trong cách chia của môn. Chọn B theo tài liệu học phần; một số tài liệu khác dùng thuật ngữ low-level cho edge detection, vì vậy không nên xem tên mức là phân loại thống nhất ở mọi nguồn. Tham chiếu: `IT5409 L1-2-IntroImageFormation.pdf`, trang 3.

</details>

### Câu 357
Nguồn PDF: trang 49

Điều nào đúng về xử lý biên ảnh trong Canny sau NMS?

- A. Biên được kết nối ngay lập tức
- B. Có hai loại biên: strong (> T_high) và weak (T_low < x < T_high); weak chỉ giữ nếu kết nối strong
- C. Tất cả pixel > 0 là biên
- D. Chỉ strong edges mới được xử lý

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Có hai loại biên: strong (> T_high) và weak (T_low < x < T_high); weak chỉ giữ nếu kết nối strong

**Giải thích:** Sau NMS, hai ngưỡng được áp lên độ lớn gradient còn lại: trên ngưỡng cao là strong, trong khoảng hai ngưỡng là weak, còn dưới ngưỡng thấp bị loại. Một điểm weak được giữ nếu có chuỗi các điểm ứng viên kết nối nó tới một điểm strong, không chỉ khi bản thân nó vượt ngưỡng cao. B mô tả đúng cơ chế, và x trong lựa chọn phải hiểu là giá trị đáp ứng gradient chứ không phải tọa độ hay cường độ ảnh gốc; quy tắc tại đúng giá trị ngưỡng có thể khác theo triển khai. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 26-27.

</details>

### Câu 358
Nguồn PDF: trang 49

Điều gì đúng về cặp (m,b) trong không gian Hough thông thường?

- A. m và b luôn là số nguyên
- B. m có thể vô cực với đường thẳng đứng → dùng dạng cực để tránh
- C. m và b không thể âm
- D. b phải nằm trong ảnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. m có thể vô cực với đường thẳng đứng → dùng dạng cực để tránh

**Giải thích:** Trong phương trình y=mx+b, một đường thẳng đứng không biểu diễn được bằng hệ số góc m hữu hạn. Dạng rho=x cos(theta)+y sin(theta) dùng hướng pháp tuyến và khoảng cách tới gốc để biểu diễn cả đường đứng lẫn các hướng khác mà không gặp vấn đề hệ số góc vô hạn. Do đó B giải thích lý do đổi tham số; m và b không bắt buộc là số nguyên, không bị cấm âm, và giao điểm b có thể nằm ngoài khung ảnh. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 31, 34.

</details>

### Câu 359
Nguồn PDF: trang 49

Điều nào đúng về ứng dụng của RANSAC ngoài phát hiện đường thẳng?

- A. Chỉ dùng cho đường thẳng
- B. Dùng cho mọi bài toán fitting mô hình hình học: đường tròn, homography, fundamental matrix, v.v.
- C. Chỉ dùng trong 2D
- D. Không dùng trong thực tế

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Dùng cho mọi bài toán fitting mô hình hình học: đường tròn, homography, fundamental matrix, v.v.

**Giải thích:** RANSAC là khung ước lượng mô hình từ mẫu nhỏ và đánh giá đồng thuận, không bị giới hạn ở phương trình đường thẳng. Slide nêu các mô hình hình học và ứng dụng như homography cho ghép ảnh, fundamental matrix cho hình học hai góc nhìn, nên B đúng về phạm vi ứng dụng rộng. Tuy nhiên từ 'mọi' quá mạnh: bài toán phải có cách ước lượng từ mẫu hợp lệ, thước đo residual và tiêu chí inlier phù hợp, đồng thời cần tránh mẫu suy biến; không phải cứ là fitting thì RANSAC luôn dùng tốt. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 38, 46.

</details>

### Câu 360
Nguồn PDF: trang 49

Phát hiện biên trong màn đêm (low-light) gặp khó khăn gì?

- A. Biên quá rõ ràng
- B. Nhiễu nhiều hơn (noise-dominated), khó phân biệt biên thực với noise
- C. Ảnh quá nhỏ
- D. Gradient quá lớn

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Nhiễu nhiều hơn (noise-dominated), khó phân biệt biên thực với noise

**Giải thích:** Khi tín hiệu ánh sáng yếu, tương phản hữu ích có thể nhỏ so với nhiễu của quá trình thu ảnh, nên tỷ lệ tín hiệu trên nhiễu thấp. Phép đạo hàm lại làm nổi các dao động cục bộ, khiến gradient do nhiễu khó phân biệt với gradient của biên thật, đúng với B. Khó khăn không phải ảnh bắt buộc nhỏ hay gradient luôn lớn; mức ảnh hưởng còn tùy cảm biến, phơi sáng và xử lý giảm nhiễu, còn làm trơn quá mạnh có thể xóa thêm biên yếu. *Kiến thức bổ sung (không có tham chiếu trong slide riêng về low-light).*

</details>

### Câu 361
Nguồn PDF: trang 49

Điều nào KHÔNG phải là thuộc tính của Canny optimal edge detector?

- A. Good detection
- B. Good localization
- C. Multiple response
- D. Single response

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** C. Multiple response

**Giải thích:** Ba tiêu chí của bộ phát hiện biên tối ưu trong bài học là phát hiện tốt, định vị tốt và chỉ có một đáp ứng cho mỗi biên thật. Multiple response tạo nhiều dấu biên cho cùng một chuyển tiếp, trái với tiêu chí single response nên C là lựa chọn 'KHÔNG'. NMS góp phần giảm đáp ứng dư quanh đỉnh gradient, nhưng tiêu chí tối ưu còn phải cân bằng với khả năng phát hiện và độ chính xác vị trí. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 25-26.

</details>

### Câu 362
Nguồn PDF: trang 49

Trong ứng dụng xe tự hành, phát hiện làn đường (lane detection) thường dùng kỹ thuật nào?

- A. Color segmentation
- B. Edge detection + Hough Transform để phát hiện đường thẳng làn đường
- C. Object detection
- D. Optical flow

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Edge detection + Hough Transform để phát hiện đường thẳng làn đường

**Giải thích:** Trong một pipeline phát hiện làn đường cổ điển, bộ phát hiện biên tạo các điểm ứng viên trên vạch làn, rồi Hough gom chúng thành đường thẳng hoặc đoạn thẳng được nhiều điểm hỗ trợ. B mô tả cách tận dụng đặc trưng hình học ấy; thường còn giới hạn vùng quan tâm và kiểm tra hướng, vị trí để loại đường từ xe hoặc cảnh nền. Đây không phải phương pháp duy nhất của xe tự hành: phân vùng màu và mô hình học sâu cũng có thể được dùng, còn làn cong không được mô tả đầy đủ bằng một đường thẳng duy nhất. *Kiến thức bổ sung (không có tham chiếu trong slide cho pipeline phát hiện làn đường).*

</details>

### Câu 363
Nguồn PDF: trang 49

Khi ảnh có biên với texture phức tạp (textured objects), phát hiện biên gặp khó khăn gì?

- A. Biên không tồn tại
- B. Texture tạo ra nhiều biên giả, khó phân biệt biên của đối tượng với biên texture
- C. Quá ít biên được phát hiện
- D. Chỉ biên ngang được phát hiện

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Texture tạo ra nhiều biên giả, khó phân biệt biên của đối tượng với biên texture

**Giải thích:** Texture chứa những thay đổi sáng tối lặp lại ngay bên trong một đối tượng, nên cũng tạo đáp ứng gradient mạnh. Bộ phát hiện biên cục bộ không tự biết đáp ứng nào là đường bao đối tượng và đáp ứng nào chỉ là hoa văn bề mặt, vì vậy B nêu đúng khó khăn phân biệt. Các 'biên giả' ở đây có thể là biến đổi cường độ thật nhưng sai đối với mục tiêu phân vùng đối tượng; chọn scale hoặc làm trơn có thể giảm chúng nhưng cũng làm mất chi tiết cần giữ. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 2, 14-15, 17-19.

</details>

### Câu 364
Nguồn PDF: trang 50

Điều nào đúng về kết quả Gradient Magnitude được dùng để phát hiện biên?

- A. Pixel có gradient magnitude thấp là biên
- B. Pixel có gradient magnitude cao thường là biên
- C. Gradient magnitude không liên quan đến biên
- D. Gradient magnitude phải bằng 1 để là biên

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Pixel có gradient magnitude cao thường là biên

**Giải thích:** Magnitude lớn cho biết cường độ biến đổi nhanh quanh pixel, nên pixel đó là ứng viên biên mạnh. Đây là lý do có thể áp ngưỡng lên ảnh gradient để chọn biên, tương ứng B. Tuy nhiên magnitude cao chưa chứng minh đó là ranh giới đối tượng vì nhiễu, texture hoặc bóng cũng tạo đáp ứng lớn; không có yêu cầu chung magnitude phải bằng 1, vì giá trị phụ thuộc thang cường độ và chuẩn hóa kernel. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 6, 12, 17-19.

</details>

### Câu 365
Nguồn PDF: trang 50

Prewitt filter với kernel Gx = [[-1,0,1],[-1,0,1],[-1,0,1]] phát hiện biên theo hướng nào?

- A. Ngang (horizontal)
- B. Dọc (vertical)
- C. Đường chéo
- D. Tất cả hướng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Dọc (vertical)

**Giải thích:** Kernel cộng các giá trị ở cột phải và trừ các giá trị ở cột trái, nên xấp xỉ biến thiên cường độ theo chiều x. Một biên dọc có sự thay đổi mạnh khi đi qua nó theo x, vì vậy đáp ứng Gx mạnh và chọn B. Ba hàng có trọng số bằng nhau tạo thành phần làm trơn theo y; việc đảo toàn bộ dấu kernel chỉ đổi dấu đạo hàm, không đổi hướng biên được nhấn mạnh. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 10-11, 17.

</details>

### Câu 366
Nguồn PDF: trang 50

Tại sao phát hiện biên là bước quan trọng trong phân vùng ảnh?

- A. Vì biên tạo ra texture
- B. Vì biên là ranh giới giữa các vùng, giúp tách các đối tượng ra khỏi nhau
- C. Vì biên chứa thông tin màu
- D. Vì biên giảm kích thước ảnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Vì biên là ranh giới giữa các vùng, giúp tách các đối tượng ra khỏi nhau

**Giải thích:** Một đường bao có thể đánh dấu nơi chuyển từ vùng ảnh này sang vùng khác, nên các biên được gom và khép kín giúp xác định vùng cần tách. B diễn đạt vai trò đó trong phân vùng, khác với việc tạo texture hoặc giảm kích thước dữ liệu. Tuy nhiên một bản đồ biên chưa phải kết quả phân vùng hoàn chỉnh: đường bao có thể đứt, và biên do chiếu sáng hay hoa văn không nhất thiết phân chia hai đối tượng, nên còn cần các bước liên kết hoặc kết hợp thông tin vùng. Tham chiếu: `IT5409 L1-2-IntroImageFormation.pdf`, trang 3; `IT5409 L4.1-EdgeDetection.pdf`, trang 2, 4.

</details>

### Câu 367
Nguồn PDF: trang 50

Điều gì đúng về image gradient trong ảnh màu?

- A. Chỉ tính cho kênh đỏ
- B. Tính gradient cho từng kênh riêng và kết hợp (ví dụ: gradient magnitude lớn nhất qua các kênh)
- C. Không thể tính gradient cho ảnh màu
- D. Chuyển sang grayscale trước

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Tính gradient cho từng kênh riêng và kết hợp (ví dụ: gradient magnitude lớn nhất qua các kênh)

**Giải thích:** Có thể tính Gx và Gy trên từng kênh màu, rồi kết hợp đáp ứng; chọn kênh có magnitude lớn nhất tại mỗi pixel là một cách giữ lại biến đổi mạnh ở bất kỳ kênh nào. Cách này tránh bỏ một ranh giới màu chỉ vì nó có độ sáng xám gần như không đổi, nên B là phương án hợp lệ. Tuy nhiên D cũng là cách xử lý hợp lệ nếu chuyển ảnh màu sang grayscale rồi tính gradient, dù có thể mất thông tin màu; câu hỏi một đáp án vì thế chưa loại trừ D rõ ràng, và đáp án gốc B được giữ chứ không có nghĩa D luôn sai. *Kiến thức bổ sung (không có tham chiếu trong slide).* Tham khảo: [mã Canny đa kênh của OpenCV](https://github.com/opencv/opencv/blob/4.x/modules/imgproc/src/canny.cpp).

</details>

### Câu 368
Nguồn PDF: trang 50

Điều nào đúng về sự khác biệt giữa Hough và RANSAC cho phát hiện đường thẳng?

- A. RANSAC luôn tốt hơn
- B. Hough voting-based, bền vững với noise; RANSAC random sampling, tốt với outliers nhưng không deterministic
- C. Chúng giống nhau hoàn toàn
- D. Hough chỉ cho đường thẳng, RANSAC không thể

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Hough voting-based, bền vững với noise; RANSAC random sampling, tốt với outliers nhưng không deterministic

**Giải thích:** Hough cổ điển duyệt các giả thuyết tham số và cộng phiếu từ điểm biên, còn RANSAC sinh một tập giả thuyết bằng các mẫu ngẫu nhiên rồi đánh giá inliers. Do đó B phân biệt đúng voting với random sampling và lý do hai phương pháp có hành vi khác nhau trước nhiễu. Cần hiểu 'không deterministic' là kết quả RANSAC có thể đổi khi đổi chuỗi lấy mẫu; cố định seed và điều kiện tính toán có thể cho kết quả lặp lại, trong khi Hough cũng có các biến thể xác suất. Không có bảo đảm RANSAC luôn tốt hơn Hough. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 32-37, 40-46.

</details>

### Câu 369
Nguồn PDF: trang 50

Điều nào KHÔNG đúng về Hough Transform?

- A. Dùng accumulator array
- B. Bền vững với noise đến một mức nhất định
- C. Tốc độ O(1) không phụ thuộc kích thước ảnh
- D. Có thể phát hiện nhiều đường cùng lúc

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** C. Tốc độ O(1) không phụ thuộc kích thước ảnh

**Giải thích:** Hough cần xử lý các điểm biên để cập nhật accumulator và sau đó tìm các ô có nhiều phiếu. Với Hough đường thẳng cổ điển, E điểm biên và K mức theta thường tạo khoảng E×K lượt cập nhật, chưa kể quét accumulator để lấy peak, nên thời gian không thể độc lập hoàn toàn với dữ liệu như O(1). C là phát biểu sai; accumulator, khả năng tìm nhiều đường và chống nhiễu trong giới hạn đều đúng với mô tả trong slide. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 32-33, 37.

</details>

### Câu 370
Nguồn PDF: trang 50

Kết quả của Canny edge detection thường được dùng như thế nào trong pipeline xử lý ảnh tiếp theo?

- A. Trực tiếp đưa vào classifier
- B. Làm đầu vào cho Hough Transform, phân vùng ảnh, hoặc trích chọn contour
- C. Thay thế ảnh gốc
- D. Nén ảnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Làm đầu vào cho Hough Transform, phân vùng ảnh, hoặc trích chọn contour

**Giải thích:** Bản đồ Canny biểu diễn các ứng viên đường biên thay vì toàn bộ cường độ ảnh, nên thích hợp để đưa vào bước gom cấu trúc hình học như Hough. Nó cũng có thể hỗ trợ tìm contour hoặc phân vùng dựa trên ranh giới, vì vậy B nêu những cách dùng phổ biến của kết quả biên. Không nên xem bản đồ này là ảnh gốc thay thế hoàn toàn vì nó bỏ màu và texture; đưa biên vào classifier vẫn có thể là một thiết kế riêng, nhưng không phải vai trò điển hình đang được hỏi. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 33, 36; `IT5409 L1-2-IntroImageFormation.pdf`, trang 3.

</details>

### Câu 371
Nguồn PDF: trang 50

Điều nào đúng về phát hiện đường tròn bằng Hough Transform?

- A. Không thể phát hiện đường tròn
- B. Cần accumulator 3D (cx, cy, r) và phức tạp hơn đường thẳng
- C. Đơn giản hơn phát hiện đường thẳng
- D. Chỉ cần 2 tham số

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Cần accumulator 3D (cx, cy, r) và phức tạp hơn đường thẳng

**Giải thích:** Đường thẳng dạng cực có hai tham số, trong khi đường tròn tổng quát cần tọa độ tâm và bán kính, tức ba tham số. Nếu lượng tử hóa trực tiếp cả ba trục, accumulator và quá trình bỏ phiếu tốn hơn, nên B đúng trong ngữ cảnh Hough cổ điển. Không phải mọi triển khai đều lưu accumulator 3D tường minh: phương pháp Hough gradient trong OpenCV tách tìm tâm và tìm bán kính để tăng hiệu quả, còn biết trước r cũng giảm bài toán xuống hai chiều. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 37. *Kiến thức bổ sung về triển khai ngoài slide:* [OpenCV, Hough Circle Transform](https://docs.opencv.org/4.x/d4/d70/tutorial_hough_circle.html).

</details>

### Câu 372
Nguồn PDF: trang 51

Điều gì xảy ra khi T_low trong Canny quá thấp?

- A. Bỏ sót nhiều biên
- B. Giữ lại nhiều biên yếu (noise), dẫn đến false positives
- C. Biên dày hơn
- D. Không ảnh hưởng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Giữ lại nhiều biên yếu (noise), dẫn đến false positives

**Giải thích:** Giảm T_low cho phép nhiều đáp ứng gradient nhỏ vượt điều kiện trở thành ứng viên biên yếu. Một phần trong số đó có thể do nhiễu và được giữ nếu nối qua chuỗi ứng viên tới biên mạnh, làm tăng false positives như B nêu. Không phải tất cả pixel vượt T_low đều được giữ, vì hysteresis vẫn yêu cầu kết nối tới strong edge; bước NMS đã quyết định làm mảnh nên hạ ngưỡng dưới không trực tiếp làm mọi biên dày lên. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 26-29.

</details>

### Câu 373
Nguồn PDF: trang 51

Bộ phát hiện biên nào ít nhạy cảm với noise nhất?

- A. Roberts (2×2)
- B. Canny (có Gaussian smoothing)
- C. Prewitt (3×3)
- D. LoG (không Gaussian)

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Canny (có Gaussian smoothing)

**Giải thích:** Canny kết hợp làm trơn Gaussian trước đạo hàm với NMS và hysteresis, nên trong so sánh khái quát của câu hỏi nó được ưu tiên về kiểm soát nhiễu hơn các sai phân đơn giản. B là đáp án gốc theo ý này, nhưng không tồn tại thứ hạng 'ít nhạy nhất' tuyệt đối nếu không cố định loại nhiễu, scale và các ngưỡng. Đặc biệt D viết 'LoG không Gaussian' là sai ngay ở tên khái niệm: LoG là Laplacian of Gaussian và có làm trơn Gaussian, nên không được dùng mô tả sai đó để kết luận LoG luôn kém hơn Canny. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 15-16, 23-27.

</details>

### Câu 374
Nguồn PDF: trang 51

Trong xử lý ảnh y tế, phát hiện biên dùng để làm gì?

- A. Tăng độ phân giải
- B. Phân đoạn cấu trúc giải phẫu (xương, mô, khối u) trong ảnh MRI, CT
- C. Tăng tương phản
- D. Nén dữ liệu

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Phân đoạn cấu trúc giải phẫu (xương, mô, khối u) trong ảnh MRI, CT

**Giải thích:** Trong ảnh MRI hoặc CT, biến đổi cường độ quanh cấu trúc giải phẫu có thể cung cấp ứng viên ranh giới cho quá trình phân đoạn. Do đó B mô tả một vai trò của phát hiện biên, khác với tăng độ phân giải, cân bằng tương phản hay nén ảnh. Biên không tự xác định tên mô hoặc kết luận một vùng là khối u, và nhiễu, tương phản yếu hoặc ranh giới không rõ đòi hỏi kết hợp mô hình vùng hay kiến thức hình học; đây là bước hỗ trợ xử lý ảnh, không phải chẩn đoán tự động chỉ từ gradient. *Kiến thức bổ sung (không có tham chiếu trong slide cho ví dụ MRI/CT).*

</details>

### Câu 375
Nguồn PDF: trang 51

Điều nào đúng về mối quan hệ giữa gradient magnitude và biên?

- A. Gradient magnitude = 0 tại biên
- B. Biên thường ở nơi gradient magnitude đạt cực trị cục bộ
- C. Gradient magnitude không liên quan đến biên
- D. Gradient magnitude phải > 255

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Biên thường ở nơi gradient magnitude đạt cực trị cục bộ

**Giải thích:** Với một chuyển tiếp sáng tối đã làm trơn, magnitude thường tăng khi tiến tới tâm chuyển tiếp rồi giảm sau khi đi qua nó. Vì thế vị trí cực đại cục bộ theo hướng gradient là ứng viên vị trí biên, đúng với B và cũng là tiêu chí NMS sử dụng. Cực đại được xét ngang qua biên chứ không nhất thiết theo mọi hướng lân cận, và không có ngưỡng cố định 255 vì magnitude phụ thuộc phép lọc và thang cường độ. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 6, 15-16, 26.

</details>

### Câu 376
Nguồn PDF: trang 51

RANSAC có thể phát hiện nhiều đường thẳng trong cùng một ảnh như thế nào?

- A. Không thể
- B. Bằng cách chạy lại RANSAC sau khi loại bỏ inliers của đường thẳng đã tìm được
- C. Chỉ phát hiện 1 đường
- D. Tự động phát hiện tất cả đường

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Bằng cách chạy lại RANSAC sau khi loại bỏ inliers của đường thẳng đã tìm được

**Giải thích:** Một lần RANSAC thông thường chọn mô hình có tập inliers tốt nhất trong các giả thuyết đã thử. Sau khi tìm một đường, có thể tách các inliers của nó khỏi dữ liệu và chạy lại trên phần còn lại để tìm đường khác, nên B nêu chiến lược phát hiện tuần tự. Cách này không tự bảo đảm tìm mọi đường: ngưỡng quá rộng có thể lấy nhầm điểm của đường khác, điểm giao có thể bị loại sớm, và các đường ít điểm hỗ trợ có thể bị bỏ sót. *Kiến thức bổ sung (slide nêu khó khăn với nhiều mô hình, chưa trình bày đầy đủ chiến lược loại inliers rồi chạy lại).*

</details>

### Câu 377
Nguồn PDF: trang 51

Điều nào đúng về filter Sobel theo chiều y (Gy)?

- A. Gy = [[1,2,1],[0,0,0],[-1,-2,-1]]
- B. Gy phát hiện biên nằm ngang (horizontal edges)
- C. Cả A và B đều đúng
- D. Chỉ A đúng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** C. Cả A và B đều đúng

**Giải thích:** Kernel Gy đã cho lấy hiệu giữa hàng trên và hàng dưới, đồng thời làm trơn theo x bằng trọng số 1-2-1. Một biên ngang gây thay đổi cường độ khi đi theo y qua biên, nên Gy nhấn mạnh nó và cả A lẫn B đúng, chọn C. Đổi dấu kernel hoặc đổi chiều trục y chỉ làm đổi dấu đáp ứng và quy ước góc, không làm Gy chuyển thành bộ phát hiện biên dọc. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 10-12, 16.

</details>

### Câu 378
Nguồn PDF: trang 51

Điều nào KHÔNG phải là ứng dụng của Hough Transform?

- A. Phát hiện đường thẳng trong đường ray
- B. Phân loại màu sắc của đối tượng
- C. Phát hiện mống mắt (iris) hình tròn
- D. Phát hiện đường chân trời

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Phân loại màu sắc của đối tượng

**Giải thích:** Hough tìm các mô hình hình học được tham số hóa từ những điểm hỗ trợ, chẳng hạn đường thẳng hoặc đường tròn. Vì vậy nó có thể tìm đường ray, đường chân trời hoặc đường bao tròn xấp xỉ của mống mắt, nhưng không có cơ chế tự gán lớp màu cho đối tượng. Chọn B cho câu hỏi phủ định; các ứng dụng hình học vẫn cần mô hình phù hợp và bước kiểm tra, vì đường chân trời không luôn thẳng và mống mắt trong ảnh phối cảnh không luôn là một đường tròn hoàn hảo. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 30, 37.

</details>

### Câu 379
Nguồn PDF: trang 51

Khi RANSAC chạy N vòng lặp, điều gì ảnh hưởng đến N tối ưu?

- A. Kích thước ảnh
- B. Tỉ lệ outliers; nhiều outliers hơn cần nhiều vòng lặp hơn
- C. Màu sắc ảnh
- D. Độ phân giải ảnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Tỉ lệ outliers; nhiều outliers hơn cần nhiều vòng lặp hơn

**Giải thích:** Nếu tỷ lệ inliers là w và mỗi mẫu cần s điểm, xác suất một mẫu toàn inliers xấp xỉ w^s; khi outliers tăng thì xác suất này giảm. Để xác suất có ít nhất một mẫu tốt đạt p, số lượt thường được chọn theo N ≥ log(1-p)/log(1-w^s), rồi làm tròn lên. B vì thế đúng về ảnh hưởng của outliers, nhưng N còn phụ thuộc kích thước mẫu tối thiểu và mức tin cậy yêu cầu, không chỉ tỷ lệ outliers; công thức dùng giả thiết lấy mẫu độc lập và tỷ lệ inliers ước lượng phù hợp. Tham chiếu: `IT5409 L4.1-EdgeDetection.pdf`, trang 44-45.

</details>

### Câu 380
Nguồn PDF: trang 52

Điều nào đúng về biên dạng "Line" (line edge) trong ảnh?

- A. Giống Step edge
- B. Là đường mỏng sáng hoặc tối trên nền, có 2 biên (step edge) ở hai cạnh
- C. Không có trong ảnh thực
- D. Chỉ có ở ảnh nhân tạo

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Là đường mỏng sáng hoặc tối trên nền, có 2 biên (step edge) ở hai cạnh

**Giải thích:** Một vạch sáng mỏng trên nền tối có chuyển tiếp tối-sáng ở cạnh đầu và sáng-tối ở cạnh còn lại; vạch tối trên nền sáng có hai chuyển tiếp với dấu ngược lại. Vì vậy line edge được mô hình hóa như một dải gồm hai step edges, khác một step đơn chỉ có một lần chuyển mức, nên chọn B. Trên ảnh lấy mẫu hoặc bị nhòe, hai đáp ứng có thể chồng lên nhau khi vạch quá hẹp, nhưng mô hình hai cạnh vẫn giải thích nguồn gốc cấu trúc này; nó không bị giới hạn ở ảnh nhân tạo. *Kiến thức bổ sung (slide minh họa step, ramp và roof, không định nghĩa trực tiếp line edge).*

</details>


## CHƯƠNG 4.2: Trích chọn đặc trưng và so khớp ảnh

### Câu 381
Nguồn PDF: trang 52

Đặc trưng toàn cục (Global feature) và đặc trưng cục bộ (Local feature) khác nhau ở điểm gì?

- A. Toàn cục chỉ dùng cho ảnh lớn, cục bộ cho ảnh nhỏ
- B. Toàn cục mô tả toàn bộ ảnh như một đối tượng; cục bộ mô tả từng vùng nhỏ/điểm đặc trưng
- C. Không có sự khác biệt
- D. Toàn cục nhanh hơn cục bộ

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Toàn cục mô tả toàn bộ ảnh như một đối tượng; cục bộ mô tả từng vùng nhỏ/điểm đặc trưng

**Giải thích:** <!-- TODO -->

</details>

### Câu 382
Nguồn PDF: trang 52

Histogram màu là loại đặc trưng nào?

- A. Đặc trưng cục bộ
- B. Đặc trưng toàn cục
- C. Đặc trưng hình dạng
- D. Đặc trưng kết cấu

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Đặc trưng toàn cục

**Giải thích:** <!-- TODO -->

</details>

### Câu 383
Nguồn PDF: trang 52

Ưu điểm của Histogram màu là gì? (Chọn tất cả đúng)

- A. Đơn giản để tính
- B. Bất biến với phép quay, dịch, zoom
- C. Tính đến sự phân bố không gian của màu
- D. Không bị ảnh hưởng bởi nền

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Đơn giản để tính; B. Bất biến với phép quay, dịch, zoom

**Giải thích:** <!-- TODO -->

</details>

### Câu 384
Nguồn PDF: trang 52

GLCM (Grey Level Co-occurrence Matrix) là loại đặc trưng nào?

- A. Đặc trưng màu
- B. Đặc trưng kết cấu (texture feature)
- C. Đặc trưng hình dạng
- D. Đặc trưng cục bộ

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Đặc trưng kết cấu (texture feature)

**Giải thích:** <!-- TODO -->

</details>

### Câu 385
Nguồn PDF: trang 52

GLCM được tính dựa trên nguyên lý nào?

- A. Đếm số pixel theo màu sắc
- B. Đếm tần suất xuất hiện của cặp mức xám theo hướng và khoảng cách nhất định
- C. Tính gradient ảnh
- D. Phân tích tần số Fourier

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Đếm tần suất xuất hiện của cặp mức xám theo hướng và khoảng cách nhất định

**Giải thích:** <!-- TODO -->

</details>

### Câu 386
Nguồn PDF: trang 52

Các tham số quan trọng được ước lượng từ GLCM bao gồm gì? (Chọn tất cả đúng)

- A. Energy (năng lượng)
- B. Entropy
- C. Contrast
- D. Inverse Differential Moment (IDM)

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Energy (năng lượng); B. Entropy; C. Contrast; D. Inverse Differential Moment (IDM)

**Giải thích:** <!-- TODO -->

</details>

### Câu 387
Nguồn PDF: trang 53

Haralick features từ GLCM gồm bao nhiêu tham số?

- A. 7
- B. 14
- C. 21
- D. 28

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. 14

**Giải thích:** <!-- TODO -->

</details>

### Câu 388
Nguồn PDF: trang 53

HOG (Histogram of Oriented Gradients) là loại đặc trưng nào?

- A. Đặc trưng màu
- B. Đặc trưng hình dạng/gradient, phổ biến cho phát hiện người
- C. Đặc trưng kết cấu
- D. Đặc trưng điểm đặc biệt

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Đặc trưng hình dạng/gradient, phổ biến cho phát hiện người

**Giải thích:** <!-- TODO -->

</details>

### Câu 389
Nguồn PDF: trang 53

Hu's moments (moment bất biến Hu) có thuộc tính gì? (Chọn tất cả đúng)

- A. Bất biến với phép tịnh tiến (translation)
- B. Bất biến với phép biến đổi tỉ lệ (scale)
- C. Bất biến với phép quay (rotation)
- D. Bất biến với nhiễu Gaussian

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Bất biến với phép tịnh tiến (translation); B. Bất biến với phép biến đổi tỉ lệ (scale); C. Bất biến với phép quay (rotation)

**Giải thích:** <!-- TODO -->

</details>

### Câu 390
Nguồn PDF: trang 53

Harris Corner Detector xác định góc dựa trên tiêu chí nào?

- A. Pixel có cường độ cao nhất
- B. Điểm mà cường độ sáng thay đổi mạnh theo ít nhất hai hướng khác nhau
- C. Điểm nằm trên biên
- D. Điểm có màu sắc khác biệt

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Điểm mà cường độ sáng thay đổi mạnh theo ít nhất hai hướng khác nhau

**Giải thích:** <!-- TODO -->

</details>

### Câu 391
Nguồn PDF: trang 53

Trong Harris Corner Detector, giá trị R được tính như thế nào?

- A. R = trace(M) - k × det(M)²
- B. R = det(M) - k × trace(M)²
- C. R = det(M) × trace(M)
- D. R = det(M) / trace(M)

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. R = det(M) - k × trace(M)²

**Giải thích:** <!-- TODO -->

</details>

### Câu 392
Nguồn PDF: trang 53

Khi R > 0 (lớn) trong Harris, điểm đó được phân loại là gì?

- A. Biên (edge)
- B. Góc (corner)
- C. Vùng phẳng (flat)
- D. Nhiễu

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Góc (corner)

**Giải thích:** <!-- TODO -->

</details>

### Câu 393
Nguồn PDF: trang 53

Khi R < 0 trong Harris, điểm đó được phân loại là gì?

- A. Góc
- B. Biên
- C. Vùng phẳng
- D. Không xác định

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Biên

**Giải thích:** <!-- TODO -->

</details>

### Câu 394
Nguồn PDF: trang 53

SIFT (Scale-Invariant Feature Transform) có tính bất biến với gì? (Chọn tất cả đúng)

- A. Scale (tỉ lệ)
- B. Rotation (phép quay)
- C. Illumination (chiếu sáng đến mức nhất định)
- D. Occlusion hoàn toàn

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Scale (tỉ lệ); B. Rotation (phép quay); C. Illumination (chiếu sáng đến mức nhất định)

**Giải thích:** <!-- TODO -->

</details>

### Câu 395
Nguồn PDF: trang 54

SIFT descriptor được mô tả bằng vector bao nhiêu chiều?

- A. 64
- B. 128
- C. 256
- D. 512

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. 128

**Giải thích:** <!-- TODO -->

</details>

### Câu 396
Nguồn PDF: trang 54

Scale space trong SIFT được xây dựng bằng cách nào?

- A. Tăng kích thước ảnh
- B. Áp dụng Gaussian blur với σ tăng dần, tạo nhiều phiên bản ảnh ở các scale khác nhau
- C. Giảm số màu
- D. Áp dụng thresholding ở nhiều mức

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Áp dụng Gaussian blur với σ tăng dần, tạo nhiều phiên bản ảnh ở các scale khác nhau

**Giải thích:** <!-- TODO -->

</details>

### Câu 397
Nguồn PDF: trang 54

DoG (Difference of Gaussian) trong SIFT dùng để làm gì?

- A. Làm mờ ảnh
- B. Xấp xỉ LoG để phát hiện keypoints ổn định theo scale
- C. Tính histogram
- D. Phân vùng ảnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Xấp xỉ LoG để phát hiện keypoints ổn định theo scale

**Giải thích:** <!-- TODO -->

</details>

### Câu 398
Nguồn PDF: trang 54

NCC (Normalized Cross-Correlation) được dùng để làm gì trong image matching?

- A. Phát hiện biên
- B. Đo độ tương đồng giữa hai vùng ảnh, bất biến với thay đổi độ sáng
- C. Tăng tương phản
- D. Phân vùng ảnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Đo độ tương đồng giữa hai vùng ảnh, bất biến với thay đổi độ sáng

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* NCC đo mức tương quan của hai vùng ảnh sau khi chuẩn hóa, nên điểm số cao biểu thị các mẫu cường độ tương đồng. **Lưu ý:** bất biến với cả độ lệch và hệ số độ sáng dương cần dạng đã trừ trung bình, thường gọi ZNCC; NCC chỉ chuẩn hóa độ dài vector không tự loại được độ lệch cộng. Ngay cả ZNCC cũng không bất biến với mọi thay đổi chiếu sáng phi tuyến hoặc bóng cục bộ. Đối chiếu: [các công thức so khớp của OpenCV](https://docs.opencv.org/4.x/de/da9/tutorial_template_matching.html).

</details>

### Câu 399
Nguồn PDF: trang 54

SSD (Sum of Squared Differences) trong image matching tính điều gì?

- A. Tổng tuyệt đối của hiệu các pixel
- B. Tổng bình phương hiệu các pixel giữa hai vùng ảnh; nhỏ hơn → giống nhau hơn
- C. Khoảng cách Euclidean giữa các đặc trưng
- D. Tỉ lệ pixel giống nhau

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Tổng bình phương hiệu các pixel giữa hai vùng ảnh; nhỏ hơn → giống nhau hơn

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* SSD = tổng (I_i - T_i)² trên các cặp pixel tương ứng của hai vùng cùng kích thước. Bình phương làm mọi sai khác đóng góp không âm, nên SSD bằng 0 khi hai vùng giống hệt nhau và tăng khi cường độ khác nhau. A là tổng sai khác tuyệt đối, không phải SSD; C có liên hệ với SSD vì SSD là bình phương khoảng cách Euclidean của các vector pixel, nhưng B mô tả trực tiếp đại lượng được hỏi. Đối chiếu: [công thức TM_SQDIFF](https://docs.opencv.org/4.x/de/da9/tutorial_template_matching.html).

</details>

### Câu 400
Nguồn PDF: trang 54

Homography là phép biến đổi gì?

- A. Phép tịnh tiến đơn giản
- B. Phép biến đổi phối cảnh (projective) 2D, ánh xạ điểm từ mặt phẳng này sang mặt phẳng khác
- C. Phép quay 3D
- D. Phép scale đều

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Phép biến đổi phối cảnh (projective) 2D, ánh xạ điểm từ mặt phẳng này sang mặt phẳng khác

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* Homography ánh xạ tọa độ thuần nhất theo x' ~ Hx, với H là ma trận 3 x 3 khả nghịch và dấu ~ biểu thị bằng nhau tới một hệ số khác 0. Sau khi chia cho tọa độ thuần nhất, nó mô tả biến đổi phối cảnh giữa hai ảnh của một mặt phẳng, bao gồm cả quay, tịnh tiến hoặc scale như các trường hợp riêng. Với cảnh 3D có độ sâu khác nhau và camera tịnh tiến, một homography duy nhất thường không căn chỉnh đúng toàn cảnh. Đối chiếu: [khái niệm homography của OpenCV](https://docs.opencv.org/4.x/d9/dab/tutorial_homography.html).

</details>

### Câu 401
Nguồn PDF: trang 54

Homography có bao nhiêu bậc tự do (DOF)?

- A. 4
- B. 6
- C. 8
- D. 9

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** C. 8

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* Ma trận homography 3 x 3 có chín phần tử, nhưng H và kH với k khác 0 tạo cùng ánh xạ tọa độ thuần nhất. Một hệ số tỷ lệ vì vậy không phải tham số độc lập, để lại tám bậc tự do. Có thể chuẩn hóa một phần tử phù hợp hoặc chuẩn hóa độ dài ma trận; không bắt buộc phần tử h33 luôn khác 0. Đây là DOF của biến đổi projective 2D tổng quát, còn affine chỉ có sáu DOF. Đối chiếu: [ma trận homography](https://docs.opencv.org/4.x/d9/dab/tutorial_homography.html).

</details>

### Câu 402
Nguồn PDF: trang 55

Tại sao dùng RANSAC kết hợp với image matching?

- A. Để tăng tốc độ
- B. Để loại bỏ các matches sai (outliers) khi ước lượng homography
- C. Để tìm thêm matches
- D. Để thay thế NCC

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Để loại bỏ các matches sai (outliers) khi ước lượng homography

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* Các descriptor giống nhau có thể tạo cặp ghép sai, nhất là khi ảnh có texture lặp lại, nên dùng mọi match để fit homography dễ làm mô hình lệch. RANSAC thử các tập nhỏ, ước lượng mô hình rồi đếm những match có sai số chiếu nhỏ để tìm tập inlier nhất quán. Nó không tạo descriptor hay tìm thêm match; vai trò chính ở đây là ước lượng hình học bền vững trước outliers, sau đó có thể fit lại trên các inlier. Đối chiếu: [feature matching và RANSAC](https://docs.opencv.org/4.x/d1/de0/tutorial_py_feature_homography.html).

</details>

### Câu 403
Nguồn PDF: trang 55

LBP (Local Binary Pattern) là loại đặc trưng gì?

- A. Đặc trưng màu
- B. Đặc trưng texture cục bộ, so sánh pixel với hàng xóm
- C. Đặc trưng hình dạng
- D. Đặc trưng toàn cục

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Đặc trưng texture cục bộ, so sánh pixel với hàng xóm

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* LBP cơ bản so sánh cường độ từng pixel lân cận với pixel trung tâm, mã hóa kết quả thành các bit và ghép chúng thành một mã nhị phân. Histogram các mã trong một vùng mô tả tần suất xuất hiện của những cấu trúc texture cục bộ. Vì vậy B đúng: LBP không chỉ đo màu và không khởi đầu từ một biểu diễn hình dạng toàn cục, dù histogram LBP có thể được tổng hợp thành đặc trưng của vùng hoặc ảnh. Đối chiếu: [nghiên cứu LBP của Đại học Oulu](https://oulurepo.oulu.fi/handle/10024/35942).

</details>

### Câu 404
Nguồn PDF: trang 55

SURF (Speeded Up Robust Features) so với SIFT có ưu điểm gì?

- A. Chính xác hơn trong mọi trường hợp
- B. Nhanh hơn nhờ sử dụng Integral Image và Haar wavelet
- C. Bất biến với nhiều phép biến đổi hơn
- D. Không cần tham số

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Nhanh hơn nhờ sử dụng Integral Image và Haar wavelet

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* SURF dùng box filters xấp xỉ đạo hàm Gaussian để phát hiện điểm và tính tổng vùng nhanh qua integral image. Các đáp ứng Haar wavelet cũng có thể tính hiệu quả bằng integral image để xác định hướng và xây dựng descriptor. Những lựa chọn này giảm chi phí tính toán so với cách xây dựng SIFT truyền thống; lợi thế tốc độ không bảo đảm SURF chính xác hơn trong mọi tình huống, không cần tham số hoặc bất biến với mọi phép biến đổi. Đối chiếu: [giới thiệu SURF](https://docs.opencv.org/4.x/df/dd2/tutorial_py_surf_intro.html).

</details>

### Câu 405
Nguồn PDF: trang 55

MSER (Maximally Stable Extremal Regions) phát hiện gì?

- A. Điểm góc
- B. Vùng ổn định qua nhiều ngưỡng threshold (region với ranh giới bền vững)
- C. Đường biên
- D. Đường thẳng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Vùng ổn định qua nhiều ngưỡng threshold (region với ranh giới bền vững)

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* MSER xét các thành phần liên thông khi thay đổi ngưỡng cường độ, rồi chọn những vùng có diện tích thay đổi tương đối ít trong một khoảng ngưỡng. Tính ổn định này giúp nhận lại một vùng qua những ảnh có điều kiện quan sát khác nhau, thay vì chỉ tìm một góc hoặc đường thẳng đơn lẻ. Cụm 'ranh giới bền vững' trong B là cách diễn đạt trực quan; tiêu chí MSER chủ yếu dựa trên sự ổn định của diện tích vùng theo ngưỡng, không đòi đường biên bất động tuyệt đối.

</details>

### Câu 406
Nguồn PDF: trang 55

Feature matching bằng NNC (Nearest Neighbor Classifier) hoạt động như thế nào?

- A. So sánh tất cả cặp đặc trưng
- B. Tìm đặc trưng trong tập tham chiếu có khoảng cách nhỏ nhất đến đặc trưng truy vấn
- C. Chọn ngẫu nhiên
- D. Dùng màu sắc để matching

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Tìm đặc trưng trong tập tham chiếu có khoảng cách nhỏ nhất đến đặc trưng truy vấn

**Giải thích:** <!-- TODO -->

</details>

### Câu 407
Nguồn PDF: trang 55

Lowe's ratio test trong SIFT matching dùng để làm gì?

- A. Tìm scale tốt nhất
- B. Loại bỏ matches không rõ ràng; nếu khoảng cách tới NN nhỏ nhất và nhì quá gần nhau → match không đáng tin
- C. Tính homography
- D. Tăng số lượng matches

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Loại bỏ matches không rõ ràng; nếu khoảng cách tới NN nhỏ nhất và nhì quá gần nhau → match không đáng tin

**Giải thích:** <!-- TODO -->

</details>

### Câu 408
Nguồn PDF: trang 55

Template matching (so khớp mẫu) dùng kỹ thuật nào?

- A. Gaussian filter
- B. Cross-correlation hoặc SSD, tìm vùng ảnh giống mẫu nhất
- C. FFT
- D. PCA

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Cross-correlation hoặc SSD, tìm vùng ảnh giống mẫu nhất

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* Template matching trượt mẫu qua ảnh và tính một điểm so khớp ở mỗi vị trí. Với cross-correlation, thường chọn điểm cao nhất; với SSD, chọn điểm thấp nhất vì đó là sai khác nhỏ nhất. FFT có thể tăng tốc tính correlation, nhưng là cách triển khai chứ không thay thế tiêu chí tương đồng ở B. Đối chiếu: [API matchTemplate](https://docs.opencv.org/4.x/df/dfb/group__imgproc__object.html).

</details>

### Câu 409
Nguồn PDF: trang 55

Đặc trưng góc (corner) có ưu điểm gì cho image matching?

- A. Dễ tính
- B. Rõ ràng, bền vững, dễ localize và match giữa các ảnh
- C. Ít bị ảnh hưởng bởi scale
- D. Chỉ xuất hiện ở biên

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Rõ ràng, bền vững, dễ localize và match giữa các ảnh

**Giải thích:** <!-- TODO -->

</details>

### Câu 410
Nguồn PDF: trang 56

Zernike moments khác Hu's moments ở điểm nào?

- A. Zernike không bất biến với quay
- B. Zernike là hệ trực giao hoàn chỉnh trên đĩa tròn đơn vị, ít nhiễu hơn khi tái tạo
- C. Zernike nhanh hơn
- D. Chúng giống nhau

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Zernike là hệ trực giao hoàn chỉnh trên đĩa tròn đơn vị, ít nhiễu hơn khi tái tạo

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* Zernike moments biểu diễn ảnh trên hệ đa thức trực giao trong đĩa đơn vị, nên các hệ số mô tả những thành phần cơ sở riêng và có thể dùng để tái tạo ảnh. Bảy bất biến Hu là các tổ hợp của moments hình học bậc thấp, không phải một hệ cơ sở trực giao đầy đủ để tái tạo. **Lưu ý:** tính trực giao giúp giảm dư thừa nhưng không bảo đảm 'ít nhiễu hơn' trong mọi trường hợp; độ bền còn phụ thuộc bậc moments, chuẩn hóa và lấy mẫu. Đối chiếu: [Teague, Image analysis via moments](https://opg.optica.org/abstract.cfm?uri=josa-70-8-920).

</details>

### Câu 411
Nguồn PDF: trang 56

Điều nào đúng về PHOG (Pyramid HOG)?

- A. HOG tính ở nhiều tỉ lệ scale khác nhau
- B. HOG tính ở nhiều mức độ phân giải không gian (spatial pyramid)
- C. HOG kết hợp với Gabor filter
- D. HOG chỉ tính ở 1 mức

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. HOG tính ở nhiều mức độ phân giải không gian (spatial pyramid)

**Giải thích:** <!-- TODO -->

</details>

### Câu 412
Nguồn PDF: trang 56

Keypoint descriptor trong SIFT mô tả gì?

- A. Vị trí của keypoint
- B. Đặc trưng gradient hướng xung quanh keypoint trong vùng 4×4 với 8 hướng
- C. Màu sắc xung quanh keypoint
- D. Kích thước của keypoint

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Đặc trưng gradient hướng xung quanh keypoint trong vùng 4×4 với 8 hướng

**Giải thích:** <!-- TODO -->

</details>

### Câu 413
Nguồn PDF: trang 56

FREAK (Fast Retina Keypoint) được lấy cảm hứng từ đâu?

- A. Cấu trúc của bộ nhớ máy tính
- B. Cấu trúc của võng mạc mắt người (retina)
- C. Thuật toán SIFT
- D. Bộ lọc Gabor

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Cấu trúc của võng mạc mắt người (retina)

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* FREAK lấy cảm hứng từ cách lấy mẫu ở võng mạc, với mẫu lấy thông tin dày hơn gần tâm và thưa hơn khi ra xa. Descriptor mã hóa các phép so sánh cường độ giữa những vùng lấy mẫu thành chuỗi bit, nhờ đó có thể so khớp bằng Hamming distance. B chỉ nguồn cảm hứng thiết kế, không có nghĩa thuật toán mô phỏng đầy đủ hoạt động sinh học của mắt; tên của nó cũng không xuất phát từ bộ nhớ máy tính hoặc bộ lọc Gabor. Đối chiếu: [bài báo FREAK](https://citeseerx.ist.psu.edu/document?doi=bfe2e9b42cca691dcddca8ca90a0d75c67cead58&repid=rep1&type=pdf).

</details>

### Câu 414
Nguồn PDF: trang 56

Điều nào đúng về GLCM và hướng tính toán?

- A. Chỉ tính theo 1 hướng
- B. Tính theo nhiều hướng (0°, 45°, 90°, 135°) và khoảng cách khác nhau
- C. Không phụ thuộc hướng
- D. Chỉ tính theo hướng ngang

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Tính theo nhiều hướng (0°, 45°, 90°, 135°) và khoảng cách khác nhau

**Giải thích:** <!-- TODO -->

</details>

### Câu 415
Nguồn PDF: trang 56

Image Moments dùng để mô tả gì?

- A. Thông tin màu
- B. Thông tin hình dạng và phân phối của pixel trong ảnh/vùng
- C. Thông tin texture
- D. Thông tin chuyển động

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Thông tin hình dạng và phân phối của pixel trong ảnh/vùng

**Giải thích:** <!-- TODO -->

</details>

### Câu 416
Nguồn PDF: trang 56

Central moments (moment trung tâm) khác raw moments ở điểm nào?

- A. Central moments phức tạp hơn
- B. Central moments bất biến với phép tịnh tiến (tính quanh centroid)
- C. Central moments nhanh hơn
- D. Không có sự khác biệt

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Central moments bất biến với phép tịnh tiến (tính quanh centroid)

**Giải thích:** <!-- TODO -->

</details>

### Câu 417
Nguồn PDF: trang 56

Điều nào đúng về BRISK (Binary Robust Invariant Scalable Keypoints)?

- A. Dùng floating-point descriptor
- B. Dùng binary descriptor, nhanh hơn SIFT/SURF nhờ Hamming distance
- C. Không bất biến với scale
- D. Cần nhiều bộ nhớ hơn SIFT

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Dùng binary descriptor, nhanh hơn SIFT/SURF nhờ Hamming distance

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* BRISK tạo descriptor nhị phân bằng so sánh các cặp mẫu cường độ và có cơ chế chuẩn hóa hướng, scale cho keypoint. Chuỗi bit có thể so khớp nhanh bằng XOR và đếm bit khác nhau, thay cho nhiều phép toán trên vector số thực như SIFT hoặc SURF. Vì vậy B nêu lợi thế tính toán hợp lý; tốc độ cả pipeline vẫn phụ thuộc detector, số keypoint và triển khai, không thể chỉ quy toàn bộ chênh lệch cho Hamming distance. Đối chiếu: [bài báo BRISK](https://dev.ipol.im/~reyotero/bib/bib_all/2011_Leutnegger_Chli_brisk_iccv.pdf).

</details>

### Câu 418
Nguồn PDF: trang 57

Khoảng cách Hamming được dùng để so sánh descriptor nào?

- A. SIFT descriptor
- B. Binary descriptor (BRISK, ORB)
- C. HOG descriptor
- D. Zernike moments

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Binary descriptor (BRISK, ORB)

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* Khoảng cách Hamming đếm số vị trí bit khác nhau giữa hai chuỗi cùng độ dài, nên phù hợp với descriptor nhị phân như BRISK và ORB. Ví dụ 1010 và 1001 khác nhau ở hai vị trí, cho khoảng cách 2; có thể tính bằng XOR rồi đếm bit 1. SIFT và HOG chuẩn là vector giá trị số, nên thường dùng khoảng cách trên vector thay vì diễn giải mỗi tọa độ như một bit. Đối chiếu: [chuẩn khoảng cách cho descriptor](https://docs.opencv.org/4.x/dc/dc3/tutorial_py_matcher.html).

</details>

### Câu 419
Nguồn PDF: trang 57

ORB (Oriented FAST and Rotated BRIEF) là sự kết hợp của gì?

- A. SIFT và SURF
- B. FAST keypoint detector và BRIEF descriptor (với thêm rotation invariance)
- C. Harris và HOG
- D. MSER và GLCM

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. FAST keypoint detector và BRIEF descriptor (với thêm rotation invariance)

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* ORB dùng FAST để phát hiện keypoint, bổ sung ước lượng hướng từ phân bố cường độ rồi định hướng lại mẫu so sánh của BRIEF. Bởi BRIEF nguyên bản không tự chuẩn hóa hướng, bước xoay mẫu giúp descriptor bền hơn khi ảnh quay. Tên ORB vì thế mô tả sự kết hợp FAST và BRIEF có xử lý hướng, không phải ghép SIFT với SURF; tính bền với quay cũng không phải bất biến tuyệt đối trước mọi biến đổi hình học. Đối chiếu: [cấu trúc ORB](https://docs.opencv.org/4.x/d1/d89/tutorial_py_orb.html).

</details>

### Câu 420
Nguồn PDF: trang 57

Điều nào KHÔNG phải là ứng dụng của local feature matching?

- A. Panorama stitching (ghép ảnh)
- B. Phân loại màu sắc đơn giản
- C. 3D reconstruction
- D. Image retrieval

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Phân loại màu sắc đơn giản

**Giải thích:** <!-- TODO -->

</details>

### Câu 421
Nguồn PDF: trang 57

Histogram Oriented Gradients (HOG) được Dalal và Triggs giới thiệu năm nào và cho ứng dụng nào?

- A. 1995, phát hiện khuôn mặt
- B. 2005, phát hiện người đi bộ (pedestrian detection)
- C. 2012, phân loại ảnh
- D. 2000, nhận dạng ký tự

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. 2005, phát hiện người đi bộ (pedestrian detection)

**Giải thích:** <!-- TODO -->

</details>

### Câu 422
Nguồn PDF: trang 57

Điều nào đúng về Integral Image (Summed Area Table)?

- A. Lưu trữ histogram của ảnh
- B. Lưu tổng tích lũy của pixel, cho phép tính nhanh tổng bất kỳ vùng hình chữ nhật trong O(1)
- C. Lưu gradient của ảnh
- D. Là cách biểu diễn ảnh trong miền tần số

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Lưu tổng tích lũy của pixel, cho phép tính nhanh tổng bất kỳ vùng hình chữ nhật trong O(1)

**Giải thích:** <!-- TODO -->

</details>

### Câu 423
Nguồn PDF: trang 57

Điều nào đúng về Image Retrieval dựa trên đặc trưng?

- A. Tìm ảnh dựa trên text mô tả
- B. Tìm ảnh tương đồng trong cơ sở dữ liệu dựa trên khoảng cách đặc trưng (feature distance)
- C. Tìm ảnh theo kích thước
- D. Tìm ảnh theo ngày tháng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Tìm ảnh tương đồng trong cơ sở dữ liệu dựa trên khoảng cách đặc trưng (feature distance)

**Giải thích:** <!-- TODO -->

</details>

### Câu 424
Nguồn PDF: trang 57

Harris corner detection có tính bất biến nào? (Chọn tất cả đúng)

- A. Bất biến với phép tịnh tiến
- B. Bất biến với phép quay nhỏ
- C. Bất biến với thay đổi chiếu sáng đến mức nhất định
- D. Bất biến với scale

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Bất biến với phép tịnh tiến; B. Bất biến với phép quay nhỏ; C. Bất biến với thay đổi chiếu sáng đến mức nhất định

**Giải thích:** <!-- TODO -->

</details>

### Câu 425
Nguồn PDF: trang 57

Tại sao SIFT được coi là mạnh mẽ (robust) cho image matching?

- A. Vì nó rất nhanh
- B. Vì đặc trưng SIFT bất biến với scale, rotation và chiếu sáng, nên matching tin cậy hơn
- C. Vì nó không cần tham số
- D. Vì descriptor ngắn

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Vì đặc trưng SIFT bất biến với scale, rotation và chiếu sáng, nên matching tin cậy hơn

**Giải thích:** <!-- TODO -->

</details>

### Câu 426
Nguồn PDF: trang 58

Tại sao Harris corner không bất biến với scale?

- A. Vì Harris không tính gradient
- B. Vì Harris không xây dựng scale space; cùng vật thể ở scale khác nhau có thể không cho ra corner
- C. Vì Harris quá nhanh
- D. Vì Harris chỉ dùng cho ảnh nhị phân

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Vì Harris không xây dựng scale space; cùng vật thể ở scale khác nhau có thể không cho ra corner

**Giải thích:** <!-- TODO -->

</details>

### Câu 427
Nguồn PDF: trang 58

Điều gì SIFT thực hiện để gán orientation cho keypoint?

- A. Dùng hướng của gradient lớn nhất trong vùng
- B. Tính histogram gradient hướng xung quanh keypoint, chọn hướng dominant
- C. Dùng hướng cạnh gần nhất
- D. Gán hướng ngẫu nhiên

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Tính histogram gradient hướng xung quanh keypoint, chọn hướng dominant

**Giải thích:** <!-- TODO -->

</details>

### Câu 428
Nguồn PDF: trang 58

Điều nào đúng về bất biến illumination của SIFT?

- A. Hoàn toàn bất biến với mọi thay đổi chiếu sáng
- B. Bất biến với thay đổi chiếu sáng additive và multiplicative ở mức nhất định
- C. Không bất biến với chiếu sáng
- D. Chỉ bất biến với chiếu sáng additive

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Bất biến với thay đổi chiếu sáng additive và multiplicative ở mức nhất định

**Giải thích:** <!-- TODO -->

</details>

### Câu 429
Nguồn PDF: trang 58

Đặc trưng nào sau đây thường được dùng cho Face recognition?

- A. HOG
- B. Eigenfaces (PCA) hoặc LBP
- C. GLCM
- D. Hu moments

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Eigenfaces (PCA) hoặc LBP

**Giải thích:** <!-- TODO -->

</details>

### Câu 430
Nguồn PDF: trang 58

Điều nào đúng về Co-HOG (Co-occurrence HOG)?

- A. HOG chỉ dùng cho ảnh grayscale
- B. Mở rộng HOG bằng cách xem xét sự tương quan (co-occurrence) giữa các hướng gradient
- C. Chậm hơn HOG chuẩn 10 lần
- D. Chỉ dùng cho texture

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Mở rộng HOG bằng cách xem xét sự tương quan (co-occurrence) giữa các hướng gradient

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* HOG thông thường thống kê hướng gradient trong từng ô, còn Co-HOG thống kê sự đồng xuất hiện của cặp hướng tại những vị trí có độ lệch xác định. Thông tin cặp này bổ sung quan hệ không gian giữa các gradient, giúp biểu diễn cấu trúc hình dạng phong phú hơn một histogram hướng riêng lẻ. B đúng về cơ chế mở rộng; không có quy luật luôn chậm hơn mười lần, và phương pháp gốc được dùng cho phát hiện người chứ không giới hạn ở texture. Đối chiếu: [bài báo Co-HOG](https://www.jstage.jst.go.jp/article/ipsjtcva/2/0/2_0_39/_article).

</details>

### Câu 431
Nguồn PDF: trang 58

Điều nào KHÔNG đúng về SIFT?

- A. Bất biến với scale
- B. Bất biến với affine transformation hoàn toàn
- C. Bất biến với rotation
- D. Dùng 128-D descriptor

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Bất biến với affine transformation hoàn toàn

**Giải thích:** <!-- TODO -->

</details>

### Câu 432
Nguồn PDF: trang 58

Affine-covariant regions khác scale-covariant regions (SIFT) ở điểm nào?

- A. Không có sự khác biệt
- B. Affine covariant xử lý được cả perspective distortion và slant, không chỉ scale và rotation
- C. Affine chậm hơn
- D. Scale-covariant mạnh hơn

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Affine covariant xử lý được cả perspective distortion và slant, không chỉ scale và rotation

**Giải thích:** <!-- TODO -->

</details>

### Câu 433
Nguồn PDF: trang 59

Geometric verification trong image matching dùng để làm gì?

- A. Tính histogram
- B. Xác nhận tính hợp lệ của matches bằng cách kiểm tra tính nhất quán hình học (ví dụ RANSAC với homography)
- C. Tăng tốc matching
- D. Phát hiện keypoints

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Xác nhận tính hợp lệ của matches bằng cách kiểm tra tính nhất quán hình học (ví dụ RANSAC với homography)

**Giải thích:** <!-- TODO -->

</details>

### Câu 434
Nguồn PDF: trang 59

Điều nào đúng về Scale Space Extrema Detection trong SIFT?

- A. Chỉ tìm điểm cực đại
- B. Tìm cực đại và cực tiểu của DoG qua scale và không gian ảnh
- C. Chỉ tìm điểm cực tiểu
- D. Không liên quan đến scale

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Tìm cực đại và cực tiểu của DoG qua scale và không gian ảnh

**Giải thích:** <!-- TODO -->

</details>

### Câu 435
Nguồn PDF: trang 59

Tại sao cần "Keypoint Localization" (refinement) sau bước phát hiện keypoint thô?

- A. Để tăng số keypoints
- B. Để loại bỏ keypoints tại cạnh/ảnh hưởng bởi contrast thấp, tăng chính xác vị trí
- C. Để giảm kích thước descriptor
- D. Để tính orientation

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Để loại bỏ keypoints tại cạnh/ảnh hưởng bởi contrast thấp, tăng chính xác vị trí

**Giải thích:** <!-- TODO -->

</details>

### Câu 436
Nguồn PDF: trang 59

Điều nào đúng về Fourier Descriptors cho hình dạng?

- A. Tính Fourier trên ảnh 2D
- B. Tính DFT của boundary contour (1D signal), dùng hệ số Fourier để mô tả hình dạng
- C. Chỉ dùng cho hình tròn
- D. Không bất biến với scale

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Tính DFT của boundary contour (1D signal), dùng hệ số Fourier để mô tả hình dạng

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* Lấy các điểm biên theo thứ tự và biểu diễn chúng thành tín hiệu một chiều, chẳng hạn z(k) = x(k) + i*y(k), rồi tính DFT để thu các hệ số Fourier. Các hệ số tần số thấp mô tả hình dạng tổng thể, còn tần số cao mang chi tiết biên. Đây không phải Fourier trực tiếp trên toàn ảnh 2D; có thể chuẩn hóa descriptor để giảm ảnh hưởng của tịnh tiến, scale, quay hoặc điểm bắt đầu, nên D không phải hạn chế bắt buộc. Đối chiếu: [Fourier descriptors của đường biên](https://homepages.inf.ed.ac.uk/rbf/CVonline/LOCAL_COPIES/MORSE/boundary-rep-desc.pdf).

</details>

### Câu 437
Nguồn PDF: trang 59

Điều nào đúng về Image stitching (ghép ảnh panorama)?

- A. Không cần feature matching
- B. Dùng SIFT hoặc ORB để tìm matches, ước lượng homography, warp và blend ảnh
- C. Chỉ dùng cho ảnh màu
- D. Cần ảnh chụp cùng lúc

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Dùng SIFT hoặc ORB để tìm matches, ước lượng homography, warp và blend ảnh

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* Một pipeline ghép ảnh dựa trên đặc trưng tìm keypoint và descriptor, ghép các điểm tương ứng rồi ước lượng homography bền vững trước matches sai. Warp đưa ảnh về cùng hệ tọa độ, còn blending xử lý phần chồng lấp để giảm đường nối và khác biệt sáng. B mô tả pipeline phổ biến; homography phù hợp nhất khi cảnh gần phẳng hoặc camera quay quanh tâm, còn parallax do vật thể ở nhiều độ sâu có thể làm ảnh ghép lệch. Đối chiếu: [matching và homography](https://docs.opencv.org/4.x/d1/de0/tutorial_py_feature_homography.html).

</details>

### Câu 438
Nguồn PDF: trang 59

Phương pháp nào dùng để phát hiện keypoints nhanh nhất?

- A. SIFT
- B. FAST (Features from Accelerated Segment Test)
- C. Harris
- D. SURF

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. FAST (Features from Accelerated Segment Test)

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* FAST phát hiện góc bằng phép kiểm tra một dãy pixel trên vòng tròn quanh điểm ứng viên và có thể loại sớm nhiều điểm không thỏa điều kiện. Cách kiểm tra đơn giản được thiết kế cho tốc độ cao, khác với các bước xây dựng scale-space phức tạp hơn ở SIFT hoặc SURF. **Lưu ý:** B là lựa chọn dự kiến trong nhóm thuật toán của câu hỏi, không phải kết luận FAST luôn nhanh nhất trên mọi phần cứng, thư viện và bộ tham số. Đối chiếu: [thuật toán FAST](https://docs.opencv.org/4.x/df/d0c/tutorial_py_fast.html).

</details>

### Câu 439
Nguồn PDF: trang 59

Điều nào đúng về Binary descriptor so với floating-point descriptor?

- A. Binary descriptor chính xác hơn
- B. Binary descriptor nhanh hơn (Hamming distance) nhưng có thể kém chính xác hơn
- C. Binary descriptor bất biến hơn
- D. Binary descriptor cần nhiều bộ nhớ hơn

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Binary descriptor nhanh hơn (Hamming distance) nhưng có thể kém chính xác hơn

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* Descriptor nhị phân lưu các kết quả so sánh thành bit, cho phép tính Hamming distance bằng thao tác bit nhanh và thường có biểu diễn gọn. Đổi lại, lượng thông tin và độ bền với biến đổi ảnh phụ thuộc cách chọn phép so sánh, nên hiệu quả matching có thể thấp hơn hoặc cao hơn một descriptor số thực trên từng nhiệm vụ. B diễn đạt một đánh đổi có thể xảy ra, không phải quy luật binary luôn kém chính xác; A, C, D cũng không đúng cho mọi thiết kế. Đối chiếu: [matching descriptor nhị phân và số thực](https://docs.opencv.org/4.x/dc/dc3/tutorial_py_matcher.html).

</details>

### Câu 440
Nguồn PDF: trang 60

Điều nào đúng về Spatial Pyramid Matching (SPM)?

- A. Không cần chia ảnh
- B. Chia ảnh thành grid ở nhiều scale, tính đặc trưng cho từng ô, kết hợp lại → thêm thông tin vị trí
- C. Chỉ dùng cho HOG
- D. Thay thế Bag of Words

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Chia ảnh thành grid ở nhiều scale, tính đặc trưng cho từng ô, kết hợp lại → thêm thông tin vị trí

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* Spatial Pyramid Matching chia ảnh thành các lưới ngày càng mịn, tính histogram đặc trưng cục bộ trong từng ô rồi tổng hợp chúng theo các mức. Hai ảnh có cùng số lượng visual words nhưng bố trí khác nhau nhờ đó không còn bị biểu diễn hoàn toàn giống nhau như bag-of-features không xét vị trí. Nó bổ sung cấu trúc không gian cho mô hình bag-of-words, không chỉ dùng với HOG và không loại bỏ nhu cầu chia ảnh. Đối chiếu: [bài báo Spatial Pyramid Matching](https://slazebni.cs.illinois.edu/publications/cvpr06b.pdf).

</details>

### Câu 441
Nguồn PDF: trang 60

Điều gì KHÔNG phải là bước trong SIFT?

- A. Scale-space extrema detection
- B. Affine transformation estimation
- C. Keypoint localization
- D. Descriptor computation

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Affine transformation estimation

**Giải thích:** <!-- TODO -->

</details>

### Câu 442
Nguồn PDF: trang 60

Tại sao đặc trưng SIFT dùng 4×4 grid × 8 orientations = 128 chiều?

- A. Vì 128 là số đẹp
- B. Vì đây là trade-off giữa discriminability và robustness; nhiều hơn → quá nhạy với nhiễu
- C. Vì đây là giới hạn bộ nhớ
- D. Vì Lowe đã chọn ngẫu nhiên

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Vì đây là trade-off giữa discriminability và robustness; nhiều hơn → quá nhạy với nhiễu

**Giải thích:** <!-- TODO -->

</details>

### Câu 443
Nguồn PDF: trang 60

Điều nào đúng về vấn đề "aperture problem" trong optical flow?

- A. Liên quan đến kích thước aperture của camera
- B. Chỉ nhìn qua một cửa sổ nhỏ, không thể xác định đủ hướng chuyển động; chỉ thấy component dọc theo biên
- C. Là vấn đề trong phát hiện biên
- D. Chỉ xảy ra với camera pin-hole

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Chỉ nhìn qua một cửa sổ nhỏ, không thể xác định đủ hướng chuyển động; chỉ thấy component dọc theo biên

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* Quan sát một đoạn biên thẳng trong cửa sổ nhỏ chỉ cung cấp một ràng buộc chuyển động, nên không đủ xác định cả hai thành phần optical flow. **Lưu ý: đáp án nguồn có lỗi diễn đạt:** thành phần quan sát được là theo gradient, tức vuông góc với biên, không phải 'dọc theo biên'; thành phần tiếp tuyến với biên chưa xác định. Cần thêm thông tin như gradient theo nhiều hướng ở góc hoặc giả thiết chuyển động trong lân cận để giải mơ hồ này. Đối chiếu: [aperture problem và normal flow](https://people.csail.mit.edu/fredo/comp-photo-book/07-matching-pixels-across-space-and-time-06-optical-flow.html).

</details>

### Câu 444
Nguồn PDF: trang 60

Điều nào đúng về SSD (Sum of Squared Differences) trong template matching?

- A. SSD lớn hơn → match tốt hơn
- B. SSD nhỏ hơn → match tốt hơn (hai vùng giống nhau hơn)
- C. SSD không phụ thuộc vào độ sáng
- D. SSD bất biến với rotation

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. SSD nhỏ hơn → match tốt hơn (hai vùng giống nhau hơn)

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* SSD cộng các bình phương sai khác tại pixel tương ứng, nên chọn vị trí có SSD nhỏ nhất để tìm vùng giống mẫu nhất. Nếu vùng bằng mẫu thì SSD bằng 0; thay đổi độ sáng có thể tăng sai khác dù cấu trúc giống nhau. Do đó SSD nguyên bản không bất biến với độ sáng hoặc quay, và chọn giá trị lớn nhất sẽ ưu tiên vùng khác mẫu. Đối chiếu: [TM_SQDIFF](https://docs.opencv.org/4.x/df/dfb/group__imgproc__object.html).

</details>

### Câu 445
Nguồn PDF: trang 60

Feature matching tốt yêu cầu descriptor phải có tính chất gì?

- A. Nhanh tính toán
- B. Đặc trưng (distinctive) để phân biệt và bền vững (robust) trước biến đổi
- C. Kích thước nhỏ nhất có thể
- D. Chỉ cần 2 chiều

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Đặc trưng (distinctive) để phân biệt và bền vững (robust) trước biến đổi

**Giải thích:** <!-- TODO -->

</details>

### Câu 446
Nguồn PDF: trang 60

Điều nào đúng về việc chọn keypoints (đặc điểm nổi bật) trong ảnh?

- A. Chọn tất cả pixel
- B. Chọn các điểm có tính distinctive cao: góc, blobs, không phải vùng phẳng hay cạnh đơn
- C. Chỉ chọn pixel sáng
- D. Chọn pixel ngẫu nhiên

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Chọn các điểm có tính distinctive cao: góc, blobs, không phải vùng phẳng hay cạnh đơn

**Giải thích:** <!-- TODO -->

</details>

### Câu 447
Nguồn PDF: trang 61

Điều nào đúng về phân loại đặc trưng trong image retrieval?

- A. Luôn dùng đặc trưng màu
- B. Tùy ứng dụng: màu (histogram), texture (GLCM, LBP), hình dạng (HOG, moments), hoặc kết hợp
- C. Chỉ dùng đặc trưng cục bộ
- D. Chỉ dùng đặc trưng toàn cục

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Tùy ứng dụng: màu (histogram), texture (GLCM, LBP), hình dạng (HOG, moments), hoặc kết hợp

**Giải thích:** <!-- TODO -->

</details>

### Câu 448
Nguồn PDF: trang 61

Điều nào KHÔNG đúng về Harris Corner Detector?

- A. Bất biến với phép quay
- B. Bất biến với scale
- C. Bền vững với nhiễu Gaussian
- D. Tính dựa trên ma trận cấu trúc M

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Bất biến với scale

**Giải thích:** <!-- TODO -->

</details>

### Câu 449
Nguồn PDF: trang 61

Điều nào đúng về cách tính cross-correlation trong template matching?

- A. Giống convolution với kernel là template
- B. Correlation f(x) ⋆ t(x) = ∑f(x+τ)t(τ), giống convolution nhưng không flip template
- C. Cần biến đổi Fourier
- D. Chỉ hoạt động với ảnh nhị phân

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Correlation f(x) ⋆ t(x) = ∑f(x+τ)t(τ), giống convolution nhưng không flip template

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* Cross-correlation nhân mẫu với từng vùng ảnh ở vị trí đang xét rồi cộng các tích, không đảo thứ tự không gian của mẫu. Convolution theo định nghĩa toán học có bước đảo kernel, nên hai phép chỉ trùng trong những trường hợp như kernel đối xứng. FFT là một cách tính nhanh chứ không phải điều kiện bắt buộc, và correlation không chỉ dùng cho ảnh nhị phân. Đối chiếu: [TM_CCORR](https://docs.opencv.org/4.x/df/dfb/group__imgproc__object.html).

</details>

### Câu 450
Nguồn PDF: trang 61

Điều nào đúng về ứng dụng SURF trong thực tế?

- A. Chỉ dùng trong nghiên cứu
- B. Dùng trong AR (Augmented Reality), tracking, object recognition thời gian thực
- C. Chậm hơn SIFT
- D. Không có bản quyền, miễn phí hoàn toàn

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Dùng trong AR (Augmented Reality), tracking, object recognition thời gian thực

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* Các keypoint và descriptor SURF cho phép tìm lại chi tiết ảnh qua các khung hình hoặc góc nhìn, nên có thể làm thành phần của tracking, nhận dạng hoặc căn chỉnh đối tượng cho AR. Integral image và các bộ lọc xấp xỉ giúp giảm chi phí, nhưng khả năng chạy thời gian thực vẫn phụ thuộc ảnh, số điểm và phần cứng. B vì vậy mô tả ứng dụng khả thi, không phải bảo đảm tốc độ; tuyên bố 'miễn phí hoàn toàn' cũng không thể suy ra chỉ từ tính năng thuật toán. Đối chiếu: [cơ chế và tốc độ SURF](https://docs.opencv.org/4.x/df/dd2/tutorial_py_surf_intro.html).

</details>

### Câu 451
Nguồn PDF: trang 61

Điều nào đúng về bản chất của Image matching?

- A. Chỉ dùng cho ảnh giống hệt nhau
- B. Tìm correspondence (điểm tương ứng) giữa hai hoặc nhiều ảnh của cùng cảnh
- C. Ghép màu sắc của ảnh
- D. Không cần đặc trưng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Tìm correspondence (điểm tương ứng) giữa hai hoặc nhiều ảnh của cùng cảnh

**Giải thích:** <!-- TODO -->

</details>

### Câu 452
Nguồn PDF: trang 61

SIFT được phát triển bởi ai và năm nào?

- A. Fei-Fei Li, 2009
- B. David Lowe, 1999/2004
- C. Hubel & Wiesel, 1960
- D. Viola & Jones, 2001

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. David Lowe, 1999/2004

**Giải thích:** <!-- TODO -->

</details>

### Câu 453
Nguồn PDF: trang 61

Điều nào đúng về tính "affine invariance" của đặc trưng?

- A. Bất biến với mọi phép biến đổi
- B. Bất biến với các phép biến đổi affine bao gồm translation, rotation, scale, và shear
- C. Chỉ bất biến với rotation
- D. Không thể đạt được

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Bất biến với các phép biến đổi affine bao gồm translation, rotation, scale, và shear

**Giải thích:** <!-- TODO -->

</details>

### Câu 454
Nguồn PDF: trang 61

Điều nào đúng về cách SIFT xây dựng pyramid trong scale space?

- A. Chỉ dùng 1 octave
- B. Xây dựng Gaussian pyramid với nhiều octaves; mỗi octave tăng gấp đôi σ và giảm resolution
- C. Chỉ zoom in
- D. Chỉ zoom out

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Xây dựng Gaussian pyramid với nhiều octaves; mỗi octave tăng gấp đôi σ và giảm resolution

**Giải thích:** <!-- TODO -->

</details>

### Câu 455
Nguồn PDF: trang 62

Điều nào đúng về ma trận cấu trúc M trong Harris?

- A. M là ma trận 1×1
- B. M = Σ [Ix², IxIy; IxIy, Iy²] tổng hóa trên cửa sổ xung quanh điểm
- C. M không phụ thuộc vào gradient
- D. M là ma trận identity

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. M = Σ [Ix², IxIy; IxIy, Iy²] tổng hóa trên cửa sổ xung quanh điểm

**Giải thích:** <!-- TODO -->

</details>

### Câu 456
Nguồn PDF: trang 62

Eigenvalues của ma trận M trong Harris cho biết điều gì?

- A. Màu sắc tại điểm
- B. λ1, λ2: biên độ thay đổi theo 2 hướng chính; cả hai lớn → corner
- C. Khoảng cách đến biên
- D. Tần số ảnh tại điểm

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. λ1, λ2: biên độ thay đổi theo 2 hướng chính; cả hai lớn → corner

**Giải thích:** <!-- TODO -->

</details>

### Câu 457
Nguồn PDF: trang 62

Điều nào đúng về ứng dụng đặc trưng texture GLCM trong y tế?

- A. Chỉ dùng để tăng tương phản
- B. Phân loại mô (benign/malignant) dựa trên đặc trưng texture trong ảnh siêu âm, MRI
- C. Phát hiện biên
- D. Nén ảnh y tế

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Phân loại mô (benign/malignant) dựa trên đặc trưng texture trong ảnh siêu âm, MRI

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* Từ GLCM của vùng mô, có thể tính các đặc trưng như contrast, energy hoặc homogeneity rồi đưa vào một mô hình phân loại đã huấn luyện với nhãn tương ứng. Khi các loại mô có phân bố texture khác nhau, những đặc trưng này có thể hỗ trợ phân biệt nhóm lành tính và ác tính; một nghiên cứu đã dùng GLCM kết hợp SVM cho ảnh siêu âm khối u gan. Đây là ứng dụng phân tích có đánh giá trên dữ liệu, không phải quy tắc GLCM tự chẩn đoán chính xác mọi ảnh MRI hay siêu âm. Đối chiếu: [nghiên cứu GLCM cho ảnh siêu âm](https://www.sciencedirect.com/science/article/abs/pii/S0957417410001065).

</details>

### Câu 458
Nguồn PDF: trang 62

Điều nào KHÔNG phải là ứng dụng của feature matching?

- A. Object recognition
- B. Image compression
- C. Visual SLAM
- D. 3D reconstruction

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Image compression

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* Feature matching tìm những điểm hoặc vùng tương ứng giữa các ảnh, phục vụ đối chiếu đối tượng, theo dõi mốc trong SLAM và tạo ràng buộc hình học cho dựng hình 3D. Nén ảnh thông thường nhằm mã hóa dữ liệu gọn hơn, không phải nhiệm vụ trực tiếp xác lập các cặp đặc trưng, nên B là đáp án dự kiến. **Lưu ý:** không nên hiểu rằng feature matching tuyệt đối không thể xuất hiện trong một hệ nén chuyên biệt; câu hỏi phân biệt các ứng dụng điển hình, không chứng minh sự loại trừ cho mọi hệ thống.

</details>

### Câu 459
Nguồn PDF: trang 62

Điều nào đúng về Hu's moments ứng dụng trong nhận dạng ký tự?

- A. Không thể dùng cho ký tự
- B. Mô tả hình dạng ký tự bất biến
- C. Không thể dùng cho ký tự
- D. Cần 256 chiều

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Mô tả hình dạng ký tự bất biến

**Giải thích:** <!-- TODO -->

</details>

### Câu 460
Nguồn PDF: trang 62

Điều nào đúng về việc tính GLCM cho ảnh màu?

- A. Chỉ tính trên 1 kênh
- B. Có thể tính riêng cho từng kênh màu hoặc trên ảnh grayscale
- C. GLCM không áp dụng được cho ảnh màu
- D. Cần chuyển sang Lab trước

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Có thể tính riêng cho từng kênh màu hoặc trên ảnh grayscale

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* GLCM cơ bản đếm sự đồng xuất hiện của các mức cường độ trong một ảnh vô hướng, nên có thể áp dụng trên grayscale hoặc riêng từng kênh màu. Với ảnh RGB, cách thứ hai tạo đặc trưng cho từng kênh rồi kết hợp, còn chuyển grayscale gộp thông tin màu thành cường độ trước khi tính. Không bắt buộc chuyển sang Lab; cũng cần nhớ tính riêng từng kênh không tự mô tả quan hệ giữa các kênh, muốn xét quan hệ đó phải dùng biến thể đặc trưng phù hợp.

</details>


## CHƯƠNG 5: Phân vùng ảnh (Segmentation)

### Câu 461
Nguồn PDF: trang 62

Mục tiêu của phân vùng ảnh (image segmentation) là gì?

- A. Tăng độ phân giải ảnh
- B. Chia ảnh thành các vùng có nghĩa tương ứng với đối tượng hoặc bộ phận của đối tượng
- C. Lọc nhiễu ảnh
- D. Phát hiện biên ảnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Chia ảnh thành các vùng có nghĩa tương ứng với đối tượng hoặc bộ phận của đối tượng

**Giải thích:** Phân vùng chia các pixel thành những vùng có ý nghĩa đối với nhiệm vụ đang xét, chẳng hạn vùng của một vật thể hoặc một bộ phận của nó. Kết quả có thể được biểu diễn bằng mask để tách thực thể cần xử lý khỏi phần còn lại của ảnh. Tăng độ phân giải và lọc nhiễu là các thao tác xử lý ảnh khác; phát hiện biên chỉ là một cách hỗ trợ xác định ranh giới vùng, không phải toàn bộ mục tiêu của phân vùng. Tham chiếu: `IT5409 L5-Segmentation.pdf`, trang 2-3.

</details>

### Câu 462
Nguồn PDF: trang 63

Phân vùng ảnh dựa trên những đặc trưng nào của pixel? (Chọn tất cả đúng)

- A. Cường độ xám (grey level)
- B. Màu sắc
- C. Texture
- D. Chuyển động (motion)

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Cường độ xám (grey level); B. Màu sắc; C. Texture; D. Chuyển động (motion)

**Giải thích:** Cường độ xám giúp tách những miền có độ sáng khác nhau, còn màu sắc cung cấp thêm thông tin để phân biệt các vật thể có độ sáng gần giống nhau. Texture mô tả mẫu biến thiên trong một lân cận, nhờ đó có thể phân biệt vùng dù màu trung bình tương tự. Với chuỗi ảnh, chuyển động giúp gom các điểm cùng chuyển động thành một đối tượng hoặc tách đối tượng khỏi nền; vì vậy cả bốn đặc trưng đều có thể dùng, tùy loại dữ liệu và nhiệm vụ. Tham chiếu: `IT5409 L5-Segmentation.pdf`, trang 2, 26-28, 39.

</details>

### Câu 463
Nguồn PDF: trang 63

Hai cách tiếp cận chính trong phân vùng ảnh dựa trên là gì?

- A. Top-down và Bottom-up
- B. Discontinuities (biên) và Homogeneous zones (vùng đồng nhất)
- C. Local và Global
- D. Supervised và Unsupervised

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Discontinuities (biên) và Homogeneous zones (vùng đồng nhất)

**Giải thích:** Cách tiếp cận dựa trên discontinuities tìm những vị trí đặc trưng ảnh thay đổi đột ngột, xem đó là ứng viên cho ranh giới giữa các vùng. Cách tiếp cận dựa trên homogeneity gom các pixel có cường độ, màu hoặc texture tương tự vào cùng vùng. Một hướng tìm nơi vùng kết thúc, hướng kia tìm những điểm nên thuộc cùng vùng; các cặp local/global hay supervised/unsupervised là những cách phân loại khác, không phải hai cơ sở phân vùng được hỏi ở đây. Tham chiếu: `IT5409 L5-Segmentation.pdf`, trang 4-5.

</details>

### Câu 464
Nguồn PDF: trang 63

Phương pháp Thresholding thuộc loại tiếp cận nào trong phân vùng?

- A. Edge-based
- B. Pixel-based
- C. Region-based
- D. Hybrid

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Pixel-based

**Giải thích:** Thresholding quyết định nhãn của từng pixel bằng cách so sánh giá trị của pixel với một hoặc nhiều ngưỡng, nên thuộc nhóm pixel-based. Với một ngưỡng T, quy tắc trong slide gán 0 khi f(x, y) < T và gán 1 khi f(x, y) >= T. Cách này không trực tiếp xây dựng đường biên hoặc phát triển một vùng liên thông; các pixel cùng nhãn vẫn có thể nằm ở những thành phần rời nhau. Tham chiếu: `IT5409 L5-Segmentation.pdf`, trang 6-7, 25.

</details>

### Câu 465
Nguồn PDF: trang 63

Global thresholding khác Local thresholding ở điểm nào?

- A. Global nhanh hơn nhưng kém chính xác hơn
- B. Global dùng một ngưỡng cho toàn bộ ảnh; Local dùng ngưỡng riêng cho từng vùng
- C. Local chỉ dùng cho ảnh nhị phân
- D. Global tốt hơn trong mọi trường hợp

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Global dùng một ngưỡng cho toàn bộ ảnh; Local dùng ngưỡng riêng cho từng vùng

**Giải thích:** Global thresholding áp dụng cùng giá trị T tại mọi vị trí của ảnh, còn local thresholding xác định ngưỡng theo từng phần hoặc lân cận. Khi nền ở một góc sáng hơn góc khác, một ngưỡng toàn cục có thể không tách được đối tượng ở cả hai nơi, trong khi ngưỡng cục bộ có thể thích ứng với khác biệt đó. Đây là khác biệt về phạm vi xác định ngưỡng, không phải một cam kết rằng phương pháp nào luôn nhanh hơn hoặc chính xác hơn. Tham chiếu: `IT5409 L5-Segmentation.pdf`, trang 6, 12.

</details>

### Câu 466
Nguồn PDF: trang 63

Thuật toán Otsu tìm ngưỡng tối ưu bằng cách nào?

- A. Dùng histogram tích lũy
- B. Maximize inter-class variance (phương sai giữa hai lớp)
- C. Minimize intra-class variance
- D. Cả B và C đều đúng (tương đương nhau)

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** D. Cả B và C đều đúng (tương đương nhau)

**Giải thích:** Với mỗi ngưỡng T, Otsu chia histogram thành hai lớp và tính phương sai nội lớp có trọng số: P1 * sigma1² + P2 * sigma2². Tổng phương sai của ảnh cố định bằng phương sai nội lớp cộng phương sai giữa các lớp, nên giảm đại lượng thứ nhất đồng nghĩa với tăng đại lượng thứ hai. Vì vậy B và C là hai cách diễn đạt tương đương của cùng tiêu chí tối ưu; phải hiểu intra-class variance ở đây là tổng có trọng số, không phải một tổng tùy ý của hai phương sai. Tham chiếu: `IT5409 L5-Segmentation.pdf`, trang 11.

</details>

### Câu 467
Nguồn PDF: trang 63

K-means clustering trong phân vùng ảnh hoạt động như thế nào?

- A. Gom pixel có màu ngẫu nhiên vào K nhóm
- B. Lặp: gán pixel vào cluster trung tâm gần nhất → cập nhật trung tâm cluster
- C. Tìm biên và gom vùng
- D. Dùng histogram để phân vùng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Lặp: gán pixel vào cluster trung tâm gần nhất → cập nhật trung tâm cluster

**Giải thích:** K-means biểu diễn mỗi pixel bằng một vector đặc trưng và khởi tạo K tâm cụm. Ở bước gán, pixel được đưa vào cụm có tâm gần nhất theo khoảng cách trong không gian đặc trưng; ở bước cập nhật, mỗi tâm được thay bằng trung bình các vector của cụm đó. Hai bước được lặp tới khi hội tụ, chứ không gom màu ngẫu nhiên ở mọi vòng lặp hoặc bắt buộc tìm biên trước. Tham chiếu: `IT5409 L5-Segmentation.pdf`, trang 14-16.

</details>

### Câu 468
Nguồn PDF: trang 63

Nhược điểm của K-means khi áp dụng cho phân vùng ảnh là gì? (Chọn tất cả đúng)

- A. Phải chỉ định K trước
- B. Nhạy cảm với việc khởi tạo centroid
- C. Có thể hội tụ về local minimum
- D. Không tính đến vị trí không gian của pixel

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Phải chỉ định K trước; B. Nhạy cảm với việc khởi tạo centroid; C. Có thể hội tụ về local minimum; D. Không tính đến vị trí không gian của pixel

**Giải thích:** K-means cần biết K để khởi tạo số tâm cụm, và các tâm ban đầu khác nhau có thể dẫn tới cách chia cụm khác nhau. Do tối ưu bằng các bước gán và cập nhật luân phiên, thuật toán có thể dừng ở cực tiểu cục bộ thay vì nghiệm tốt nhất toàn cục. D đúng trong thiết lập chỉ dùng màu hoặc cường độ: hai pixel xa nhau vẫn có thể cùng cụm; đây không phải hạn chế bắt buộc của mọi biến thể, vì slide cũng minh họa việc thêm tọa độ x, y vào vector đặc trưng để xét vị trí. Tham chiếu: `IT5409 L5-Segmentation.pdf`, trang 14, 18, 26-27.

</details>

### Câu 469
Nguồn PDF: trang 63

Region Growing (phát triển vùng) hoạt động như thế nào?

- A. Chia ảnh thành nhiều vùng nhỏ rồi gộp lại
- B. Bắt đầu từ seed pixel(s), mở rộng vùng bằng cách thêm pixel lân cận thỏa mãn tiêu chí đồng nhất
- C. Tìm biên trước rồi chia vùng
- D. Dùng histogram để tạo vùng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Bắt đầu từ seed pixel(s), mở rộng vùng bằng cách thêm pixel lân cận thỏa mãn tiêu chí đồng nhất

**Giải thích:** Region Growing bắt đầu từ một hoặc nhiều seed được chọn thủ công hoặc tự động, rồi xét các pixel ở lân cận của vùng hiện tại. Pixel chỉ được thêm nếu thỏa tiêu chí đồng nhất, đồng thời quan hệ lân cận 4 hoặc 8 giúp duy trì tính liên thông của vùng. Quá trình mở rộng dừng khi không còn pixel phù hợp; chia nhỏ ảnh rồi gộp lại là cơ chế của Split and Merge, không phải cơ chế phát triển từ seed. Tham chiếu: `IT5409 L5-Segmentation.pdf`, trang 29-30.

</details>

### Câu 470
Nguồn PDF: trang 64

Tiêu chí đồng nhất trong Region Growing có thể là gì? (Chọn tất cả đúng)

- A. Cường độ sáng tương tự
- B. Màu sắc tương tự
- C. Texture tương tự
- D. Vị trí gần nhau

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Cường độ sáng tương tự; B. Màu sắc tương tự; C. Texture tương tự

**Giải thích:** Tính đồng nhất đánh giá sự tương tự về nội dung ảnh, nên có thể dựa vào độ sáng, màu hoặc đặc trưng texture của pixel và vùng. Gần nhau về vị trí chỉ xác định pixel nào có thể được xét để giữ vùng liên thông, không bảo đảm chúng có đặc trưng giống nhau: hai pixel nằm hai phía một biên vẫn kề nhau. Vì vậy A, B, C là tiêu chí đồng nhất, còn D là điều kiện không gian cần phân biệt với tiêu chí đó. Tham chiếu: `IT5409 L5-Segmentation.pdf`, trang 4, 26, 29-30.

</details>

### Câu 471
Nguồn PDF: trang 64

Split and Merge algorithm sử dụng cấu trúc dữ liệu nào?

- A. Binary tree
- B. Quadtree
- C. Graph
- D. Linked list

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Quadtree

**Giải thích:** Mỗi lần split, một vùng không đồng nhất được chia thành bốn phần tư, nên một nút biểu diễn vùng có tối đa bốn nút con. Lặp lại thao tác này tạo cấu trúc quadtree, trong đó các lá biểu diễn những vùng không cần chia tiếp theo tiêu chí đã chọn. Cây nhị phân chỉ có hai nhánh tại mỗi lần chia, còn danh sách liên kết không thể hiện tự nhiên quan hệ phân cấp bốn phần như sơ đồ của thuật toán. Tham chiếu: `IT5409 L5-Segmentation.pdf`, trang 31-32.

</details>

### Câu 472
Nguồn PDF: trang 64

Bước "Split" trong Split and Merge algorithm thực hiện điều gì?

- A. Gộp các vùng đồng nhất lại
- B. Chia vùng không đồng nhất thành 4 sub-vùng (quadrants)
- C. Tính histogram của vùng
- D. Tìm biên của vùng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Chia vùng không đồng nhất thành 4 sub-vùng (quadrants)

**Giải thích:** Bước split kiểm tra một vùng bằng tiêu chí đồng nhất, ví dụ phương sai hoặc khoảng chênh giữa giá trị lớn nhất và nhỏ nhất. Nếu vùng không đạt tiêu chí, nó được chia thành bốn phần tư và phép kiểm tra được thực hiện đệ quy trên các phần đó. Việc tính đặc trưng chỉ phục vụ quyết định có chia hay không; gộp các vùng là bước merge riêng, không phải thao tác split. Tham chiếu: `IT5409 L5-Segmentation.pdf`, trang 31-32.

</details>

### Câu 473
Nguồn PDF: trang 64

Bước "Merge" trong Split and Merge algorithm thực hiện điều gì?

- A. Tiếp tục chia nhỏ vùng
- B. Gộp các vùng kề nhau thỏa mãn tiêu chí đồng nhất
- C. Xóa các vùng nhỏ
- D. Tính đặc trưng của vùng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Gộp các vùng kề nhau thỏa mãn tiêu chí đồng nhất

**Giải thích:** Sau khi chia, các ô có thể quá nhỏ hoặc hai ô liền nhau thực chất thuộc cùng một miền ảnh. Bước merge xét các vùng kề nhau và gộp khi vùng hợp của chúng vẫn thỏa tiêu chí đồng nhất, giúp khắc phục việc chia quá chi tiết. Chỉ kề nhau chưa đủ để gộp, và xóa một vùng nhỏ cũng không tương đương với merge vì các pixel của vùng đó vẫn phải được phân vào kết quả. Tham chiếu: `IT5409 L5-Segmentation.pdf`, trang 29, 31-32.

</details>

### Câu 474
Nguồn PDF: trang 64

Watershed algorithm (thuật toán đầu nguồn) xem ảnh như thế nào?

- A. Như một đồ thị phẳng
- B. Như địa hình 3D với pixel sáng là đỉnh núi và pixel tối là thung lũng
- C. Như histogram 2D
- D. Như ma trận adjacency

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Như địa hình 3D với pixel sáng là đỉnh núi và pixel tối là thung lũng

**Giải thích:** Watershed dùng một ảnh vô hướng làm bề mặt địa hình: tọa độ pixel xác định vị trí trên mặt phẳng và giá trị ảnh xác định độ cao. Nếu dùng trực tiếp cường độ xám, giá trị sáng cao hơn tạo đỉnh, còn giá trị tối thấp hơn tạo thung lũng; các lưu vực được hình dung qua quá trình làm ngập địa hình. Slide có bước đảo ảnh trong ví dụ, nên cách diễn giải sáng/tối sẽ đảo theo phép biến đổi đó, không phải thuộc tính cố định của mọi đầu vào watershed. Tham chiếu: `IT5409 L5-Segmentation.pdf`, trang 34-36.

</details>

### Câu 475
Nguồn PDF: trang 64

Nhược điểm lớn nhất của Watershed algorithm là gì?

- A. Quá chậm
- B. Over-segmentation (phân vùng quá mức) do nhiễu tạo ra nhiều vùng nhỏ
- C. Không hoạt động với ảnh màu
- D. Cần seed điểm đầu vào

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Over-segmentation (phân vùng quá mức) do nhiễu tạo ra nhiều vùng nhỏ

**Giải thích:** Trong mô hình địa hình của watershed, các cực tiểu cục bộ tạo những lưu vực có thể phát triển thành vùng riêng. Nhiễu làm xuất hiện nhiều cực tiểu nhỏ không tương ứng với đối tượng thật, nên một đối tượng có thể bị chia thành nhiều mảnh, gọi là over-segmentation. Vấn đề nằm ở cấu trúc địa hình đầu vào và số lưu vực, không phải ở việc thuật toán tuyệt đối không xử lý được ảnh màu hoặc luôn quá chậm. Tham chiếu: `IT5409 L5-Segmentation.pdf`, trang 34-37.

</details>

### Câu 476
Nguồn PDF: trang 64

Mean shift algorithm trong phân vùng ảnh dựa trên nguyên lý gì?

- A. Minimize variance
- B. Tìm điểm mode (đỉnh mật độ) của phân phối trong không gian đặc trưng bằng cách dịch về hướng gradient mật độ
- C. Phân tích Fourier
- D. Random sampling

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Tìm điểm mode (đỉnh mật độ) của phân phối trong không gian đặc trưng bằng cách dịch về hướng gradient mật độ

**Giải thích:** Mean Shift đặt một cửa sổ trong không gian đặc trưng, tính tâm khối lượng của các điểm trong cửa sổ rồi dịch tâm cửa sổ về vị trí đó. Lặp thao tác này đưa các điểm tới những mode, tức cực đại cục bộ của mật độ; các quỹ đạo hội tụ về cùng mode có thể được gom thành một cụm. Khác K-means với K tâm đã định trước, cơ chế ở đây là tìm các đỉnh mật độ và miền hút của chúng, không phải phân tích Fourier hoặc lấy mẫu ngẫu nhiên. Tham chiếu: `IT5409 L5-Segmentation.pdf`, trang 19-23.

</details>

### Câu 477
Nguồn PDF: trang 65

Active contours (Snakes) là gì?

- A. Thuật toán phân vùng dựa trên màu sắc
- B. Đường cong co giãn được định nghĩa bởi năng lượng; cực tiểu hóa năng lượng để bám vào biên đối tượng
- C. Loại filter đặc biệt
- D. Phương pháp phân cụm

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Đường cong co giãn được định nghĩa bởi năng lượng; cực tiểu hóa năng lượng để bám vào biên đối tượng

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* Snake biểu diễn một đường cong biến dạng và tối ưu năng lượng kết hợp tính trơn của đường với thông tin ảnh hoặc lực ràng buộc. Khi tối ưu, đường cong dịch chuyển để bám vào những đặc trưng như biên đối tượng, thay vì gom pixel bằng khoảng cách tới centroid. Vì vậy B đúng về cơ chế; kết quả phụ thuộc khởi tạo và năng lượng được chọn, nên không bảo đảm đường cong luôn tìm được mọi biên hoặc nghiệm tối ưu toàn cục. Đối chiếu: [Snakes: Active contour models](https://link.springer.com/article/10.1007/BF00133570).

</details>

### Câu 478
Nguồn PDF: trang 65

Năng lượng của Snakes (Active Contours) bao gồm những thành phần nào? (Chọn tất cả đúng)

- A. Internal energy (giữ đường cong trơn và không duỗi dài)
- B. Image energy (kéo đường cong về phía biên)
- C. External/constraint energy
- D. Thermal energy

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Internal energy (giữ đường cong trơn và không duỗi dài); B. Image energy (kéo đường cong về phía biên); C. External/constraint energy

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* Internal energy phạt việc kéo giãn và uốn cong để điều chỉnh độ căng, độ trơn của snake; nó không cấm đường cong thay đổi chiều dài tuyệt đối. Image energy tạo lực từ dữ liệu ảnh để hút đường về cấu trúc cần tìm, còn constraint energy biểu diễn hướng dẫn hay ràng buộc bên ngoài, nên A, B, C thuộc mô hình snake cổ điển. Thermal energy không phải thành phần chuẩn ở đây; một số tài liệu gộp image và constraint vào nhóm external energy, nên cách đặt tên các hạng có thể khác nhau. Đối chiếu: [mô hình snakes](https://link.springer.com/article/10.1007/BF00133570).

</details>

### Câu 479
Nguồn PDF: trang 65

IoU (Intersection over Union) trong đánh giá phân vùng được tính như thế nào?

- A. Diện tích giao / Diện tích hợp
- B. Diện tích hợp / Diện tích giao
- C. Diện tích giao × Diện tích hợp
- D. Diện tích giao - Diện tích hợp

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Diện tích giao / Diện tích hợp

**Giải thích:** Với mask dự đoán P và mask chuẩn G, IoU = |P giao G| / |P hợp G|; ở ảnh rời rạc, diện tích chính là số pixel trong mỗi tập. Phần giao chỉ giữ các pixel đối tượng được dự đoán đúng, còn phần hợp bao gồm cả pixel dự đoán thừa và pixel đối tượng bị bỏ sót. Do đó IoU phạt cả hai loại sai lệch và bằng 1 khi hai mask trùng nhau với phần hợp khác rỗng; đảo tử và mẫu không còn là tỷ lệ chồng lấp chuẩn. Tham chiếu: `IT5409 L7.3.2-DlForCvSegmentation.pdf`, trang 18.

</details>

### Câu 480
Nguồn PDF: trang 65

Phân vùng ảnh là bước quan trọng trong những ứng dụng nào? (Chọn tất cả đúng)

- A. Nhận dạng đối tượng
- B. Image retrieval
- C. Phân tích ảnh y tế
- D. Theo dõi đối tượng trong video

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Nhận dạng đối tượng; B. Image retrieval; C. Phân tích ảnh y tế; D. Theo dõi đối tượng trong video

**Giải thích:** Trong nhận dạng, mask phân vùng giúp tách đối tượng để phân tích; trong image retrieval, vùng ảnh có thể cung cấp đặc trưng của phần cần tìm thay vì toàn bộ nền. Với ảnh y tế, phân vùng xác định ranh giới cấu trúc cần đo hoặc phân tích, còn trong video nó giúp xác định vùng đối tượng để hỗ trợ theo dõi qua các khung hình. Slide liệt kê cả bốn nhóm ứng dụng này; điều đó không có nghĩa mọi hệ nhận dạng hay tracking đều bắt buộc phải có một bước phân vùng độc lập. Tham chiếu: `IT5409 L5-Segmentation.pdf`, trang 3, 37.

</details>

### Câu 481
Nguồn PDF: trang 65

Graph-based segmentation (Felzenszwalb & Huttenlocher) xem ảnh như gì?

- A. Ma trận pixel thông thường
- B. Đồ thị có trọng số, pixel là nút, cạnh giữa pixel kề nhau có trọng số là sự khác biệt giữa chúng
- C. Cây nhị phân
- D. Chuỗi Markov

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Đồ thị có trọng số, pixel là nút, cạnh giữa pixel kề nhau có trọng số là sự khác biệt giữa chúng

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* Ảnh được chuyển thành đồ thị với nút là pixel, cạnh nối những pixel thuộc lân cận đã chọn và trọng số thể hiện độ khác nhau của đặc trưng như màu. Cạnh trọng số lớn là dấu hiệu hai pixel ít tương tự, còn các cạnh nhỏ hỗ trợ việc gom vùng. Phương pháp Felzenszwalb-Huttenlocher so sánh khác biệt giữa các vùng với mức biến thiên nội vùng để quyết định gộp, không chỉ cắt mọi cạnh vượt một ngưỡng cố định. Đối chiếu: [Efficient Graph-Based Image Segmentation](https://cs.brown.edu/people/pfelzens/papers/seg-ijcv.pdf).

</details>

### Câu 482
Nguồn PDF: trang 65

Normalized Cut (Ncut) là phương pháp phân vùng dựa trên gì?

- A. Pixel intensity
- B. Phân chia đồ thị sao cho tối thiểu hóa cut giữa các cluster so với tổng connectivity
- C. Histogram của vùng
- D. Gradient của biên

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Phân chia đồ thị sao cho tối thiểu hóa cut giữa các cluster so với tổng connectivity

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* Ncut biểu diễn pixel hoặc đơn vị ảnh thành đồ thị tương đồng rồi tìm cách tách đồ thị với kết nối yếu giữa các phần. Tiêu chí chuẩn hóa chi phí cut bằng tổng kết nối của từng phần với toàn đồ thị, thay vì chỉ tối thiểu số hoặc trọng số cạnh bị cắt. Sự chuẩn hóa này hạn chế xu hướng tách một nhóm rất nhỏ chỉ vì nó có ít cạnh, nên B phản ánh bản chất phân chia đồ thị, không phải chỉ ngưỡng hóa cường độ hay histogram. Đối chiếu: [Normalized Cuts and Image Segmentation](https://www.cis.upenn.edu/~jshi/papers/pami_ncut.pdf).

</details>

### Câu 483
Nguồn PDF: trang 65

Markov Random Field (MRF) trong phân vùng ảnh mô hình hóa điều gì?

- A. Chuyển động đối tượng
- B. Sự phụ thuộc ngữ cảnh (contextual dependencies) giữa các pixel lân cận
- C. Phổ màu của ảnh
- D. Kết cấu toàn cục

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Sự phụ thuộc ngữ cảnh (contextual dependencies) giữa các pixel lân cận

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* MRF dùng các biến ngẫu nhiên cho nhãn pixel với cấu trúc phụ thuộc được quy định bởi đồ thị lân cận. Trong mô hình phân vùng phổ biến, một hạng năng lượng đánh giá nhãn phù hợp với dữ liệu, còn hạng tương tác khuyến khích những pixel có quan hệ phù hợp nhận nhãn nhất quán. B đúng vì quyết định không được đưa ra độc lập cho từng pixel; mức làm trơn phải cân bằng với dữ liệu để tránh xóa ranh giới thật, và MRF không chỉ mô hình chuyển động hay phổ màu. Đối chiếu: [mô hình MRF/CRF cho gán nhãn ảnh](https://www.microsoft.com/en-us/research/wp-content/uploads/2010/04/multi_scale.pdf).

</details>

### Câu 484
Nguồn PDF: trang 66

Superpixel là gì?

- A. Pixel có độ phân giải cao
- B. Nhóm các pixel liền kề có đặc trưng tương tự, dùng làm đơn vị xử lý thay vì pixel đơn lẻ
- C. Pixel đặc biệt dùng làm seed
- D. Kết quả cuối cùng của phân vùng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Nhóm các pixel liền kề có đặc trưng tương tự, dùng làm đơn vị xử lý thay vì pixel đơn lẻ

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* Superpixel là một vùng nhỏ liên thông gồm nhiều pixel có đặc trưng gần nhau, được tạo làm đơn vị cho các bước xử lý tiếp theo. Nó không phải pixel của cảm biến có độ phân giải cao hơn và thường cũng chưa tương ứng với toàn bộ một đối tượng ngữ nghĩa. Các superpixel có thể được gán nhãn hoặc gộp thêm để tạo kết quả cuối; chất lượng của chúng quan trọng vì ranh giới bị bỏ qua ở bước này có thể khó khôi phục về sau. Đối chiếu: [SLIC Superpixels](https://www.epfl.ch/labs/ivrl/research/slic-superpixels/).

</details>

### Câu 485
Nguồn PDF: trang 66

SLIC (Simple Linear Iterative Clustering) tạo ra loại gì?

- A. Binary segmentation
- B. Superpixels dựa trên K-means trong không gian màu-vị trí (CIELAB + xy)
- C. Histogram phân vùng
- D. Edge map

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Superpixels dựa trên K-means trong không gian màu-vị trí (CIELAB + xy)

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* SLIC dùng biến thể phân cụm kiểu K-means trên vector gồm màu Lab và tọa độ x, y, đồng thời giới hạn việc tìm cụm trong lân cận để tính hiệu quả. Khoảng cách kết hợp độ giống màu và khoảng cách không gian, với tham số compactness điều chỉnh đánh đổi giữa bám biên và vùng gọn. Vì vậy đầu ra là các superpixel như B, không phải một histogram hoặc edge map; chỉ phân cụm theo màu mà bỏ x, y có thể gom cả những pixel xa nhau vào một cụm. Đối chiếu: [SLIC của nhóm tác giả](https://www.epfl.ch/labs/ivrl/research/slic-superpixels/).

</details>

### Câu 486
Nguồn PDF: trang 66

Tiêu chí đánh giá phân vùng nào đo tỉ lệ pixel được phân loại đúng?

- A. IoU
- B. Pixel Accuracy
- C. Mean IoU (mIoU)
- D. F1-score

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Pixel Accuracy

**Giải thích:** Pixel Accuracy lấy số pixel có nhãn dự đoán trùng nhãn chuẩn chia cho tổng số pixel được đánh giá. Chỉ số này trả lời trực tiếp câu hỏi có bao nhiêu pixel được phân loại đúng, nhưng một lớp nền chiếm phần lớn ảnh có thể làm kết quả cao dù các đối tượng nhỏ bị bỏ sót. IoU xét phần giao so với phần hợp của mask, còn F1 cân bằng precision và recall, nên không phải cùng phép đếm đúng trên tổng pixel. Tham chiếu: `IT5409 L7.3.2-DlForCvSegmentation.pdf`, trang 18-19.

</details>

### Câu 487
Nguồn PDF: trang 66

Mean IoU (mIoU) khác với Pixel Accuracy ở điểm nào?

- A. mIoU chậm hơn tính
- B. mIoU tính trung bình IoU qua các lớp, tránh bias do lớp dominant chiếm nhiều pixel
- C. mIoU chỉ tính cho 2 lớp
- D. Không có sự khác biệt

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. mIoU tính trung bình IoU qua các lớp, tránh bias do lớp dominant chiếm nhiều pixel

**Giải thích:** mIoU tính IoU riêng cho từng lớp rồi lấy trung bình không trọng số trên các lớp được đánh giá; mỗi lớp đóng góp một hạng dù diện tích của chúng khác nhau. Pixel Accuracy lại cộng số pixel đúng trên toàn ảnh, nên lớp nền rất lớn có thể lấn át lỗi ở lớp nhỏ. Vì thế mIoU giảm sự chi phối của lớp đông pixel trong phép tổng hợp, nhưng không tự loại bỏ mọi vấn đề mất cân bằng dữ liệu và cũng không chỉ áp dụng cho hai lớp. Tham chiếu: `IT5409 L7.3.2-DlForCvSegmentation.pdf`, trang 18, về đánh giá theo pixel và IoU.

</details>

### Câu 488
Nguồn PDF: trang 66

Interactive segmentation cho phép người dùng làm gì?

- A. Chọn màu nền
- B. Cung cấp annotations (điểm, vùng) để hướng dẫn thuật toán phân vùng
- C. Điều chỉnh độ tương phản
- D. Chọn filter

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Cung cấp annotations (điểm, vùng) để hướng dẫn thuật toán phân vùng

**Giải thích:** Người dùng cung cấp thông tin về vùng cần tách, chẳng hạn chọn seed ở đối tượng, để thuật toán biết điểm xuất phát hoặc nhãn cần ưu tiên. Slide về Region Growing cho phép seed được chọn thủ công, minh họa cách một thao tác của người dùng hướng dẫn quá trình mở rộng vùng theo tiêu chí đồng nhất. Tương tác ở đây bổ sung thông tin cho quyết định phân vùng, khác với chỉ đổi màu nền, độ tương phản hoặc chọn một bộ lọc hiển thị. Tham chiếu: `IT5409 L5-Segmentation.pdf`, trang 30.

</details>

### Câu 489
Nguồn PDF: trang 66

GrabCut là phương pháp phân vùng nào?

- A. Purely automatic
- B. Interactive, dùng Gaussian Mixture Models và graph cuts, người dùng vẽ bounding box
- C. Chỉ dùng thresholding
- D. Deep learning

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Interactive, dùng Gaussian Mixture Models và graph cuts, người dùng vẽ bounding box

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* GrabCut có thể khởi tạo bằng một hình chữ nhật bao quanh đối tượng, xem phía ngoài là nền chắc chắn và phân loại dần vùng bên trong. Các GMM mô tả màu foreground và background, còn graph cut tìm cách gán nhãn cân bằng độ phù hợp màu với quan hệ giữa pixel. Người dùng có thể bổ sung nét đánh dấu để sửa vùng sai, nên B đúng về tính tương tác; đây không phải chỉ thresholding hoặc một mạng deep learning. Đối chiếu: [quy trình GrabCut](https://docs.opencv.org/4.x/d8/d83/tutorial_py_grabcut.html).

</details>

### Câu 490
Nguồn PDF: trang 66

Conditional Random Field (CRF) được dùng để làm gì trong phân vùng?

- A. Phát hiện biên ban đầu
- B. Post-processing để làm sắc nét boundaries, tính đến pixel compatibility và spatial consistency
- C. Tạo superpixels
- D. Tính histogram

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Post-processing để làm sắc nét boundaries, tính đến pixel compatibility và spatial consistency

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* CRF kết hợp độ tin cậy của nhãn tại mỗi pixel với tương tác giữa các nhãn có xét dữ liệu ảnh, như màu và khoảng cách vị trí. Khi dùng sau một mạng phân vùng, nó có thể giảm những nhãn rời rạc và điều chỉnh mask theo biên ảnh, nên B mô tả một ứng dụng hậu xử lý phổ biến. Tuy nhiên CRF không nhất thiết chỉ là hậu xử lý hoặc chỉ xét pixel kề nhau; dense CRF còn có thể liên kết các cặp pixel xa nhau, và việc làm sắc biên không được bảo đảm trên mọi ảnh. Đối chiếu: [Fully Connected CRFs](https://arxiv.org/abs/1210.5644).

</details>

### Câu 491
Nguồn PDF: trang 67

Phân vùng ảnh y tế (Medical Image Segmentation) gặp thách thức gì đặc biệt? (Chọn tất cả đúng)

- A. Cấu trúc giải phẫu phức tạp và biến thiên lớn giữa bệnh nhân
- B. Ranh giới mờ giữa các cấu trúc
- C. Ít dữ liệu labeled (annotated) để huấn luyện
- D. Ảnh thường có nhiễu (MRI, CT noise)

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Cấu trúc giải phẫu phức tạp và biến thiên lớn giữa bệnh nhân; B. Ranh giới mờ giữa các cấu trúc; C. Ít dữ liệu labeled (annotated) để huấn luyện; D. Ảnh thường có nhiễu (MRI, CT noise)

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* Biến thiên giải phẫu làm hình dạng và vị trí cấu trúc không cố định giữa các bệnh nhân, còn độ tương phản thấp khiến biên giữa mô khó phân biệt. Dữ liệu được gán nhãn chính xác có thể ít do cần công sức chuyên gia; nhiễu và artefact của quy trình thu nhận ảnh còn làm đặc trưng quan sát kém ổn định. Vì vậy cả A, B, C, D đều có thể là thách thức, nhưng mức độ phụ thuộc loại ảnh và bộ dữ liệu, không phải mọi ảnh CT hay MRI đều có cùng khó khăn. Đối chiếu: [thách thức cấu trúc và chất lượng ảnh](https://pmc.ncbi.nlm.nih.gov/articles/PMC6878163/), [nghiên cứu về chất lượng nhãn](https://pmc.ncbi.nlm.nih.gov/articles/PMC7484266/).

</details>

### Câu 492
Nguồn PDF: trang 67

Phương pháp nào là Semi-supervised segmentation?

- A. K-means thuần túy
- B. GrabCut và Active Contours
- C. Otsu thresholding
- D. Watershed thuần túy

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. GrabCut và Active Contours

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* Theo ý định của ngân hàng câu hỏi, B chỉ những phương pháp có thể nhận hướng dẫn ban đầu từ người dùng, như bounding box cho GrabCut hoặc khởi tạo đường cong cho snakes. **Lưu ý thuật ngữ:** cách này nên gọi là phân vùng tương tác hoặc có hướng dẫn; semi-supervised learning theo nghĩa hiện đại là học từ cả dữ liệu có nhãn và chưa có nhãn, nên B không phải phân loại chuẩn theo nghĩa đó. Active contours cũng có thể được khởi tạo tự động, vì vậy không thể khẳng định mọi biến thể của nó đều bán giám sát. Đối chiếu về tương tác: [GrabCut](https://docs.opencv.org/4.x/d8/d83/tutorial_py_grabcut.html), [snakes](https://link.springer.com/article/10.1007/BF00133570).

</details>

### Câu 493
Nguồn PDF: trang 67

Phân vùng dựa trên màu (color-based segmentation) hoạt động hiệu quả trong trường hợp nào?

- A. Khi đối tượng có màu tương tự nền
- B. Khi đối tượng có màu sắc đặc trưng và khác biệt với nền
- C. Khi ảnh là grayscale
- D. Khi ánh sáng thay đổi nhiều

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Khi đối tượng có màu sắc đặc trưng và khác biệt với nền

**Giải thích:** Phân vùng theo màu cần các nhóm màu của đối tượng và nền đủ phân biệt trong không gian đặc trưng, khi đó thresholding hoặc clustering có cơ sở để gán nhãn khác nhau. Nếu chúng có màu gần giống nhau, chỉ thông tin màu không đủ quyết định pixel thuộc vùng nào; có thể cần thêm texture hoặc vị trí. Ánh sáng thay đổi còn làm màu quan sát biến đổi, nên không phải điều kiện bảo đảm hiệu quả, trong khi ảnh grayscale không cung cấp đầy đủ các kênh màu. Tham chiếu: `IT5409 L5-Segmentation.pdf`, trang 4, 14-16, 26-28.

</details>

### Câu 494
Nguồn PDF: trang 67

Level Set Methods trong phân vùng dựa trên nguyên lý gì?

- A. Phân cụm K-means
- B. Biểu diễn đường biên phân vùng như zero level set của hàm implicit (signed distance function)
- C. Random forest
- D. Histogram

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Biểu diễn đường biên phân vùng như zero level set của hàm implicit (signed distance function)

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* Level Set biểu diễn đường biên gián tiếp bằng tập các điểm thỏa phi(x, y) = 0, thay vì lưu riêng một danh sách điểm đường cong. Hàm khoảng cách có dấu là một cách khởi tạo phổ biến: hai phía biên có dấu khác nhau và tại biên giá trị bằng 0. Khi cập nhật phi theo phương trình tiến hóa, đường biên di chuyển và có thể tự tách hoặc hợp; không bắt buộc phi luôn là hàm khoảng cách chính xác ở mọi bước. Đối chiếu: [giải thích của Sethian về Level Set](https://math.berkeley.edu/~sethian/Explanations/level_set_explain.html).

</details>

### Câu 495
Nguồn PDF: trang 67

Điều nào đúng về Expectation Maximization (EM) trong phân vùng?

- A. Chỉ dùng cho K-means
- B. EM ước lượng parameters của Gaussian Mixture Model (GMM) để mô hình hóa phân phối pixel
- C. EM không thể dùng cho phân vùng
- D. EM là deterministic

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. EM ước lượng parameters của Gaussian Mixture Model (GMM) để mô hình hóa phân phối pixel

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* Với GMM, bước E tính mức trách nhiệm của từng thành phần Gaussian đối với mỗi pixel, còn bước M cập nhật trọng số, trung bình và hiệp phương sai từ các trách nhiệm đó. B vì vậy mô tả một ứng dụng đúng của EM để ước lượng mô hình phân phối. **Lưu ý:** D không luôn sai: EM chuẩn là xác định khi dữ liệu và khởi tạo đã cố định; khởi tạo ngẫu nhiên có thể làm các lần chạy khác nhau. Do đó câu một đáp án này chưa chặt chẽ, không nên giải thích rằng EM vốn ngẫu nhiên. Đối chiếu: [GMM và EM](https://scikit-learn.org/stable/modules/mixture.html).

</details>

### Câu 496
Nguồn PDF: trang 67

Frequency-weighted IoU khác Mean IoU như thế nào?

- A. Tính nhanh hơn
- B. Cân nhắc tần suất (frequency) của từng lớp khi tính trung bình, các lớp phổ biến có weight cao hơn
- C. Chỉ tính cho 2 lớp
- D. Không xét đến lớp đặc biệt

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Cân nhắc tần suất (frequency) của từng lớp khi tính trung bình, các lớp phổ biến có weight cao hơn

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* Mean IoU lấy trung bình IoU với trọng số bằng nhau cho các lớp được đánh giá, còn frequency-weighted IoU dùng tỷ lệ pixel ground truth của từng lớp làm trọng số. Nếu nền chiếm 90% pixel, IoU của nền đóng góp 90% vào tổng có trọng số, thay vì chỉ một phần bằng các lớp khác. B vì vậy đúng về cách tổng hợp; cách này phản ánh độ phổ biến nhưng có thể làm lỗi ở lớp hiếm ít ảnh hưởng tới điểm chung hơn. Đối chiếu: [các metric trong bài báo FCN](https://arxiv.org/abs/1411.4038).

</details>

### Câu 497
Nguồn PDF: trang 67

Phân vùng ảnh satellite dùng để làm gì? (Chọn tất cả đúng)

- A. Phân loại địa hình
- B. Phát hiện thay đổi đô thị
- C. Phân tích nông nghiệp
- D. Theo dõi biến đổi khí hậu

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Phân loại địa hình; B. Phát hiện thay đổi đô thị; C. Phân tích nông nghiệp; D. Theo dõi biến đổi khí hậu

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* Phân vùng ảnh vệ tinh có thể tạo bản đồ các vùng phủ bề mặt như nước, cây trồng hoặc khu xây dựng, hỗ trợ A và C. So sánh những bản đồ tương ứng qua thời gian giúp phát hiện mở rộng đô thị hoặc biến đổi diện tích lớp phủ, hỗ trợ B và cung cấp dữ liệu cho nghiên cứu môi trường, khí hậu ở D. Phân vùng chỉ là một bước trong chuỗi phân tích; thay đổi trên một ảnh đơn lẻ không đủ để kết luận nguyên nhân hoặc xu hướng biến đổi khí hậu. Đối chiếu: [ESA về bản đồ lớp phủ và ứng dụng](https://www.esa.int/Applications/Observing_the_Earth/Copernicus/Sentinel-2/Land-cover_maps_of_Europe_from_the_Cloud).

</details>

### Câu 498
Nguồn PDF: trang 67

Tiêu chí homogeneity (đồng nhất) trong phân vùng region-based có thể đánh giá dựa trên gì?

- A. Chỉ cường độ trung bình
- B. Cường độ, màu sắc, texture; kiểm tra predicat P trả về TRUE khi vùng đồng nhất
- C. Chỉ màu sắc
- D. Chỉ vị trí spatial

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Cường độ, màu sắc, texture; kiểm tra predicat P trả về TRUE khi vùng đồng nhất

**Giải thích:** Predicate P biểu diễn một phép kiểm tra mà vùng phải thỏa để được coi là đồng nhất, chẳng hạn phương sai cường độ nhỏ hơn một ngưỡng. Đặc trưng dùng cho P có thể là cường độ, màu hoặc texture, nên không bị giới hạn ở cường độ trung bình hay chỉ một loại đặc trưng. Trong Split and Merge, P giúp quyết định chia một vùng không đồng nhất và gộp hai vùng khi vùng hợp vẫn đồng nhất; tính kề nhau là điều kiện không gian riêng. Tham chiếu: `IT5409 L5-Segmentation.pdf`, trang 4, 26, 29-31.

</details>

### Câu 499
Nguồn PDF: trang 68

Điều nào KHÔNG đúng về Watershed algorithm?

- A. Coi ảnh như địa hình
- B. Luôn cho kết quả tốt mà không cần xử lý thêm
- C. Có thể dùng với markers để giảm over-segmentation
- D. Phổ biến cho phân vùng ảnh y tế

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Luôn cho kết quả tốt mà không cần xử lý thêm

**Giải thích:** Khẳng định có từ "luôn" không phù hợp với cách watershed phân chia địa hình: cấu trúc nhiễu hoặc quá nhiều cực tiểu có thể sinh những vùng không phục vụ mục tiêu cần tách. Bài giảng cũng nhấn mạnh không có phương pháp phân vùng nào phù hợp với mọi ảnh và việc kiểm soát dữ liệu hoặc tiền xử lý có thể cần thiết. Do đó B là nhận định sai; mô hình địa hình không tự bảo đảm rằng mỗi lưu vực sẽ tương ứng với một đối tượng có nghĩa. Tham chiếu: `IT5409 L5-Segmentation.pdf`, trang 34-38.

</details>

### Câu 500
Nguồn PDF: trang 68

Instance segmentation khác semantic segmentation ở điểm nào?

- A. Semantic phân biệt từng instance riêng lẻ
- B. Instance segmentation phân biệt từng cá thể đối tượng (instance) riêng lẻ, ngay cả cùng class
- C. Không có sự khác biệt
- D. Semantic nhanh hơn

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Instance segmentation phân biệt từng cá thể đối tượng (instance) riêng lẻ, ngay cả cùng class

**Giải thích:** Semantic segmentation gán nhãn lớp cho từng pixel, nên pixel của hai người khác nhau đều có thể mang cùng nhãn "person" mà không chỉ rõ người nào. Instance segmentation bổ sung sự phân biệt cá thể, tạo mask riêng cho từng người dù cả hai thuộc cùng lớp. Sự khác biệt nằm ở thông tin đầu ra về danh tính từng đối tượng, không phải một quy tắc rằng semantic luôn nhanh hơn; slide minh họa đầu ra theo cá thể và mask của Mask R-CNN. Tham chiếu: `IT5409 L7.3.2-DlForCvSegmentation.pdf`, trang 2-3, 20-22.

</details>

### Câu 501
Nguồn PDF: trang 68

Điều nào đúng về contour-based segmentation?

- A. Chỉ hoạt động với ảnh đơn sắc
- B. Phân vùng dựa trên đường biên khép kín xung quanh đối tượng
- C. Không thể xử lý đối tượng có lỗ
- D. Không liên quan đến edge detection

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Phân vùng dựa trên đường biên khép kín xung quanh đối tượng

**Giải thích:** Một contour khép kín phân chia miền bên trong và bên ngoài, nhờ đó chuyển thông tin đường biên thành một vùng hoặc mask. Bài giảng nêu quan hệ giữa closed edges và regions: tìm được ranh giới khép kín là một cách xác định vùng mà không cần gom pixel từ seed. Vì vậy phương pháp có liên hệ với phát hiện biên, không chỉ dành cho ảnh đơn sắc; một tập các đoạn biên rời rạc chưa tự tạo thành phân vùng hoàn chỉnh. Tham chiếu: `IT5409 L5-Segmentation.pdf`, trang 5, 33.

</details>

### Câu 502
Nguồn PDF: trang 68

Điều nào đúng về kỹ thuật "marker-controlled watershed"?

- A. Sử dụng nhiều seed/markers để kiểm soát quá trình flooding
- B. Không cần markers
- C. Luôn cho kết quả over-segmentation
- D. Chỉ áp dụng cho ảnh grayscale

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Sử dụng nhiều seed/markers để kiểm soát quá trình flooding

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* Marker-controlled watershed khởi tạo những vùng mang nhãn xác định rồi cho quá trình flooding lan từ các marker, thay vì tạo vùng độc lập từ mọi cực tiểu do nhiễu. Những marker cho đối tượng và nền giúp kiểm soát số lưu vực và giảm phân vùng quá mức, nên A đúng. Marker có thể được tạo thủ công hoặc tự động; chất lượng của chúng vẫn ảnh hưởng kết quả, và thuật toán không bị giới hạn ở việc chỉ nhận ảnh grayscale. Đối chiếu: [watershed có marker trong OpenCV](https://docs.opencv.org/4.x/d3/db4/tutorial_py_watershed.html).

</details>

### Câu 503
Nguồn PDF: trang 68

Region Adjacency Graph (RAG) dùng để làm gì trong phân vùng?

- A. Phát hiện biên ban đầu
- B. Biểu diễn quan hệ kề nhau giữa các vùng, hỗ trợ quyết định merge trong region merging
- C. Tính histogram
- D. Tạo mask nhị phân

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Biểu diễn quan hệ kề nhau giữa các vùng, hỗ trợ quyết định merge trong region merging

**Giải thích:** Quan hệ kề nhau xác định những cặp vùng có thể xét để gộp: trong RAG, mỗi vùng là một nút và cạnh nối hai vùng kề nhau. Thông tin này hỗ trợ bước merge được mô tả trong slide, nhưng có cạnh chỉ có nghĩa là hai vùng kề nhau, không có nghĩa chúng chắc chắn đồng nhất. Quyết định gộp vẫn cần kiểm tra đặc trưng của vùng hợp; đồ thị kề vùng không thay thế phép tính histogram hoặc trực tiếp sinh mask nhị phân. Tham chiếu: `IT5409 L5-Segmentation.pdf`, trang 29, 31-32, về điều kiện gộp vùng kề nhau.

</details>

### Câu 504
Nguồn PDF: trang 68

Điều nào đúng về tiêu chí phân vùng tốt?

- A. Tất cả pixel có cùng giá trị
- B. Các vùng đồng nhất nội tại, khác biệt với nhau, biên rõ ràng
- C. Ít vùng nhất có thể
- D. Nhiều vùng nhất có thể

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Các vùng đồng nhất nội tại, khác biệt với nhau, biên rõ ràng

**Giải thích:** Một vùng nên đồng nhất theo đặc trưng đã chọn, còn hai vùng kề nhau phải đủ khác biệt để không thể gộp mà vẫn giữ tính đồng nhất. Ranh giới rõ giúp xác định pixel thuộc vùng nào, nhưng đồng nhất không đòi hỏi mọi pixel có giá trị hoàn toàn bằng nhau; thường nó được kiểm tra bằng một dung sai hoặc predicate. Chỉ tối thiểu hay tối đa số vùng không bảo đảm chất lượng, vì có thể lần lượt gộp nhầm đối tượng hoặc chia đối tượng thành quá nhiều mảnh. Tham chiếu: `IT5409 L5-Segmentation.pdf`, trang 29, 31, 37.

</details>

### Câu 505
Nguồn PDF: trang 68

Phân vùng dựa trên texture (texture-based segmentation) dùng đặc trưng nào?

- A. Histogram màu
- B. GLCM features, Gabor filter responses, LBP
- C. HOG
- D. Hu moments

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. GLCM features, Gabor filter responses, LBP

**Giải thích:** GLCM mô tả quan hệ giữa các mức xám ở một khoảng cách và hướng, Gabor cung cấp đáp ứng lọc theo cấu trúc không gian, còn LBP là một mô tả texture cục bộ. Các đặc trưng này giữ thông tin về cách mẫu cường độ phân bố trong lân cận, phù hợp để tách hai vùng có màu trung bình gần nhau nhưng texture khác nhau. Histogram màu đơn thuần không ghi lại quan hệ không gian đó; HOG và Hu moments chủ yếu mô tả gradient hoặc hình dạng thay vì bộ đặc trưng texture được nêu ở B. Tham chiếu: `IT5409 L4.2-FeatureExtractionAndImageMatching.pdf`, trang 2, 4-6, 15; `IT5409 L5-Segmentation.pdf`, trang 27-28.

</details>

### Câu 506
Nguồn PDF: trang 69

Semantic segmentation trong autonomous driving phân loại pixel thành những lớp nào? (Chọn tất cả đúng)

- A. Road / sidewalk
- B. Vehicle
- C. Pedestrian
- D. Sky / Building

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Road / sidewalk; B. Vehicle; C. Pedestrian; D. Sky / Building

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* Semantic segmentation của cảnh đường phố gán nhãn cho các vùng mặt đường, vỉa hè, phương tiện và người đi bộ để mô tả môi trường xe đang quan sát. Bầu trời và tòa nhà cũng là lớp ngữ nghĩa của cảnh, dù không phải đối tượng cần tránh trực tiếp, nên cả A, B, C, D đều có thể được gán nhãn. Tập lớp chính xác phụ thuộc dataset hoặc hệ thống; segmentation phân biệt lớp theo pixel, không tự suy ra khoảng cách an toàn hay quyết định điều khiển xe. Đối chiếu: [các lớp của Cityscapes](https://www.cityscapes-dataset.com/dataset-overview/).

</details>

### Câu 507
Nguồn PDF: trang 69

Điều nào đúng về "under-segmentation"?

- A. Có quá nhiều vùng nhỏ
- B. Có quá ít vùng; nhiều đối tượng khác nhau bị gom vào cùng một vùng
- C. Biên quá sắc nét
- D. Không có đối tượng nào được phân vùng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Có quá ít vùng; nhiều đối tượng khác nhau bị gom vào cùng một vùng

**Giải thích:** Under-segmentation xảy ra khi một vùng kết quả bao phủ những phần đáng lẽ phải tách riêng, chẳng hạn gom đối tượng và nền hoặc hai đối tượng khác nhau. Khi đó số vùng quá ít so với cấu trúc cần nhận diện, chứ không phải càng ít vùng thì càng tốt. Ngược lại, nhiều vùng nhỏ là over-segmentation; mức phân chia phù hợp phải được xác định theo mục tiêu và độ chi tiết của bài toán, như lưu ý trong phần kết luận của bài giảng. Tham chiếu: `IT5409 L5-Segmentation.pdf`, trang 29, 37-38.

</details>

### Câu 508
Nguồn PDF: trang 69

Phương pháp nào sau đây là unsupervised segmentation?

- A. Yêu cầu ground truth
- B. K-means, Mean Shift, Watershed
- C. Chỉ Supervised CNN
- D. GrabCut

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. K-means, Mean Shift, Watershed

**Giải thích:** K-means phân nhóm từ khoảng cách tới các tâm, Mean Shift tìm các mode của mật độ, còn watershed chia các lưu vực của địa hình ảnh; các cơ chế này không cần học từ một tập mask chuẩn có nhãn. Chúng vẫn cần tham số hoặc lựa chọn xử lý đầu vào, nên unsupervised không có nghĩa là hoàn toàn không cần thiết lập. B nói tới các phiên bản không được hướng dẫn bằng nhãn; supervised CNN cần dữ liệu huấn luyện có nhãn, còn một quy trình tương tác không thuộc cùng thiết lập thuần không giám sát. Tham chiếu: `IT5409 L5-Segmentation.pdf`, trang 14-15, 19-25, 34-36.

</details>

### Câu 509
Nguồn PDF: trang 69

Điều nào đúng về ứng dụng phân vùng trong nhận dạng?

- A. Phân vùng thay thế hoàn toàn nhận dạng
- B. Phân vùng giúp isolate đối tượng quan tâm trước khi nhận dạng
- C. Nhận dạng không cần phân vùng
- D. Phân vùng chỉ dùng sau nhận dạng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Phân vùng giúp isolate đối tượng quan tâm trước khi nhận dạng

**Giải thích:** Mask phân vùng giữ lại pixel của đối tượng quan tâm và loại phần nền khỏi vùng được đưa vào bước phân tích tiếp theo. Điều này có thể giúp đặc trưng phục vụ nhận dạng phản ánh đối tượng thay vì các chi tiết nền không liên quan. Tuy nhiên, tách được vùng chưa cho biết đối tượng thuộc lớp nào, nên phân vùng không thay thế nhận dạng; slide cũng lưu ý đôi khi có thể tránh bước phân vùng, vì vậy B mô tả một ứng dụng hữu ích chứ không phải điều kiện bắt buộc của mọi hệ nhận dạng. Tham chiếu: `IT5409 L5-Segmentation.pdf`, trang 3, 37-38.

</details>

### Câu 510
Nguồn PDF: trang 69

Điều nào đúng về Multi-thresholding?

- A. Dùng 1 ngưỡng chia ảnh thành 2 lớp
- B. Dùng n ngưỡng chia ảnh thành n+1 lớp
- C. Tự động chọn số ngưỡng
- D. Luôn tốt hơn single thresholding

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Dùng n ngưỡng chia ảnh thành n+1 lớp

**Giải thích:** Với n ngưỡng phân biệt được sắp tăng dần, miền cường độ được chia thành một khoảng dưới ngưỡng đầu, n-1 khoảng giữa các ngưỡng và một khoảng trên ngưỡng cuối, tổng cộng n+1 lớp. Ví dụ hai ngưỡng tạo ba lớp tối, trung gian và sáng. Đây là phép chia theo khoảng giá trị, không tự quy định cách chọn n hoặc bảo đảm kết quả tốt hơn một ngưỡng; mỗi lớp giá trị cũng có thể gồm nhiều vùng không liên thông. Tham chiếu: `IT5409 L5-Segmentation.pdf`, trang 7-8.

</details>

### Câu 511
Nguồn PDF: trang 69

Trong phân vùng ảnh y tế, tại sao Deep Learning (U-Net) ngày càng phổ biến?

- A. Vì nó không cần dữ liệu huấn luyện
- B. Vì nó học được đặc trưng phức tạp tự động, vượt trội so với traditional methods
- C. Vì nó nhanh hơn tất cả
- D. Vì không cần GPU

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Vì nó học được đặc trưng phức tạp tự động, vượt trội so với traditional methods

**Giải thích:** Mạng phân vùng học đặc trưng qua các lớp tích chập và tạo dự đoán theo pixel, thay vì chỉ dùng một quy tắc ngưỡng hoặc đặc trưng được thiết kế sẵn. Slide giới thiệu U-Net cho phân vùng ảnh y sinh và U-Net++ khai thác đặc trưng đa tỉ lệ qua các kết nối skip. B nêu lợi thế học biểu diễn phức tạp, nhưng "vượt trội" không nên hiểu là bảo đảm thắng mọi phương pháp trên mọi bộ dữ liệu; mô hình vẫn cần huấn luyện và hiệu quả phụ thuộc dữ liệu, thiết lập đánh giá, tài nguyên. Tham chiếu: `IT5409 L7.3.2-DlForCvSegmentation.pdf`, trang 4-6, 16-17.

</details>

### Câu 512
Nguồn PDF: trang 69

Superpixel-based segmentation có ưu điểm gì?

- A. Cần ít bộ nhớ hơn
- B. Giảm số đơn vị xử lý từ pixel → superpixel, giữ cấu trúc vùng
- C. Loại bỏ mọi nhiễu
- D. Cho kết quả chính xác hơn pixel-based

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Giảm số đơn vị xử lý từ pixel → superpixel, giữ cấu trúc vùng

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* Gom nhiều pixel thành một superpixel làm giảm số nút hoặc đơn vị phải gán nhãn ở bước phân tích tiếp theo, trong khi vẫn giữ thông tin về các vùng liên thông và ranh giới gần đúng. Đây là ưu điểm trực tiếp ở B; tiết kiệm bộ nhớ cũng có thể xảy ra nhưng phụ thuộc cấu trúc dữ liệu và việc có giữ ảnh gốc hay không. Superpixel không loại mọi nhiễu và không bảo đảm chính xác hơn xử lý từng pixel, nhất là khi một superpixel vượt qua biên thật của đối tượng. Đối chiếu: [mục đích của superpixels](https://www.epfl.ch/labs/ivrl/research/slic-superpixels/).

</details>

### Câu 513
Nguồn PDF: trang 69

Điều nào đúng về background subtraction trong video segmentation?

- A. Chỉ hoạt động trong môi trường trong nhà
- B. Trừ frame hiện tại với ảnh nền (background model) để phát hiện foreground (chuyển động)
- C. Cần camera chuyển động
- D. Không liên quan đến phân vùng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Trừ frame hiện tại với ảnh nền (background model) để phát hiện foreground (chuyển động)

**Giải thích:** Background subtraction so sánh khung hình hiện tại với ảnh hoặc mô hình nền và đánh dấu những pixel có sai khác đủ lớn là foreground. Trong thiết lập camera cố định, vùng khác nền thường biểu thị vật thể mới xuất hiện hoặc đang chuyển động; mô hình nền có thể được cập nhật để thích ứng với thay đổi theo thời gian. Camera chuyển động không phải điều kiện cần, và sai khác do bóng hay ánh sáng cũng có thể tạo foreground giả, nên phép trừ không đồng nghĩa với nhận biết chuyển động hoàn hảo. Tham chiếu: `IT5409 L3.1-ImageEnhancement.pdf`, trang 26; `IT5409 L6-Motion.pdf`, trang 46, 50-51.

</details>

### Câu 514
Nguồn PDF: trang 70

Điều nào đúng về sự khác biệt giữa Segmentation và Classification?

- A. Chúng giống nhau
- B. Classification gán nhãn cho toàn ảnh; Segmentation gán nhãn cho từng pixel
- C. Segmentation chỉ gán nhãn cho đối tượng lớn nhất
- D. Classification gán nhãn cho từng pixel

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Classification gán nhãn cho toàn ảnh; Segmentation gán nhãn cho từng pixel

**Giải thích:** Trong image classification, đầu ra cho biết lớp của ảnh nhưng không chỉ vị trí chính xác của các pixel thuộc đối tượng. Semantic segmentation tạo bản đồ nhãn có kích thước không gian tương ứng với ảnh, nên mỗi pixel nhận một lớp và cấu trúc vị trí được giữ lại. Vì câu hỏi đang so sánh hai nhiệm vụ này, B đúng; cần phân biệt với phân vùng truyền thống, vốn có thể chỉ chia vùng đồng nhất mà chưa gán tên lớp ngữ nghĩa. Tham chiếu: `IT5409 L7.3.2-DlForCvSegmentation.pdf`, trang 2-5; `IT5409 L5-Segmentation.pdf`, trang 38.

</details>

### Câu 515
Nguồn PDF: trang 70

F-measure (F1-score) trong đánh giá phân vùng được tính từ gì?

- A. Chỉ từ Precision
- B. Harmonic mean của Precision và Recall
- C. Tích của Precision và Recall
- D. Tổng của Precision và Recall

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Harmonic mean của Precision và Recall

**Giải thích:** F1 = 2 * Precision * Recall / (Precision + Recall), là trung bình điều hòa của hai đại lượng khi mẫu số khác 0. Nó thấp nếu một trong hai rất thấp, nên không cho một precision cao che lấp việc bỏ sót nhiều pixel đối tượng, hoặc một recall cao che lấp nhiều dự đoán thừa. Tích và tổng riêng lẻ không phải công thức F1; chẳng hạn precision = 1 và recall = 0,5 cho F1 khoảng 0,667. Tham chiếu: `IT5409 L7.3.2-DlForCvSegmentation.pdf`, trang 19.

</details>

### Câu 516
Nguồn PDF: trang 70

Điều gì ảnh hưởng đến chất lượng của Region Growing?

- A. Chỉ kích thước ảnh
- B. Lựa chọn seed pixel và tiêu chí đồng nhất (homogeneity criterion)
- C. Chỉ màu sắc ảnh
- D. Kích thước memory

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Lựa chọn seed pixel và tiêu chí đồng nhất (homogeneity criterion)

**Giải thích:** Seed xác định vị trí bắt đầu của vùng, còn tiêu chí đồng nhất quyết định pixel lân cận nào được nhận vào ở từng bước mở rộng. Seed ở sai cấu trúc có thể làm vùng phát triển từ phần không mong muốn; tiêu chí quá lỏng có thể cho vùng vượt qua ranh giới, còn quá chặt khiến nó dừng sớm. Vì hai lựa chọn này trực tiếp điều khiển quá trình tạo vùng, chất lượng không thể được giải thích chỉ bằng kích thước ảnh, màu ảnh hoặc dung lượng bộ nhớ. Tham chiếu: `IT5409 L5-Segmentation.pdf`, trang 29-30.

</details>

### Câu 517
Nguồn PDF: trang 70

Adaptive thresholding (ngưỡng thích nghi) dùng để giải quyết vấn đề nào?

- A. Ảnh quá lớn
- B. Chiếu sáng không đồng đều trên ảnh (uneven illumination)
- C. Ảnh có quá nhiều đối tượng
- D. Ảnh bị nhiễu muối tiêu

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Chiếu sáng không đồng đều trên ảnh (uneven illumination)

**Giải thích:** Khi chiếu sáng không đều, cùng một loại nền hoặc đối tượng có thể mang cường độ rất khác nhau ở các vị trí, khiến một ngưỡng toàn cục phân loại sai một phần ảnh. Adaptive thresholding tính ngưỡng theo vùng hoặc cửa sổ cục bộ để thích ứng với biến thiên đó. Kích thước cửa sổ vẫn quan trọng: quá lớn có thể bỏ qua thay đổi cục bộ, quá nhỏ dễ làm quyết định thiếu ổn định; phương pháp này không tự thay thế một bộ lọc nhiễu muối tiêu. Tham chiếu: `IT5409 L5-Segmentation.pdf`, trang 12-13.

</details>

### Câu 518
Nguồn PDF: trang 70

Điều nào đúng về Mean Shift algorithm?

- A. Cần chỉ định số cluster K trước
- B. Không cần K; tự tìm số cluster; bất biến với outliers
- C. Luôn nhanh hơn K-means
- D. Chỉ hoạt động với 2 cluster

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Không cần K; tự tìm số cluster; bất biến với outliers

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* Mean Shift tìm các mode của mật độ ước lượng rồi gom những điểm hội tụ về cùng mode, nên không cần đặt số cụm K trước; số cụm còn phụ thuộc bandwidth và cách gộp mode. **Lưu ý: B chỉ đúng một phần:** tính robust với outliers không đồng nghĩa với 'bất biến'; điểm ngoại lai vẫn có thể ảnh hưởng mật độ, tạo mode phụ hoặc làm thay đổi kết quả. Thuật toán cũng không luôn nhanh hơn K-means, nên không có lựa chọn hoàn toàn chính xác theo cách viết hiện tại. Đối chiếu: [Mean Shift: A Robust Approach](https://comaniciu.net/Papers/MsRobustApproach.pdf).

</details>

### Câu 519
Nguồn PDF: trang 70

Điều nào KHÔNG phải là ứng dụng của phân vùng ảnh?

- A. Nhận dạng ký tự
- B. Nén video không mất thông tin (lossless compression)
- C. Phát hiện khối u
- D. Tracking đối tượng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Nén video không mất thông tin (lossless compression)

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* Phân vùng ký tự, vùng tổn thương hoặc vùng đối tượng giúp xác định phần ảnh cần nhận dạng, phân tích hay theo dõi, nên A, C, D là các ứng dụng điển hình. B là đáp án dự kiến vì mục tiêu trực tiếp của nén không mất thông tin là mã hóa sao cho khôi phục chính xác dữ liệu, không phải chia ảnh thành vùng có nghĩa. **Lưu ý:** điều này không chứng minh phân vùng không thể hỗ trợ một phương pháp nén theo vùng; cách hỏi loại trừ tuyệt đối chưa chặt chẽ.

</details>

### Câu 520
Nguồn PDF: trang 70

Điều nào đúng về kết quả lý tưởng của phân vùng?

- A. Mỗi pixel thuộc đúng 1 vùng, vùng nội tại đồng nhất và khác biệt với vùng kề
- B. Mỗi pixel có thể thuộc nhiều vùng
- C. Số vùng bằng số pixel
- D. Tất cả pixel cùng vùng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Mỗi pixel thuộc đúng 1 vùng, vùng nội tại đồng nhất và khác biệt với vùng kề

**Giải thích:** Phân vùng cứng tạo một phép chia phủ toàn bộ ảnh: các vùng không chồng nhau, nên mỗi pixel được gán vào đúng một vùng. Mỗi vùng phải đồng nhất theo tiêu chí đã chọn, còn hợp của hai vùng kề nhau phải không đồng nhất, nếu không chúng chưa có lý do để tách riêng. Điều kiện này loại cả hai cực đoan chia mỗi pixel thành một vùng hoặc gom tất cả vào một vùng, trừ những ảnh đặc biệt thực sự thỏa tiêu chí tương ứng. Tham chiếu: `IT5409 L5-Segmentation.pdf`, trang 29.

</details>

### Câu 521
Nguồn PDF: trang 70

Điều nào đúng về Otsu's method và lịch sử?

- A. Được phát triển năm 1979 bởi Nobuyuki Otsu
- B. Là phương pháp bằng tay không tự động
- C. Chỉ dùng cho ảnh màu
- D. Cần training data

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Được phát triển năm 1979 bởi Nobuyuki Otsu

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* Bài báo 'A Threshold Selection Method from Gray-Level Histograms' của Nobuyuki Otsu được công bố trong IEEE Transactions on Systems, Man, and Cybernetics năm 1979, nên A đúng về tác giả và mốc công bố. Phương pháp chọn ngưỡng tự động từ histogram bằng tiêu chí phương sai, không cần người dùng gán nhãn một tập huấn luyện. Nó thường được áp dụng trên ảnh cường độ xám, nên các nhận định chỉ dùng cho ảnh màu hoặc bắt buộc thao tác bằng tay đều không đúng. Đối chiếu: [bài báo Otsu năm 1979](https://ieeexplore.ieee.org/document/4310076).

</details>

### Câu 522
Nguồn PDF: trang 71

Phân vùng dựa trên biên (edge-based) và dựa trên vùng (region- based) có thể kết hợp không?

- A. Không thể kết hợp
- B. Có, hybrid approach dùng biên để hỗ trợ region-based hoặc ngược lại
- C. Chỉ kết hợp trong Deep Learning
- D. Chỉ trong ảnh màu

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Có, hybrid approach dùng biên để hỗ trợ region-based hoặc ngược lại

**Giải thích:** Bài giảng trình bày edge-based và region-based như hai hướng có thể bổ trợ nhau, đồng thời nêu quan hệ giữa đường biên khép kín và vùng. Thông tin biên có thể hạn chế việc mở rộng hoặc gộp vượt sang đối tượng khác, còn thông tin vùng có thể hỗ trợ xác định những ranh giới có ý nghĩa. Do hai hướng mô tả các mặt khác nhau của cùng phép chia ảnh, việc kết hợp không bị giới hạn ở deep learning hoặc ảnh màu. Tham chiếu: `IT5409 L5-Segmentation.pdf`, trang 4-5.

</details>

### Câu 523
Nguồn PDF: trang 71

Điều nào đúng về scale trong phân vùng?

- A. Scale không ảnh hưởng đến phân vùng
- B. Cùng ảnh có thể phân vùng khác nhau ở các scale khác nhau (multi-scale segmentation)
- C. Chỉ phân vùng ở scale nhỏ nhất
- D. Scale chỉ ảnh hưởng đến màu sắc

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Cùng ảnh có thể phân vùng khác nhau ở các scale khác nhau (multi-scale segmentation)

**Giải thích:** Mức chi tiết cần giữ quyết định cấu trúc nào được xem là một vùng: ở mức thô có thể giữ toàn bộ đối tượng, còn mức tinh có thể tách các bộ phận hoặc texture bên trong. Các tham số như độ rộng cửa sổ Mean Shift ảnh hưởng việc các đỉnh đặc trưng được gom lại hay tách ra, nên cùng ảnh có thể có những phân vùng khác nhau. Slide nhấn mạnh phải chọn mức chính xác và chi tiết theo mục tiêu, thay vì cho rằng chỉ phân vùng ở scale nhỏ nhất mới đúng. Tham chiếu: `IT5409 L5-Segmentation.pdf`, trang 25, 37-38.

</details>

### Câu 524
Nguồn PDF: trang 71

Điều nào đúng về cách đánh giá kết quả phân vùng so với ground truth?

- A. Chỉ so sánh số vùng
- B. So sánh mask (nhãn pixel) dự đoán với ground truth bằng các metrics như IoU, pixel accuracy
- C. Chỉ so sánh màu sắc vùng
- D. Chỉ so sánh kích thước vùng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. So sánh mask (nhãn pixel) dự đoán với ground truth bằng các metrics như IoU, pixel accuracy

**Giải thích:** Mask chuẩn và mask dự đoán phải được đối chiếu tại cùng vị trí ảnh để biết pixel nào đúng, thừa hoặc bị bỏ sót. Pixel Accuracy đếm nhãn đúng trên tổng pixel, còn IoU đo phần giao trên phần hợp của vùng dự đoán và vùng chuẩn. Chỉ so số vùng hoặc diện tích không đủ: hai mask có cùng diện tích nhưng nằm ở vị trí khác nhau vẫn có thể không giao nhau, và màu hiển thị của mask không quyết định độ chính xác nhãn. Tham chiếu: `IT5409 L7.3.2-DlForCvSegmentation.pdf`, trang 18-19.

</details>

### Câu 525
Nguồn PDF: trang 71

Điều nào đúng về Dataset benchmark cho semantic segmentation?

- A. Pascal VOC và Cityscapes là hai benchmark phổ biến
- B. Chỉ có 1 dataset duy nhất
- C. Không có benchmark chuẩn
- D. Benchmark chỉ dùng cho deep learning

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Pascal VOC và Cityscapes là hai benchmark phổ biến

**Giải thích:** *Kiến thức bổ sung (không có tham chiếu trong slide).* PASCAL VOC có bài toán đánh giá phân vùng đối tượng theo lớp, còn Cityscapes cung cấp nhãn theo pixel cho cảnh đường phố; cả hai được dùng để so sánh các hệ thống semantic segmentation. Benchmark gồm dữ liệu, nhãn và quy trình đánh giá chung, không phải thuật toán chỉ dành cho deep learning. A vì vậy đúng; việc có nhiều dataset cũng phản ánh khác biệt về miền ảnh và tập lớp, nên kết quả trên một benchmark không tự bảo đảm khả năng khái quát sang mọi miền khác. Đối chiếu: [VOC2012](https://www.robots.ox.ac.uk/~vgg/projects/pascal/VOC/voc2012/), [Cityscapes](https://www.cityscapes-dataset.com/dataset-overview/).

</details>

### Câu 526
Nguồn PDF: trang 71

Điều gì xảy ra khi threshold trong Otsu quá cao?

- A. Phân vùng tốt hơn
- B. Nhiều pixel foreground bị phân loại sai thành background
- C. Over-segmentation
- D. Không thay đổi

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Nhiều pixel foreground bị phân loại sai thành background

**Giải thích:** Đáp án giả định quy ước trong slide: đối tượng sáng là foreground, pixel có f(x, y) >= T nhận nhãn 1 và pixel dưới T nhận nhãn 0. Nếu T bị nâng quá cao, các pixel đối tượng có cường độ nằm giữa ngưỡng đúng và ngưỡng mới bị chuyển sang background, làm tăng false negatives. Đây là ảnh hưởng của ngưỡng bị đặt sai, không phải bảo đảm Otsu luôn chọn ngưỡng quá cao; nếu đối tượng tối và dùng quy ước nhãn đảo thì kết luận cần đổi tương ứng. Tham chiếu: `IT5409 L5-Segmentation.pdf`, trang 7, 11.

</details>

### Câu 527
Nguồn PDF: trang 71

Điều nào đúng về "texture-based" phân vùng vùng mây trong ảnh khí tượng?

- A. Dùng chỉ màu sắc
- B. Dùng đặc trưng texture (Gabor, GLCM) vì mây có pattern khác biệt
- C. Chỉ dùng thresholding đơn giản
- D. Không thể phân vùng mây

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Dùng đặc trưng texture (Gabor, GLCM) vì mây có pattern khác biệt

**Giải thích:** Nếu vùng mây và nền có mẫu biến thiên không gian khác nhau như giả thiết của câu hỏi, texture cung cấp dấu hiệu phân biệt ngoài màu trung bình. GLCM ghi nhận quan hệ mức xám giữa các điểm ở khoảng cách và hướng xác định, còn đáp ứng Gabor mô tả cấu trúc theo hướng và tần số không gian. B vì thế phù hợp với phân vùng theo texture, nhưng không có nghĩa mọi ảnh mây đều tách được chỉ bằng hai đặc trưng này; mức phân biệt còn phụ thuộc ảnh và điều kiện quan sát. Tham chiếu: `IT5409 L4.2-FeatureExtractionAndImageMatching.pdf`, trang 4-6; `IT5409 L5-Segmentation.pdf`, trang 27-28.

</details>

### Câu 528
Nguồn PDF: trang 71

Precision trong đánh giá phân vùng nhị phân được tính như thế nào?

- A. TP / (TP + FN)
- B. TP / (TP + FP)
- C. (TP + TN) / Total
- D. TP × TN

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. TP / (TP + FP)

**Giải thích:** Trong phân vùng nhị phân, TP là pixel đối tượng được dự đoán đúng, còn FP là pixel nền bị dự đoán nhầm thành đối tượng. Tổng TP + FP chính là tất cả pixel được mô hình gán nhãn đối tượng, nên precision đo phần đúng trong các dự đoán dương tính đó. A là recall vì dùng FN ở mẫu số, còn C là accuracy khi Total tính tất cả pixel; các công thức này trả lời những câu hỏi đánh giá khác nhau. Tham chiếu: `IT5409 L7.3.2-DlForCvSegmentation.pdf`, trang 19; `IT5409 L7.2-ObjectDetection.pdf`, trang 40.

</details>

### Câu 529
Nguồn PDF: trang 72

Recall trong đánh giá phân vùng được tính như thế nào?

- A. TP / (TP + FP)
- B. TP / (TP + FN)
- C. TN / (TN + FP)
- D. TP × FN

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. TP / (TP + FN)

**Giải thích:** Recall hỏi trong tất cả pixel thực sự thuộc đối tượng, mô hình đã tìm được bao nhiêu pixel. Tập pixel đối tượng trong ground truth gồm TP được tìm đúng và FN bị bỏ sót, nên tỷ lệ cần tính là TP / (TP + FN). A là precision với tập dự đoán dương tính ở mẫu số, còn C đo tỷ lệ dự đoán đúng trên các pixel nền; recall cao vẫn có thể đi kèm nhiều FP nếu mô hình gán foreground quá rộng. Tham chiếu: `IT5409 L7.3.2-DlForCvSegmentation.pdf`, trang 19; `IT5409 L7.2-ObjectDetection.pdf`, trang 40-41.

</details>

### Câu 530
Nguồn PDF: trang 72

Điều nào đúng về phân vùng dựa trên CNN (Convolutional Neural Networks)?

- A. Cần ít dữ liệu training hơn traditional methods
- B. Học được đặc trưng phức tạp, cho kết quả vượt trội trên nhiều benchmark
- C. Không thể chạy real-time
- D. Chỉ phân vùng nhị phân

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Học được đặc trưng phức tạp, cho kết quả vượt trội trên nhiều benchmark

**Giải thích:** CNN cho phân vùng học các bộ lọc từ dữ liệu và có thể kết hợp thông tin qua nhiều tầng, thay vì chỉ dựa vào một ngưỡng hay đặc trưng thủ công. Mạng fully convolutional trong slide tạo điểm số C x H x W rồi chọn lớp cho mỗi vị trí, nên đầu ra có thể chứa nhiều lớp chứ không bị giới hạn ở phân vùng nhị phân. Đây là cơ sở của lợi thế biểu diễn trong B; tốc độ, nhu cầu dữ liệu và mức vượt trội thực tế phụ thuộc kiến trúc, phần cứng và tập đánh giá, không thể suy ra các khẳng định tuyệt đối ở A hoặc C. Tham chiếu: `IT5409 L7.3.2-DlForCvSegmentation.pdf`, trang 4-6, 16-17, 22-25.

</details>


## CHƯƠNG 6: Chuyển động và Theo dõi

### Câu 531
Nguồn PDF: trang 72

Video được định nghĩa là gì trong bối cảnh Computer Vision?

- A. Chuỗi ảnh màu
- B. Chuỗi frames I(x,y,t) được capture theo thời gian
- C. File đa phương tiện
- D. Dữ liệu 1D

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Chuỗi frames I(x,y,t) được capture theo thời gian

**Giải thích:** <!-- TODO -->

</details>

### Câu 532
Nguồn PDF: trang 72

Optical flow được định nghĩa là gì?

- A. Chuyển động thực sự của các điểm trong cảnh
- B. Chuyển động biểu kiến (apparent motion) của các pattern cường độ sáng trong ảnh
- C. Luồng ánh sáng qua camera
- D. Tốc độ di chuyển của camera

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Chuyển động biểu kiến (apparent motion) của các pattern cường độ sáng trong ảnh

**Giải thích:** <!-- TODO -->

</details>

### Câu 533
Nguồn PDF: trang 72

Optical flow và motion field khác nhau như thế nào?

- A. Chúng giống nhau
- B. Motion field là chuyển động 3D thực chiếu lên ảnh; optical flow là apparent motion có thể khác motion field
- C. Optical flow là 3D, motion field là 2D
- D. Motion field chỉ dùng cho video

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Motion field là chuyển động 3D thực chiếu lên ảnh; optical flow là apparent motion có thể khác motion field

**Giải thích:** <!-- TODO -->

</details>

### Câu 534
Nguồn PDF: trang 72

Giả thiết "Brightness Constancy" trong optical flow phát biểu gì?

- A. Camera có độ sáng cố định
- B. Cường độ sáng của một điểm không thay đổi khi nó di chuyển qua các frames
- C. Nền ảnh luôn sáng
- D. Frame rate không đổi

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Cường độ sáng của một điểm không thay đổi khi nó di chuyển qua các frames

**Giải thích:** <!-- TODO -->

</details>

### Câu 535
Nguồn PDF: trang 72

Giả thiết "Small Motion" trong optical flow có nghĩa là gì?

- A. Đối tượng nhỏ
- B. Các điểm không di chuyển quá xa giữa hai frames liên tiếp (u, v < 1 pixel hoặc nhỏ)
- C. Camera di chuyển chậm
- D. Thời gian giữa 2 frames ngắn

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Các điểm không di chuyển quá xa giữa hai frames liên tiếp (u, v < 1 pixel hoặc nhỏ)

**Giải thích:** <!-- TODO -->

</details>

### Câu 536
Nguồn PDF: trang 73

Phương trình ràng buộc optical flow là gì?

- A. Ix × u + Iy × v = It
- B. Ix × u + Iy × v + It = 0
- C. Ix + Iy + It = 0
- D. Ix × Iy = It

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Ix × u + Iy × v + It = 0

**Giải thích:** <!-- TODO -->

</details>

### Câu 537
Nguồn PDF: trang 73

"Aperture problem" trong optical flow là gì?

- A. Camera có aperture nhỏ
- B. Chỉ có thể xác định component chuyển động dọc theo biên; không thể xác định đủ 2 thành phần (u,v) từ 1 phương trình
- C. Ảnh bị mờ do aperture
- D. Không thể phát hiện chuyển động nhỏ

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Chỉ có thể xác định component chuyển động dọc theo biên; không thể xác định đủ 2 thành phần (u,v) từ 1 phương trình

**Giải thích:** <!-- TODO -->

</details>

### Câu 538
Nguồn PDF: trang 73

Lucas-Kanade method giải quyết aperture problem như thế nào?

- A. Dùng nhiều camera
- B. Giả thiết flow đều trong một cửa sổ nhỏ → overdetermined system → least squares
- C. Tăng framerate
- D. Dùng nhiều ngưỡng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Giả thiết flow đều trong một cửa sổ nhỏ → overdetermined system → least squares

**Giải thích:** <!-- TODO -->

</details>

### Câu 539
Nguồn PDF: trang 73

Horn-Schunck method khác Lucas-Kanade ở điểm nào?

- A. Horn-Schunck cho sparse flow, LK cho dense flow
- B. Horn-Schunck thêm ràng buộc smooth toàn cục → dense flow; LK dùng local window
- C. Horn-Schunck nhanh hơn
- D. LK thêm ràng buộc global smoothness

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Horn-Schunck thêm ràng buộc smooth toàn cục → dense flow; LK dùng local window

**Giải thích:** <!-- TODO -->

</details>

### Câu 540
Nguồn PDF: trang 73

Dense optical flow khác Sparse optical flow ở điểm nào?

- A. Dense nhanh hơn
- B. Dense tính flow cho tất cả pixel; Sparse chỉ tính tại các keypoints/đặc điểm nổi bật
- C. Sparse chính xác hơn
- D. Không có sự khác biệt

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Dense tính flow cho tất cả pixel; Sparse chỉ tính tại các keypoints/đặc điểm nổi bật

**Giải thích:** <!-- TODO -->

</details>

### Câu 541
Nguồn PDF: trang 73

Image pyramid dùng để giải quyết vấn đề gì trong optical flow?

- A. Nhiễu ảnh
- B. Large motion: coarse-to-fine approach, ước lượng rough flow ở resolution thấp rồi refine
- C. Thay đổi ánh sáng
- D. Deformation

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Large motion: coarse-to-fine approach, ước lượng rough flow ở resolution thấp rồi refine

**Giải thích:** <!-- TODO -->

</details>

### Câu 542
Nguồn PDF: trang 73

Trong coarse-to-fine optical flow, thứ tự xử lý là gì?

- A. Fine → Coarse (từ resolution cao đến thấp)
- B. Coarse → Fine (từ resolution thấp đến cao, warp ảnh và tính residual flow)
- C. Tất cả resolution cùng lúc
- D. Ngẫu nhiên

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Coarse → Fine (từ resolution thấp đến cao, warp ảnh và tính residual flow)

**Giải thích:** <!-- TODO -->

</details>

### Câu 543
Nguồn PDF: trang 74

Ứng dụng của optical flow là gì? (Chọn tất cả đúng)

- A. Ước lượng cấu trúc 3D
- B. Phân đoạn đối tượng theo chuyển động
- C. Video stabilization
- D. Nhận dạng hoạt động (action recognition)

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Ước lượng cấu trúc 3D; B. Phân đoạn đối tượng theo chuyển động; C. Video stabilization; D. Nhận dạng hoạt động (action recognition)

**Giải thích:** <!-- TODO -->

</details>

### Câu 544
Nguồn PDF: trang 74

Feature-based tracking (theo dõi dựa trên đặc điểm) hoạt động như thế nào?

- A. Track toàn bộ ảnh
- B. Extract keypoints (Harris, SIFT) từ frame đầu → track qua các frames sau bằng optical flow/matching
- C. Dùng màu sắc để track
- D. Phân vùng mỗi frame riêng lẻ

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Extract keypoints (Harris, SIFT) từ frame đầu → track qua các frames sau bằng optical flow/matching

**Giải thích:** <!-- TODO -->

</details>

### Câu 545
Nguồn PDF: trang 74

Background subtraction dùng để làm gì trong video?

- A. Làm mờ nền
- B. Phát hiện vùng foreground (chuyển động) bằng cách trừ frame hiện tại với background model
- C. Cải thiện chất lượng video
- D. Nén video

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Phát hiện vùng foreground (chuyển động) bằng cách trừ frame hiện tại với background model

**Giải thích:** <!-- TODO -->

</details>

### Câu 546
Nguồn PDF: trang 74

Thách thức của background subtraction là gì? (Chọn tất cả đúng)

- A. Thay đổi chiếu sáng
- B. Camera rung (jitter)
- C. Nền động (swaying trees, water)
- D. Bóng đổ (shadows)

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Thay đổi chiếu sáng; B. Camera rung (jitter); C. Nền động (swaying trees, water); D. Bóng đổ (shadows)

**Giải thích:** <!-- TODO -->

</details>

### Câu 547
Nguồn PDF: trang 74

Kalman Filter dùng để làm gì trong tracking?

- A. Phát hiện đối tượng
- B. Dự đoán vị trí đối tượng tiếp theo và cập nhật dự đoán khi có observation mới
- C. Phân vùng đối tượng
- D. Nhận dạng đối tượng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Dự đoán vị trí đối tượng tiếp theo và cập nhật dự đoán khi có observation mới

**Giải thích:** <!-- TODO -->

</details>

### Câu 548
Nguồn PDF: trang 74

Kalman Filter gồm hai bước chính là gì?

- A. Detection và Recognition
- B. Prediction (dự đoán trạng thái tiếp theo) và Update/Correction (cập nhật với measurement mới)
- C. Segmentation và Tracking
- D. Initialization và Termination

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Prediction (dự đoán trạng thái tiếp theo) và Update/Correction (cập nhật với measurement mới)

**Giải thích:** <!-- TODO -->

</details>

### Câu 549
Nguồn PDF: trang 74

Mean Shift tracking dùng gì để biểu diễn đối tượng?

- A. Bounding box đơn giản
- B. Histogram màu của vùng đối tượng
- C. Mạng neural
- D. 3D model

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Histogram màu của vùng đối tượng

**Giải thích:** <!-- TODO -->

</details>

### Câu 550
Nguồn PDF: trang 74

Particle Filter khác Kalman Filter ở điểm nào?

- A. Chúng giống nhau
- B. Particle Filter dùng particles (mẫu ngẫu nhiên) để xấp xỉ phân phối, xử lý được nonlinear và non-Gaussian
- C. Kalman xử lý nonlinear tốt hơn
- D. Particle Filter chỉ dùng cho ảnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Particle Filter dùng particles (mẫu ngẫu nhiên) để xấp xỉ phân phối, xử lý được nonlinear và non-Gaussian

**Giải thích:** <!-- TODO -->

</details>

### Câu 551
Nguồn PDF: trang 75

Motion field là gì?

- A. Trường vector mô tả optical flow
- B. Chiếu của chuyển động 3D thực trong cảnh lên mặt phẳng ảnh 2D
- C. Phổ tần số của video
- D. Histogram chuyển động

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Chiếu của chuyển động 3D thực trong cảnh lên mặt phẳng ảnh 2D

**Giải thích:** <!-- TODO -->

</details>

### Câu 552
Nguồn PDF: trang 75

Tại sao optical flow ≠ motion field trong thực tế?

- A. Chúng luôn bằng nhau
- B. Vì thay đổi chiếu sáng (không phải chuyển động) cũng tạo ra optical flow (VD: quả cầu xoay đồng nhất)
- C. Vì camera không hoàn hảo
- D. Vì pixel quá nhỏ

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Vì thay đổi chiếu sáng (không phải chuyển động) cũng tạo ra optical flow (VD: quả cầu xoay đồng nhất)

**Giải thích:** <!-- TODO -->

</details>

### Câu 553
Nguồn PDF: trang 75

GMM (Gaussian Mixture Model) trong background subtraction dùng để làm gì?

- A. Phát hiện keypoints
- B. Mô hình hóa background có thể thay đổi theo thời gian bằng mixture of Gaussians
- C. Nén video
- D. Nhận dạng hoạt động

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Mô hình hóa background có thể thay đổi theo thời gian bằng mixture of Gaussians

**Giải thích:** <!-- TODO -->

</details>

### Câu 554
Nguồn PDF: trang 75

Điều nào đúng về KLT (Kanade-Lucas-Tomasi) tracker?

- A. Dùng Lucas-Kanade optical flow để track Harris/Shi-Tomasi corners qua frames
- B. Là phương pháp deep learning
- C. Track tất cả pixel
- D. Không cần keypoints

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Dùng Lucas-Kanade optical flow để track Harris/Shi-Tomasi corners qua frames

**Giải thích:** <!-- TODO -->

</details>

### Câu 555
Nguồn PDF: trang 75

Optical flow của camera đang zoom in (các điểm di chuyển ra xa tâm ảnh) được gọi là gì?

- A. Rotation flow
- B. Expansion flow (diverging pattern)
- C. Translation flow
- D. Compression flow

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Expansion flow (diverging pattern)

**Giải thích:** <!-- TODO -->

</details>

### Câu 556
Nguồn PDF: trang 75

Điều nào đúng về tracking trong occlusion (đối tượng bị che khuất)?

- A. Tracking luôn thất bại khi bị occlusion
- B. Cần cơ chế xử lý: dự đoán (Kalman), re-detection sau khi xuất hiện lại
- C. Không cần xử lý đặc biệt
- D. Occlusion không ảnh hưởng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Cần cơ chế xử lý: dự đoán (Kalman), re-detection sau khi xuất hiện lại

**Giải thích:** <!-- TODO -->

</details>

### Câu 557
Nguồn PDF: trang 75

Farnebäck algorithm là gì?

- A. Phương pháp phát hiện biên
- B. Thuật toán dense optical flow dựa trên polynomial expansion
- C. Phương pháp phân vùng
- D. Phương pháp nhận dạng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Thuật toán dense optical flow dựa trên polynomial expansion

**Giải thích:** <!-- TODO -->

</details>

### Câu 558
Nguồn PDF: trang 76

Template matching tracking (template-based tracking) hoạt động như thế nào?

- A. Học template từ nhiều frames
- B. Dùng SSD/NCC để tìm vùng ảnh frame tiếp theo giống nhất với template (patch từ frame trước)
- C. Dùng deep learning
- D. Phân vùng mỗi frame

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Dùng SSD/NCC để tìm vùng ảnh frame tiếp theo giống nhất với template (patch từ frame trước)

**Giải thích:** <!-- TODO -->

</details>

### Câu 559
Nguồn PDF: trang 76

Điều nào đúng về Lucas-Kanade trong OpenCV?

- A. Cho dense flow
- B. cv2.calcOpticalFlowPyrLK dùng pyramid LK cho sparse tracking
- C. Chỉ cho 1 điểm
- D. Không hỗ trợ pyramid

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. cv2.calcOpticalFlowPyrLK dùng pyramid LK cho sparse tracking

**Giải thích:** <!-- TODO -->

</details>

### Câu 560
Nguồn PDF: trang 76

Điều nào đúng về background model adaptive (thích nghi)?

- A. Background model cố định, không thay đổi
- B. Background model được cập nhật dần theo thời gian để thích nghi với thay đổi chậm
- C. Background model chỉ dùng 1 frame
- D. Background là tất cả pixel

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Background model được cập nhật dần theo thời gian để thích nghi với thay đổi chậm

**Giải thích:** <!-- TODO -->

</details>

### Câu 561
Nguồn PDF: trang 76

DeepSORT là phương pháp tracking nào?

- A. Thuần optical flow
- B. Kết hợp SORT (Kalman + Hungarian) với deep appearance features cho re- identification
- C. Pure deep learning không có motion model
- D. Chỉ dùng bounding box

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Kết hợp SORT (Kalman + Hungarian) với deep appearance features cho re- identification

**Giải thích:** <!-- TODO -->

</details>

### Câu 562
Nguồn PDF: trang 76

Điều nào đúng về SORT (Simple Online and Realtime Tracking)?

- A. Chỉ dùng màu sắc
- B. Kết hợp Kalman filter (prediction) và Hungarian algorithm (assignment) cho multi-object tracking
- C. Là single object tracker
- D. Dùng deep learning hoàn toàn

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Kết hợp Kalman filter (prediction) và Hungarian algorithm (assignment) cho multi-object tracking

**Giải thích:** <!-- TODO -->

</details>

### Câu 563
Nguồn PDF: trang 76

Điều nào đúng về action recognition từ video?

- A. Chỉ dùng ảnh tĩnh
- B. Phân tích temporal pattern của optical flow, skeleton, hoặc video frames để nhận dạng hoạt động
- C. Chỉ dùng audio
- D. Không liên quan đến Computer Vision

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Phân tích temporal pattern của optical flow, skeleton, hoặc video frames để nhận dạng hoạt động

**Giải thích:** <!-- TODO -->

</details>

### Câu 564
Nguồn PDF: trang 76

Điều nào đúng về quan hệ giữa optical flow và chuyển động camera?

- A. Camera đứng yên không ảnh hưởng đến optical flow
- B. Camera chuyển động tạo ra optical flow toàn cục (global motion) ngay cả khi cảnh tĩnh
- C. Chỉ đối tượng chuyển động tạo optical flow
- D. Camera chuyển động triệt tiêu optical flow

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Camera chuyển động tạo ra optical flow toàn cục (global motion) ngay cả khi cảnh tĩnh

**Giải thích:** <!-- TODO -->

</details>

### Câu 565
Nguồn PDF: trang 77

Điều nào đúng về Lucas-Kanade và điều kiện ứng dụng tốt nhất?

- A. Hoạt động tốt với large motion
- B. Hoạt động tốt với small motion và textured regions (không phải vùng đồng nhất)
- C. Chỉ cho dense optical flow
- D. Không cần giả thiết

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Hoạt động tốt với small motion và textured regions (không phải vùng đồng nhất)

**Giải thích:** <!-- TODO -->

</details>

### Câu 566
Nguồn PDF: trang 77

Trong video surveillance, "object detection + tracking" pipeline thường gồm các bước nào?

- A. Chỉ tracking
- B. Detect objects (YOLO/SSD) → Associate detections across frames (tracking)
- C. Chỉ detection
- D. Classification trước rồi detection

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Detect objects (YOLO/SSD) → Associate detections across frames (tracking)

**Giải thích:** <!-- TODO -->

</details>

### Câu 567
Nguồn PDF: trang 77

Điều nào đúng về Tomasi-Kanade feature selection cho tracking?

- A. Chọn ngẫu nhiên
- B. Chọn corners có eigenvalue nhỏ nhất của structure matrix lớn → "good features to track"
- C. Chọn pixel sáng nhất
- D. Chọn tất cả pixel

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Chọn corners có eigenvalue nhỏ nhất của structure matrix lớn → "good features to track"

**Giải thích:** <!-- TODO -->

</details>

### Câu 568
Nguồn PDF: trang 77

Điều nào đúng về Lucas-Kanade với pyramid (PyLK)?

- A. Pyramid không cần thiết
- B. Tính flow ở Gaussian pyramid từ coarse đến fine level; xử lý được motion lớn hơn
- C. Chỉ dùng 1 level
- D. Pyramid làm giảm chính xác

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Tính flow ở Gaussian pyramid từ coarse đến fine level; xử lý được motion lớn hơn

**Giải thích:** <!-- TODO -->

</details>

### Câu 569
Nguồn PDF: trang 77

Điều nào đúng về correlation-based tracking?

- A. Không thể track thời gian thực
- B. MOSSE, CSK, KCF dùng correlation filter trong Fourier domain để tracking nhanh
- C. Chỉ track 1 màu
- D. Cần multiple cameras

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. MOSSE, CSK, KCF dùng correlation filter trong Fourier domain để tracking nhanh

**Giải thích:** <!-- TODO -->

</details>

### Câu 570
Nguồn PDF: trang 77

Điều nào đúng về Siamese network trong tracking?

- A. Dùng 2 identical networks để so sánh template với search region
- B. Chỉ dùng 1 network
- C. Không dùng deep learning
- D. Chỉ track khuôn mặt

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Dùng 2 identical networks để so sánh template với search region

**Giải thích:** <!-- TODO -->

</details>

### Câu 571
Nguồn PDF: trang 77

Ứng dụng video segmentation cho ô tô tự lái dùng kỹ thuật nào?

- A. Chỉ background subtraction
- B. Kết hợp optical flow, semantic segmentation, và object detection
- C. Chỉ object detection
- D. Không dùng phân vùng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Kết hợp optical flow, semantic segmentation, và object detection

**Giải thích:** <!-- TODO -->

</details>

### Câu 572
Nguồn PDF: trang 77

Điều nào đúng về Multi-Object Tracking (MOT)?

- A. Chỉ track 1 đối tượng
- B. Track nhiều đối tượng đồng thời; cần giải bài toán data association (gán track cho detection)
- C. Không cần detection
- D. Dùng manual annotation

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Track nhiều đối tượng đồng thời; cần giải bài toán data association (gán track cho detection)

**Giải thích:** <!-- TODO -->

</details>

### Câu 573
Nguồn PDF: trang 78

Hungarian Algorithm trong MOT dùng để làm gì?

- A. Phát hiện đối tượng
- B. Gán (assign) detections cho tracks hiện tại theo cách tối ưu (minimum cost assignment)
- C. Dự đoán vị trí
- D. Phân vùng đối tượng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Gán (assign) detections cho tracks hiện tại theo cách tối ưu (minimum cost assignment)

**Giải thích:** <!-- TODO -->

</details>

### Câu 574
Nguồn PDF: trang 78

Điều nào đúng về long-term tracking so với short-term tracking?

- A. Long-term tracking dễ hơn
- B. Long-term phải xử lý occlusion, out-of-view, và re-identification
- C. Short-term phức tạp hơn
- D. Chúng giống nhau

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Long-term phải xử lý occlusion, out-of-view, và re-identification

**Giải thích:** <!-- TODO -->

</details>

### Câu 575
Nguồn PDF: trang 78

Video optical flow có ứng dụng trong compression không?

- A. Không liên quan
- B. Có, motion compensation trong video codecs (H.264, HEVC) dùng optical flow để dự đoán frame
- C. Chỉ dùng cho ảnh tĩnh
- D. Làm tăng kích thước file

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Có, motion compensation trong video codecs (H.264, HEVC) dùng optical flow để dự đoán frame

**Giải thích:** <!-- TODO -->

</details>

### Câu 576
Nguồn PDF: trang 78

Điều nào đúng về video stabilization dùng optical flow?

- A. Thêm shake vào video
- B. Ước lượng global motion (camera shake) và bù lại để tạo video mượt mà
- C. Chỉ giảm frame rate
- D. Cắt video

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Ước lượng global motion (camera shake) và bù lại để tạo video mượt mà

**Giải thích:** <!-- TODO -->

</details>

### Câu 577
Nguồn PDF: trang 78

Optical flow được tính dựa trên bao nhiêu giả thiết cơ bản?

- A. 1
- B. 2: Brightness constancy và Small motion
- C. 3
- D. Không cần giả thiết

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. 2: Brightness constancy và Small motion

**Giải thích:** <!-- TODO -->

</details>

### Câu 578
Nguồn PDF: trang 78

Điều nào đúng về event cameras (neuromorphic cameras) so với frame-based cameras?

- A. Không liên quan đến optical flow
- B. Event cameras ghi nhận thay đổi intensity theo từng pixel (asynchronous), phù hợp cho fast motion flow
- C. Chậm hơn frame cameras
- D. Chỉ cho ảnh grayscale

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Event cameras ghi nhận thay đổi intensity theo từng pixel (asynchronous), phù hợp cho fast motion flow

**Giải thích:** <!-- TODO -->

</details>

### Câu 579
Nguồn PDF: trang 78

Điều nào đúng về Horn-Schunck và việc chọn tham số α?

- A. α không ảnh hưởng đến kết quả
- B. α lớn → flow mượt hơn nhưng kém chính xác tại biên; α nhỏ → flow chi tiết hơn nhưng noisier
- C. α luôn phải = 1
- D. α chỉ ảnh hưởng đến tốc độ

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. α lớn → flow mượt hơn nhưng kém chính xác tại biên; α nhỏ → flow chi tiết hơn nhưng noisier

**Giải thích:** <!-- TODO -->

</details>

### Câu 580
Nguồn PDF: trang 79

Điều nào đúng về ứng dụng optical flow trong action recognition?

- A. Optical flow không dùng trong action recognition
- B. Two-stream networks: 1 stream xử lý RGB frames, 1 stream xử lý stacked optical flow
- C. Chỉ dùng 1 stream
- D. Dùng audio thay vì optical flow

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Two-stream networks: 1 stream xử lý RGB frames, 1 stream xử lý stacked optical flow

**Giải thích:** <!-- TODO -->

</details>


## CHƯƠNG 7: Deep Learning cho Computer Vision

### Câu 581
Nguồn PDF: trang 79

Deep Learning khác Traditional Machine Learning ở điểm gì?

- A. Deep Learning dùng ít data hơn
- B. Deep Learning học tự động đặc trưng từ dữ liệu thô; TML cần hand-crafted features
- C. TML cho kết quả tốt hơn
- D. Deep Learning chỉ dùng cho ảnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Deep Learning học tự động đặc trưng từ dữ liệu thô; TML cần hand-crafted features

**Giải thích:** <!-- TODO -->

</details>

### Câu 582
Nguồn PDF: trang 79

CNN (Convolutional Neural Network) phù hợp với xử lý ảnh vì lý do gì?

- A. Nhanh nhất trong mọi task
- B. Khai thác tính local và translational equivariance của ảnh; parameter sharing giảm số tham số
- C. Không cần training
- D. Chỉ dùng được với GPU

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Khai thác tính local và translational equivariance của ảnh; parameter sharing giảm số tham số

**Giải thích:** <!-- TODO -->

</details>

### Câu 583
Nguồn PDF: trang 79

Convolution layer trong CNN thực hiện điều gì?

- A. Nhân ma trận thông thường
- B. Tích chập input với learnable filters → tạo feature maps
- C. Pooling
- D. Normalization

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Tích chập input với learnable filters → tạo feature maps

**Giải thích:** <!-- TODO -->

</details>

### Câu 584
Nguồn PDF: trang 79

ReLU activation function được định nghĩa là gì?

- A. sigmoid(x)
- B. max(0, x)
- C. tanh(x)
- D. x²

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. max(0, x)

**Giải thích:** <!-- TODO -->

</details>

### Câu 585
Nguồn PDF: trang 79

Tại sao ReLU phổ biến hơn Sigmoid trong deep network?

- A. ReLU chậm hơn nhưng chính xác hơn
- B. ReLU không bị vanishing gradient problem như Sigmoid, và tính toán đơn giản
- C. Sigmoid cho kết quả tốt hơn
- D. ReLU cần ít memory hơn

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. ReLU không bị vanishing gradient problem như Sigmoid, và tính toán đơn giản

**Giải thích:** <!-- TODO -->

</details>

### Câu 586
Nguồn PDF: trang 79

Max Pooling trong CNN dùng để làm gì?

- A. Tăng kích thước feature map
- B. Giảm kích thước không gian (spatial), tăng invariance với dịch chuyển nhỏ
- C. Thêm nonlinearity
- D. Normalize activations

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Giảm kích thước không gian (spatial), tăng invariance với dịch chuyển nhỏ

**Giải thích:** <!-- TODO -->

</details>

### Câu 587
Nguồn PDF: trang 80

AlexNet thắng ImageNet ILSVRC 2012 với kiến trúc gồm bao nhiêu conv layers?

- A. 3
- B. 5
- C. 8
- D. 10

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. 5

**Giải thích:** <!-- TODO -->

</details>

### Câu 588
Nguồn PDF: trang 80

AlexNet giới thiệu những kỹ thuật mới nào? (Chọn tất cả đúng)

- A. ReLU activation
- B. Dropout regularization
- C. Data augmentation
- D. GPU training

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. ReLU activation; B. Dropout regularization; C. Data augmentation; D. GPU training

**Giải thích:** <!-- TODO -->

</details>

### Câu 589
Nguồn PDF: trang 80

VGGNet (VGG-16/VGG-19) có đặc điểm gì?

- A. Dùng large 7×7 filters
- B. Dùng nhiều 3×3 filters nhỏ nhưng deep; đơn giản, dễ hiểu
- C. Không có max pooling
- D. Chỉ 5 layers

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Dùng nhiều 3×3 filters nhỏ nhưng deep; đơn giản, dễ hiểu

**Giải thích:** <!-- TODO -->

</details>

### Câu 590
Nguồn PDF: trang 80

Tại sao dùng nhiều filter 3×3 thay vì 1 filter lớn (7×7)?

- A. 3×3 cho kết quả kém hơn nhưng nhanh hơn
- B. Nhiều 3×3 có cùng receptive field nhưng ít tham số hơn và thêm nonlinearity
- C. 7×7 không hoạt động với CNN
- D. 3×3 dễ cài đặt hơn

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Nhiều 3×3 có cùng receptive field nhưng ít tham số hơn và thêm nonlinearity

**Giải thích:** <!-- TODO -->

</details>

### Câu 591
Nguồn PDF: trang 80

ResNet giải quyết vấn đề gì trong deep network?

- A. Overfitting
- B. Vanishing gradient: skip connections (residual connections) cho phép gradient flow qua
- C. Quá ít parameters
- D. Chậm training

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Vanishing gradient: skip connections (residual connections) cho phép gradient flow qua

**Giải thích:** <!-- TODO -->

</details>

### Câu 592
Nguồn PDF: trang 80

Skip connection trong ResNet (Residual Learning) thực hiện điều gì?

- A. Bỏ qua toàn bộ block
- B. Cộng input của block vào output: F(x) + x → mạng học residual F(x) thay vì mapping trực tiếp
- C. Nối (concatenate) input và output
- D. Nhân input với output

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Cộng input của block vào output: F(x) + x → mạng học residual F(x) thay vì mapping trực tiếp

**Giải thích:** <!-- TODO -->

</details>

### Câu 593
Nguồn PDF: trang 80

Transfer Learning trong Computer Vision hoạt động như thế nào?

- A. Train từ đầu trên dataset nhỏ
- B. Dùng model pre-trained trên ImageNet, fine-tune cho task mới với ít data
- C. Chuyển features từ ảnh sang text
- D. Dùng nhiều GPU

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Dùng model pre-trained trên ImageNet, fine-tune cho task mới với ít data

**Giải thích:** <!-- TODO -->

</details>

### Câu 594
Nguồn PDF: trang 81

Batch Normalization làm gì?

- A. Giảm số batch trong training
- B. Normalize activations theo từng batch, giúp ổn định training và cho phép learning rate cao hơn
- C. Tăng batch size
- D. Chuẩn hóa input image

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Normalize activations theo từng batch, giúp ổn định training và cho phép learning rate cao hơn

**Giải thích:** <!-- TODO -->

</details>

### Câu 595
Nguồn PDF: trang 81

Dropout trong training CNN dùng để làm gì?

- A. Giảm số layers
- B. Ngẫu nhiên vô hiệu hóa neurons trong training → regularization, giảm overfitting
- C. Tăng tốc inference
- D. Giảm số classes

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Ngẫu nhiên vô hiệu hóa neurons trong training → regularization, giảm overfitting

**Giải thích:** <!-- TODO -->

</details>

### Câu 596
Nguồn PDF: trang 81

ImageNet dataset gồm bao nhiêu classes?

- A. 100
- B. 1000
- C. 10000
- D. 100000

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. 1000

**Giải thích:** <!-- TODO -->

</details>

### Câu 597
Nguồn PDF: trang 81

CIFAR-10 dataset có bao nhiêu classes và kích thước ảnh?

- A. 100 classes, 64×64
- B. 10 classes, 32×32
- C. 10 classes, 224×224
- D. 1000 classes, 32×32

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. 10 classes, 32×32

**Giải thích:** <!-- TODO -->

</details>

### Câu 598
Nguồn PDF: trang 81

Fully Connected layer (FC layer) khác Convolution layer ở điểm nào?

- A. FC dùng filters như Conv
- B. FC kết nối mọi neuron với mọi neuron của layer trước (dense); Conv dùng local receptive field và weight sharing
- C. FC nhanh hơn
- D. FC cho spatial features

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. FC kết nối mọi neuron với mọi neuron của layer trước (dense); Conv dùng local receptive field và weight sharing

**Giải thích:** <!-- TODO -->

</details>

### Câu 599
Nguồn PDF: trang 81

Receptive field của neuron trong CNN là gì?

- A. Số filters trong layer
- B. Vùng ảnh đầu vào ảnh hưởng đến giá trị của neuron đó
- C. Kích thước feature map
- D. Số parameters

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Vùng ảnh đầu vào ảnh hưởng đến giá trị của neuron đó

**Giải thích:** <!-- TODO -->

</details>

### Câu 600
Nguồn PDF: trang 81

Dilated (Atrous) Convolution tăng receptive field như thế nào?

- A. Tăng kích thước filter
- B. Chèn zeros vào filter (dilation rate d), không giảm resolution
- C. Dùng pooling
- D. Giảm stride

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Chèn zeros vào filter (dilation rate d), không giảm resolution

**Giải thích:** <!-- TODO -->

</details>

### Câu 601
Nguồn PDF: trang 81

GoogLeNet (Inception) giới thiệu Inception module là gì?

- A. Chỉ dùng 1 filter size
- B. Dùng song song 1×1, 3×3, 5×5 convolutions và max pooling → concatenate output
- C. Loại bỏ fully connected
- D. Thay thế ReLU bằng Sigmoid

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Dùng song song 1×1, 3×3, 5×5 convolutions và max pooling → concatenate output

**Giải thích:** <!-- TODO -->

</details>

### Câu 602
Nguồn PDF: trang 82

1×1 Convolution (bottleneck) dùng để làm gì?

- A. Làm to feature map
- B. Giảm số channels (dimensionality reduction), add nonlinearity mà không thay đổi spatial size
- C. Phát hiện biên
- D. Thay thế max pooling

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Giảm số channels (dimensionality reduction), add nonlinearity mà không thay đổi spatial size

**Giải thích:** <!-- TODO -->

</details>

### Câu 603
Nguồn PDF: trang 82

DenseNet khác ResNet ở điểm nào?

- A. Không có skip connections
- B. Kết nối mỗi layer với tất cả layers trước đó (concatenate), tăng feature reuse
- C. Chỉ có 1 skip connection
- D. Sử dụng subtractive connections

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Kết nối mỗi layer với tất cả layers trước đó (concatenate), tăng feature reuse

**Giải thích:** <!-- TODO -->

</details>

### Câu 604
Nguồn PDF: trang 82

MobileNet dùng kỹ thuật nào để giảm params?

- A. Fewer layers
- B. Depthwise Separable Convolution: depthwise conv + pointwise (1×1) conv
- C. Smaller input size
- D. Không dùng ReLU

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Depthwise Separable Convolution: depthwise conv + pointwise (1×1) conv

**Giải thích:** <!-- TODO -->

</details>

### Câu 605
Nguồn PDF: trang 82

Softmax function được dùng ở output layer để làm gì?

- A. Regularization
- B. Chuyển raw scores thành probability distribution (tổng = 1) cho classification
- C. Normalize activations trong network
- D. Thay thế ReLU

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Chuyển raw scores thành probability distribution (tổng = 1) cho classification

**Giải thích:** <!-- TODO -->

</details>

### Câu 606
Nguồn PDF: trang 82

Cross-entropy loss function trong classification được tính như thế nào?

- A. MSE giữa predicted và true label
- B. -Σ y_i × log(ŷ_i) - đo khoảng cách giữa predicted probability và true label
- C. Absolute difference
- D. Hinge loss

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. -Σ y_i × log(ŷ_i) - đo khoảng cách giữa predicted probability và true label

**Giải thích:** <!-- TODO -->

</details>

### Câu 607
Nguồn PDF: trang 82

Data augmentation trong training CNN nhằm mục đích gì?

- A. Tăng tốc training
- B. Artificially tăng dataset bằng transformations → giảm overfitting, tăng generalization
- C. Giảm dataset size
- D. Tăng model size

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Artificially tăng dataset bằng transformations → giảm overfitting, tăng generalization

**Giải thích:** <!-- TODO -->

</details>

### Câu 608
Nguồn PDF: trang 82

Kỹ thuật Fine-tuning trong Transfer Learning thực hiện điều gì?

- A. Train toàn bộ model từ scratch
- B. Giải phóng một số layers cuối của pre-trained model và retrain với low learning rate trên new task
- C. Chỉ thay đổi output layer
- D. Freeze toàn bộ model

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Giải phóng một số layers cuối của pre-trained model và retrain với low learning rate trên new task

**Giải thích:** <!-- TODO -->

</details>

### Câu 609
Nguồn PDF: trang 83

Điều nào đúng về Depthwise Separable Convolution?

- A. Tốn nhiều params hơn standard conv
- B. Tách conv thành depthwise (per-channel) + pointwise (1×1 across channels) → ít params hơn ~8-9x
- C. Kém chính xác hơn nhiều
- D. Chỉ dùng cho mobile devices

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Tách conv thành depthwise (per-channel) + pointwise (1×1 across channels) → ít params hơn ~8-9x

**Giải thích:** <!-- TODO -->

</details>

### Câu 610
Nguồn PDF: trang 83

Điều nào đúng về validation set trong training?

- A. Dùng để update model weights
- B. Dùng để tune hyperparameters và kiểm tra generalization trong quá trình training
- C. Dùng để tính final performance
- D. Không cần thiết

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Dùng để tune hyperparameters và kiểm tra generalization trong quá trình training

**Giải thích:** <!-- TODO -->

</details>

### Câu 611
Nguồn PDF: trang 83

Deep learning vs Human performance: DeepFace đạt độ chính xác bao nhiêu cho face verification?

- A. 90.5%
- B. 97.35%
- C. 85.2%
- D. 99.1%

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. 97.35%

**Giải thích:** <!-- TODO -->

</details>

### Câu 612
Nguồn PDF: trang 83

Điều nào đúng về SqueezeNet?

- A. Lớn và chính xác nhất
- B. Kiến trúc nhỏ gọn đạt AlexNet accuracy với ít params hơn 50x
- C. Chỉ dùng cho detection
- D. Không dùng được trên mobile

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Kiến trúc nhỏ gọn đạt AlexNet accuracy với ít params hơn 50x

**Giải thích:** <!-- TODO -->

</details>

### Câu 613
Nguồn PDF: trang 83

EfficientNet mở rộng CNN theo các chiều nào?

- A. Chỉ depth
- B. Compound scaling: đồng thời depth, width, và resolution theo tỉ lệ
- C. Chỉ width
- D. Chỉ resolution

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Compound scaling: đồng thời depth, width, và resolution theo tỉ lệ

**Giải thích:** <!-- TODO -->

</details>

### Câu 614
Nguồn PDF: trang 83

Stride trong convolution layer ảnh hưởng đến gì?

- A. Số filters
- B. Kích thước output feature map (stride lớn → output nhỏ hơn)
- C. Giá trị weights
- D. Số channels

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Kích thước output feature map (stride lớn → output nhỏ hơn)

**Giải thích:** <!-- TODO -->

</details>

### Câu 615
Nguồn PDF: trang 83

Padding trong convolution dùng để làm gì?

- A. Tăng số filters
- B. Thêm zeros xung quanh input để kiểm soát kích thước output
- C. Giảm training time
- D. Tăng depth

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Thêm zeros xung quanh input để kiểm soát kích thước output

**Giải thích:** <!-- TODO -->

</details>

### Câu 616
Nguồn PDF: trang 84

Điều nào đúng về Gradient Descent trong training CNN?

- A. Tìm global minimum trong mọi trường hợp
- B. Iterative optimization: cập nhật weights theo hướng negative gradient của loss
- C. Chỉ dùng cho convex problems
- D. Không cần learning rate

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Iterative optimization: cập nhật weights theo hướng negative gradient của loss

**Giải thích:** <!-- TODO -->

</details>

### Câu 617
Nguồn PDF: trang 84

Mini-batch SGD khác Full-batch GD ở điểm nào?

- A. Mini-batch chính xác hơn
- B. Mini-batch dùng subset nhỏ của data mỗi step → nhanh hơn, có thể thoát local minima
- C. Full-batch nhanh hơn
- D. Không có sự khác biệt

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Mini-batch dùng subset nhỏ của data mỗi step → nhanh hơn, có thể thoát local minima

**Giải thích:** <!-- TODO -->

</details>

### Câu 618
Nguồn PDF: trang 84

Điều nào đúng về Adam optimizer?

- A. Không cần tuning learning rate
- B. Adaptive learning rate per parameter, kết hợp momentum và RMSprop
- C. Chậm nhất trong các optimizers
- D. Không phù hợp cho deep learning

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Adaptive learning rate per parameter, kết hợp momentum và RMSprop

**Giải thích:** <!-- TODO -->

</details>

### Câu 619
Nguồn PDF: trang 84

Layer Normalization khác Batch Normalization ở điểm nào?

- A. Không có sự khác biệt
- B. Layer Norm normalize qua features (không phải batch) → hoạt động tốt với batch size nhỏ/RNN
- C. Batch Norm tốt hơn trong mọi trường hợp
- D. Layer Norm chỉ dùng cho images

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Layer Norm normalize qua features (không phải batch) → hoạt động tốt với batch size nhỏ/RNN

**Giải thích:** <!-- TODO -->

</details>

### Câu 620
Nguồn PDF: trang 84

Global Average Pooling (GAP) thay thế FC layer như thế nào?

- A. Không thể thay thế FC
- B. GAP lấy average của mỗi feature map → vector; giảm params, hạn chế overfitting
- C. GAP tăng params
- D. GAP chỉ dùng cho ảnh màu

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. GAP lấy average của mỗi feature map → vector; giảm params, hạn chế overfitting

**Giải thích:** <!-- TODO -->

</details>

### Câu 621
Nguồn PDF: trang 84

Điều nào đúng về interpretability (khả năng giải thích) của CNN?

- A. CNN hoàn toàn transparent
- B. CNN thường là black-box; Grad-CAM, feature visualization giúp hiểu CNN đang nhìn vào đâu
- C. CNN không thể giải thích được
- D. Chỉ ResNet có thể giải thích

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. CNN thường là black-box; Grad-CAM, feature visualization giúp hiểu CNN đang nhìn vào đâu

**Giải thích:** <!-- TODO -->

</details>

### Câu 622
Nguồn PDF: trang 84

Điều nào đúng về AlphaGo và Deep Learning?

- A. AlphaGo không dùng Deep Learning
- B. AlphaGo dùng CNN cho policy và value network; đánh bại con người 9-1
- C. AlphaGo dùng pure rule-based
- D. AlphaGo chỉ thắng beginner level

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. AlphaGo dùng CNN cho policy và value network; đánh bại con người 9-1

**Giải thích:** <!-- TODO -->

</details>

### Câu 623
Nguồn PDF: trang 84

Điều nào đúng về CNN và spatial invariance?

- A. CNN hoàn toàn invariant với translation
- B. Pooling cho partial translation invariance; nhưng CNN nói chung equivariant hơn invariant
- C. CNN không có spatial invariance
- D. Conv layer cho hoàn toàn invariance

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Pooling cho partial translation invariance; nhưng CNN nói chung equivariant hơn invariant

**Giải thích:** <!-- TODO -->

</details>

### Câu 624
Nguồn PDF: trang 85

Điều nào đúng về Receptive Field với depth của network?

- A. RF không tăng theo depth
- B. RF tăng với mỗi layer; deeper network → larger effective receptive field → capture global context
- C. RF chỉ phụ thuộc vào filter size
- D. RF giảm với depth

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. RF tăng với mỗi layer; deeper network → larger effective receptive field → capture global context

**Giải thích:** <!-- TODO -->

</details>

### Câu 625
Nguồn PDF: trang 85

Điều nào đúng về hai-stream networks trong video understanding?

- A. Chỉ dùng 1 stream
- B. Spatial stream xử lý RGB; temporal stream xử lý stacked optical flow
- C. Không dùng optical flow
- D. Cần 3 streams

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Spatial stream xử lý RGB; temporal stream xử lý stacked optical flow

**Giải thích:** <!-- TODO -->

</details>

### Câu 626
Nguồn PDF: trang 85

R-CNN (Region-based CNN) được phát triển bởi ai?

- A. Fei-Fei Li
- B. Ross Girshick et al., CVPR 2014
- C. Andrew Ng
- D. Yann LeCun

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Ross Girshick et al., CVPR 2014

**Giải thích:** <!-- TODO -->

</details>

### Câu 627
Nguồn PDF: trang 85

R-CNN hoạt động theo pipeline nào?

- A. Direct regression
- B. Region proposals (Selective Search) → warp → CNN features → SVM classify
- C. Anchor-based detection
- D. Grid-based detection

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Region proposals (Selective Search) → warp → CNN features → SVM classify

**Giải thích:** <!-- TODO -->

</details>

### Câu 628
Nguồn PDF: trang 85

Nhược điểm chính của R-CNN so với Fast R-CNN?

- A. R-CNN cho kết quả kém hơn
- B. R-CNN chậm vì phải chạy CNN riêng cho từng region proposal (~2000 lần)
- C. R-CNN không dùng được
- D. R-CNN cần nhiều GPU hơn

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. R-CNN chậm vì phải chạy CNN riêng cho từng region proposal (~2000 lần)

**Giải thích:** <!-- TODO -->

</details>

### Câu 629
Nguồn PDF: trang 85

Fast R-CNN cải thiện R-CNN như thế nào?

- A. Dùng ít region proposals hơn
- B. Chạy CNN 1 lần trên toàn ảnh → feature map → RoI Pooling → classify từng region
- C. Không dùng region proposals
- D. Dùng anchor boxes

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Chạy CNN 1 lần trên toàn ảnh → feature map → RoI Pooling → classify từng region

**Giải thích:** <!-- TODO -->

</details>

### Câu 630
Nguồn PDF: trang 85

RoI (Region of Interest) Pooling làm gì?

- A. Tạo region proposals
- B. Extract fixed-size feature vector từ bất kỳ vùng RoI nào trong feature map
- C. Classify objects
- D. Regress bounding boxes

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Extract fixed-size feature vector từ bất kỳ vùng RoI nào trong feature map

**Giải thích:** <!-- TODO -->

</details>

### Câu 631
Nguồn PDF: trang 86

Faster R-CNN cải thiện Fast R-CNN như thế nào?

- A. Loại bỏ bounding box regression
- B. Thay Selective Search bằng Region Proposal Network (RPN) học được; end- to-end training
- C. Dùng 1 stage
- D. Không dùng RoI Pooling

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Thay Selective Search bằng Region Proposal Network (RPN) học được; end- to-end training

**Giải thích:** <!-- TODO -->

</details>

### Câu 632
Nguồn PDF: trang 86

RPN (Region Proposal Network) làm gì?

- A. Classify objects
- B. Predict objectness score và bbox của các anchor boxes → tạo proposals
- C. Extract features
- D. Perform NMS

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Predict objectness score và bbox của các anchor boxes → tạo proposals

**Giải thích:** <!-- TODO -->

</details>

### Câu 633
Nguồn PDF: trang 86

Anchor boxes trong object detection là gì?

- A. Bounding box cuối cùng
- B. Prior boxes với aspect ratios và scales định sẵn, dùng làm reference cho prediction
- C. Ground truth boxes
- D. Proposals từ Selective Search

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Prior boxes với aspect ratios và scales định sẵn, dùng làm reference cho prediction

**Giải thích:** <!-- TODO -->

</details>

### Câu 634
Nguồn PDF: trang 86

YOLO (You Only Look Once) phát hiện đối tượng như thế nào?

- A. Hai stages: propose rồi classify
- B. Một stage: chia ảnh thành grid, mỗi cell predict bbox và class đồng thời
- C. Chỉ phát hiện 1 đối tượng
- D. Dùng Selective Search

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Một stage: chia ảnh thành grid, mỗi cell predict bbox và class đồng thời

**Giải thích:** <!-- TODO -->

</details>

### Câu 635
Nguồn PDF: trang 86

YOLO nhanh hơn Faster R-CNN vì lý do gì?

- A. Dùng ít layers hơn
- B. Single-stage: không có separate proposal stage; predict trực tiếp từ image
- C. Dùng ít anchor boxes hơn
- D. Không cần NMS

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Single-stage: không có separate proposal stage; predict trực tiếp từ image

**Giải thích:** <!-- TODO -->

</details>

### Câu 636
Nguồn PDF: trang 86

SSD (Single Shot Detector) dùng gì để phát hiện đa scale?

- A. Image pyramid
- B. Multi-scale feature maps: detect objects ở các scales khác nhau từ các levels của feature pyramid
- C. Selective Search
- D. RPN

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Multi-scale feature maps: detect objects ở các scales khác nhau từ các levels của feature pyramid

**Giải thích:** <!-- TODO -->

</details>

### Câu 637
Nguồn PDF: trang 86

IoU (Intersection over Union) trong object detection được dùng để làm gì? (Chọn tất cả đúng)

- A. Đánh giá chất lượng predicted bbox so với ground truth
- B. Xác định positive/negative samples khi training
- C. Trong NMS để loại bbox trùng lặp
- D. Tính mAP

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Đánh giá chất lượng predicted bbox so với ground truth; B. Xác định positive/negative samples khi training; C. Trong NMS để loại bbox trùng lặp; D. Tính mAP

**Giải thích:** <!-- TODO -->

</details>

### Câu 638
Nguồn PDF: trang 86

NMS (Non-Maximum Suppression) trong object detection làm gì?

- A. Tìm thêm objects
- B. Loại bỏ redundant overlapping boxes: giữ box confidence cao nhất, loại boxes có IoU > threshold
- C. Tăng số proposals
- D. Classify objects

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Loại bỏ redundant overlapping boxes: giữ box confidence cao nhất, loại boxes có IoU > threshold

**Giải thích:** <!-- TODO -->

</details>

### Câu 639
Nguồn PDF: trang 87

mAP (mean Average Precision) được tính như thế nào?

- A. Trung bình Accuracy qua các classes
- B. Trung bình AP qua các classes; AP = area under Precision-Recall curve
- C. Maximum precision đạt được
- D. Trung bình IoU

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Trung bình AP qua các classes; AP = area under Precision-Recall curve

**Giải thích:** <!-- TODO -->

</details>

### Câu 640
Nguồn PDF: trang 87

Selective Search tạo ra bao nhiêu region proposals xấp xỉ?

- A. 100
- B. 2000
- C. 10000
- D. 100

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. 2000

**Giải thích:** <!-- TODO -->

</details>

### Câu 641
Nguồn PDF: trang 87

Two-stage detectors (R-CNN family) có đặc điểm gì so với one- stage?

- A. Nhanh hơn
- B. Chính xác hơn nhưng chậm hơn; có separate proposal và classification stages
- C. Kém chính xác hơn
- D. Không có sự khác biệt

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Chính xác hơn nhưng chậm hơn; có separate proposal và classification stages

**Giải thích:** <!-- TODO -->

</details>

### Câu 642
Nguồn PDF: trang 87

Feature Pyramid Network (FPN) dùng để làm gì?

- A. Tăng tốc training
- B. Tạo multi-scale feature maps với skip connections để detect objects ở mọi scale
- C. Thay thế RPN
- D. Giảm số parameters

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Tạo multi-scale feature maps với skip connections để detect objects ở mọi scale

**Giải thích:** <!-- TODO -->

</details>

### Câu 643
Nguồn PDF: trang 87

DETR (Detection Transformer) khác các phương pháp trước ở điểm gì?

- A. Dùng anchor boxes nhiều hơn
- B. Dùng Transformer architecture và bipartite matching loss; không cần anchor boxes hay NMS
- C. Chỉ dùng CNN
- D. Chậm hơn nhiều

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Dùng Transformer architecture và bipartite matching loss; không cần anchor boxes hay NMS

**Giải thích:** <!-- TODO -->

</details>

### Câu 644
Nguồn PDF: trang 87

Localization trong object detection là gì?

- A. Phân loại đối tượng
- B. Xác định vị trí (bounding box) của đối tượng trong ảnh
- C. Phân vùng đối tượng
- D. Theo dõi đối tượng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Xác định vị trí (bounding box) của đối tượng trong ảnh

**Giải thích:** <!-- TODO -->

</details>

### Câu 645
Nguồn PDF: trang 87

Bài toán Single Object Localization kết hợp hai loss gì?

- A. Cross-entropy + MSE
- B. Softmax loss (classification) + L2/smooth-L1 loss (bbox regression)
- C. Binary cross-entropy + IoU loss
- D. Hinge loss + MSE

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Softmax loss (classification) + L2/smooth-L1 loss (bbox regression)

**Giải thích:** <!-- TODO -->

</details>

### Câu 646
Nguồn PDF: trang 88

Sliding window approach trong object detection có nhược điểm gì?

- A. Ít proposals
- B. Rất chậm vì phải chạy CNN tại rất nhiều vị trí, scales, và aspect ratios
- C. Kém chính xác
- D. Chỉ dùng cho 1 class

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Rất chậm vì phải chạy CNN tại rất nhiều vị trí, scales, và aspect ratios

**Giải thích:** <!-- TODO -->

</details>

### Câu 647
Nguồn PDF: trang 88

Điều nào đúng về Soft-NMS so với standard NMS?

- A. Loại bỏ hoàn toàn overlapping boxes
- B. Giảm confidence score của overlapping boxes thay vì loại bỏ hoàn toàn → ít miss adjacent objects
- C. Nhanh hơn NMS
- D. Không cần IoU threshold

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Giảm confidence score của overlapping boxes thay vì loại bỏ hoàn toàn → ít miss adjacent objects

**Giải thích:** <!-- TODO -->

</details>

### Câu 648
Nguồn PDF: trang 88

Điều nào đúng về yêu cầu dữ liệu cho training object detection?

- A. Không cần labeled data
- B. Cần ground truth bounding boxes và class labels cho từng đối tượng trong ảnh
- C. Chỉ cần image-level labels
- D. Chỉ cần 10 ảnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Cần ground truth bounding boxes và class labels cho từng đối tượng trong ảnh

**Giải thích:** <!-- TODO -->

</details>

### Câu 649
Nguồn PDF: trang 88

COCO dataset được dùng để benchmark gì?

- A. Chỉ image classification
- B. Object detection, instance segmentation, keypoint detection, và image captioning
- C. Chỉ segmentation
- D. Chỉ tracking

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Object detection, instance segmentation, keypoint detection, và image captioning

**Giải thích:** <!-- TODO -->

</details>

### Câu 650
Nguồn PDF: trang 88

Điều nào đúng về Focal Loss trong RetinaNet?

- A. Chỉ xử lý easy examples
- B. Down-weight easy negatives, focus training on hard examples → giải quyết class imbalance
- C. Thay thế softmax
- D. Dùng cho regression

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Down-weight easy negatives, focus training on hard examples → giải quyết class imbalance

**Giải thích:** <!-- TODO -->

</details>

### Câu 651
Nguồn PDF: trang 88

Điều nào đúng về FCN (Fully Convolutional Network) trong segmentation?

- A. Dùng fully connected layers ở cuối
- B. Thay FC layers bằng conv layers → cho dense predictions (semantic map) cùng kích thước ảnh
- C. Chỉ cho binary segmentation
- D. Không dùng pooling

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Thay FC layers bằng conv layers → cho dense predictions (semantic map) cùng kích thước ảnh

**Giải thích:** <!-- TODO -->

</details>

### Câu 652
Nguồn PDF: trang 88

U-Net có đặc điểm nào? (Chọn tất cả đúng)

- A. Encoder-decoder architecture
- B. Skip connections từ encoder sang decoder
- C. Phổ biến trong medical image segmentation
- D. Symmetric structure

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Encoder-decoder architecture; B. Skip connections từ encoder sang decoder; C. Phổ biến trong medical image segmentation; D. Symmetric structure

**Giải thích:** <!-- TODO -->

</details>

### Câu 653
Nguồn PDF: trang 89

Transpose Convolution (Deconvolution) dùng để làm gì?

- A. Giảm kích thước feature map
- B. Tăng kích thước feature map (learnable upsampling)
- C. Extract features
- D. Normalize activations

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Tăng kích thước feature map (learnable upsampling)

**Giải thích:** <!-- TODO -->

</details>

### Câu 654
Nguồn PDF: trang 89

Max Unpooling trong decoder hoạt động như thế nào?

- A. Lấy giá trị max trong cửa sổ
- B. Dùng switch variables (vị trí max lưu từ max pooling) để đặt values lại đúng vị trí khi upsampling
- C. Linear interpolation
- D. Nearest neighbor upsampling

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Dùng switch variables (vị trí max lưu từ max pooling) để đặt values lại đúng vị trí khi upsampling

**Giải thích:** <!-- TODO -->

</details>

### Câu 655
Nguồn PDF: trang 89

Nearest Neighbor Upsampling đặt giá trị như thế nào?

- A. Nội suy tuyến tính
- B. Copy giá trị của pixel đến các vị trí lân cận không có giá trị
- C. Tính trung bình lân cận
- D. Dùng learnable weights

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Copy giá trị của pixel đến các vị trí lân cận không có giá trị

**Giải thích:** <!-- TODO -->

</details>

### Câu 656
Nguồn PDF: trang 89

Bilinear interpolation upsampling tính giá trị mới như thế nào?

- A. Chỉ dùng 1 pixel lân cận
- B. Nội suy tuyến tính từ 4 pixel lân cận
- C. Lấy max của 4 lân cận
- D. Lấy min của 4 lân cận

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Nội suy tuyến tính từ 4 pixel lân cận

**Giải thích:** <!-- TODO -->

</details>

### Câu 657
Nguồn PDF: trang 89

Mask R-CNN = Faster R-CNN + thêm gì?

- A. Keypoint head
- B. Mask head (per-RoI binary mask prediction) cho instance segmentation
- C. Caption head
- D. Depth head

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Mask head (per-RoI binary mask prediction) cho instance segmentation

**Giải thích:** <!-- TODO -->

</details>

### Câu 658
Nguồn PDF: trang 89

Panoptic segmentation kết hợp gì?

- A. Detection + Classification
- B. Semantic segmentation (stuff classes) + Instance segmentation (thing classes)
- C. Tracking + Segmentation
- D. Classification + Regression

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Semantic segmentation (stuff classes) + Instance segmentation (thing classes)

**Giải thích:** <!-- TODO -->

</details>

### Câu 659
Nguồn PDF: trang 89

DeepLab dùng kỹ thuật nào để tăng receptive field không giảm resolution?

- A. Max pooling
- B. Atrous (dilated) convolution với rate > 1
- C. Stride = 2
- D. Global average pooling

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Atrous (dilated) convolution với rate > 1

**Giải thích:** <!-- TODO -->

</details>

### Câu 660
Nguồn PDF: trang 89

Semantic segmentation vs Instance segmentation khác nhau thế nào?

- A. Không khác
- B. Semantic gán class cho mỗi pixel; Instance thêm phân biệt giữa các cá thể cùng class
- C. Instance là subset của semantic
- D. Semantic nhanh hơn

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Semantic gán class cho mỗi pixel; Instance thêm phân biệt giữa các cá thể cùng class

**Giải thích:** <!-- TODO -->

</details>

### Câu 661
Nguồn PDF: trang 90

"Bed of nails" upsampling đặt giá trị như thế nào?

- A. Copy giá trị cho tất cả vị trí mới
- B. Đặt giá trị vào 1 vị trí (góc trên trái), các vị trí còn lại = 0
- C. Nội suy tuyến tính
- D. Dùng switch variables

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Đặt giá trị vào 1 vị trí (góc trên trái), các vị trí còn lại = 0

**Giải thích:** <!-- TODO -->

</details>

### Câu 662
Nguồn PDF: trang 90

Điều nào đúng về Encoder trong semantic segmentation architecture?

- A. Tăng resolution qua các layers
- B. Giảm spatial resolution (downsampling) và tăng channels → học high- level features
- C. Chỉ dùng fully connected layers
- D. Không có pooling

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Giảm spatial resolution (downsampling) và tăng channels → học high- level features

**Giải thích:** <!-- TODO -->

</details>

### Câu 663
Nguồn PDF: trang 90

Điều nào đúng về Decoder trong segmentation?

- A. Giảm resolution
- B. Tăng resolution (upsampling) về kích thước ảnh gốc, refine spatial details
- C. Chỉ classify
- D. Không có conv layers

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Tăng resolution (upsampling) về kích thước ảnh gốc, refine spatial details

**Giải thích:** <!-- TODO -->

</details>

### Câu 664
Nguồn PDF: trang 90

DeepLabv3+ kết hợp gì?

- A. Chỉ atrous conv
- B. Atrous Spatial Pyramid Pooling (ASPP) + encoder-decoder với skip connections
- C. Chỉ U-Net
- D. Chỉ FCN

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Atrous Spatial Pyramid Pooling (ASPP) + encoder-decoder với skip connections

**Giải thích:** <!-- TODO -->

</details>

### Câu 665
Nguồn PDF: trang 90

ASPP (Atrous Spatial Pyramid Pooling) dùng để làm gì?

- A. Giảm params
- B. Capture multi-scale context bằng cách áp dụng atrous conv với nhiều dilation rates song song
- C. Upsampling
- D. Classification

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Capture multi-scale context bằng cách áp dụng atrous conv với nhiều dilation rates song song

**Giải thích:** <!-- TODO -->

</details>

### Câu 666
Nguồn PDF: trang 90

Pixel Accuracy trong semantic segmentation được tính thế nào?

- A. TP / (TP + FP)
- B. Số pixel được phân loại đúng / Tổng số pixel
- C. Trung bình IoU
- D. F1-score

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Số pixel được phân loại đúng / Tổng số pixel

**Giải thích:** <!-- TODO -->

</details>

### Câu 667
Nguồn PDF: trang 90

Điều nào đúng về skip connections trong U-Net?

- A. Kết nối layers không liên tiếp trong encoder
- B. Kết nối encoder layer tương ứng với decoder layer → preserve spatial details
- C. Chỉ dùng trong ResNet
- D. Làm chậm inference

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Kết nối encoder layer tương ứng với decoder layer → preserve spatial details

**Giải thích:** <!-- TODO -->

</details>

### Câu 668
Nguồn PDF: trang 91

Instance segmentation output cho mỗi detected object là gì?

- A. Chỉ bounding box
- B. Bounding box + class label + binary mask cho từng instance
- C. Chỉ class label
- D. Depth map

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Bounding box + class label + binary mask cho từng instance

**Giải thích:** <!-- TODO -->

</details>

### Câu 669
Nguồn PDF: trang 91

Điều nào đúng về Cityscapes dataset?

- A. Dataset classification ảnh
- B. Dataset benchmark cho semantic segmentation trong urban scenes
- C. Dataset chỉ cho detection
- D. Dataset âm thanh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Dataset benchmark cho semantic segmentation trong urban scenes

**Giải thích:** <!-- TODO -->

</details>

### Câu 670
Nguồn PDF: trang 91

CondConv (Conditionally Parameterized Convolution) là gì?

- A. Standard convolution
- B. Kết hợp nhiều expert kernels theo input-dependent weights → conditional computation
- C. Chỉ dùng 1 kernel
- D. Không có gì đặc biệt

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Kết hợp nhiều expert kernels theo input-dependent weights → conditional computation

**Giải thích:** <!-- TODO -->

</details>

### Câu 671
Nguồn PDF: trang 91

Điều nào đúng về ViT (Vision Transformer)?

- A. Dùng convolution là chính
- B. Chia ảnh thành patches, flatten thành tokens, xử lý bằng Transformer encoder
- C. Chỉ dùng cho NLP
- D. Không cần pre-training

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Chia ảnh thành patches, flatten thành tokens, xử lý bằng Transformer encoder

**Giải thích:** <!-- TODO -->

</details>

### Câu 672
Nguồn PDF: trang 91

Điều nào đúng về self-supervised learning trong CV?

- A. Cần nhiều labeled data
- B. Học visual representations từ unlabeled data bằng pretext tasks
- C. Kém hơn supervised
- D. Chỉ dùng trong NLP

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Học visual representations từ unlabeled data bằng pretext tasks

**Giải thích:** <!-- TODO -->

</details>

### Câu 673
Nguồn PDF: trang 91

Contrastive Learning (SimCLR, MoCo) học gì?

- A. Supervised classification
- B. Representations sao cho augmented views của cùng image similar, views của images khác nhau dissimilar
- C. Chỉ detection features
- D. Caption generation

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Representations sao cho augmented views của cùng image similar, views của images khác nhau dissimilar

**Giải thích:** <!-- TODO -->

</details>

### Câu 674
Nguồn PDF: trang 91

Điều nào đúng về Grad-CAM?

- A. Tăng accuracy của model
- B. Visualization: dùng gradients để tạo coarse localization map cho vùng model "nhìn vào" khi phân loại
- C. Regularization method
- D. Data augmentation

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Visualization: dùng gradients để tạo coarse localization map cho vùng model "nhìn vào" khi phân loại

**Giải thích:** <!-- TODO -->

</details>

### Câu 675
Nguồn PDF: trang 91

Điều nào đúng về Weakly Supervised Object Detection?

- A. Cần full bounding box annotations
- B. Chỉ cần image-level labels, không cần bounding box → học localization
- C. Không thể detect objects
- D. Chỉ cho segmentation

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Chỉ cần image-level labels, không cần bounding box → học localization

**Giải thích:** <!-- TODO -->

</details>

### Câu 676
Nguồn PDF: trang 92

Điều nào đúng về Knowledge Distillation trong CV?

- A. Transfer learning thông thường
- B. Train small student model để mimick predictions của large teacher model
- C. Data augmentation
- D. Self-supervised learning

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Train small student model để mimick predictions của large teacher model

**Giải thích:** <!-- TODO -->

</details>

### Câu 677
Nguồn PDF: trang 92

Neural Architecture Search (NAS) dùng để làm gì?

- A. Train model nhanh hơn
- B. Automatically search for optimal neural network architecture
- C. Augment data
- D. Prune network

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Automatically search for optimal neural network architecture

**Giải thích:** <!-- TODO -->

</details>

### Câu 678
Nguồn PDF: trang 92

Điều nào đúng về keypoint detection trong human pose estimation?

- A. Detect bounding box của người
- B. Localize anatomical keypoints (joints) như vai, khuỷu, cổ tay
- C. Segment người khỏi nền
- D. Track người qua frames

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Localize anatomical keypoints (joints) như vai, khuỷu, cổ tay

**Giải thích:** <!-- TODO -->

</details>

### Câu 679
Nguồn PDF: trang 92

YOLOv8 so với YOLOv1 có những cải tiến gì?

- A. Ít layers hơn
- B. Anchor-free, decoupled head, improved backbone, mosaic augmentation
- C. Chậm hơn
- D. Kém chính xác hơn

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Anchor-free, decoupled head, improved backbone, mosaic augmentation

**Giải thích:** <!-- TODO -->

</details>

### Câu 680
Nguồn PDF: trang 92

Điều nào đúng về CLIP (Contrastive Language-Image Pre- training)?

- A. Chỉ học visual features
- B. Học joint embedding của text và images cho zero-shot classification
- C. Chỉ học text features
- D. Cần fine-tuning cho mọi task

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Học joint embedding của text và images cho zero-shot classification

**Giải thích:** <!-- TODO -->

</details>

### Câu 681
Nguồn PDF: trang 92

FCN (Long, Shelhamer, Darrell) xuất hiện năm nào và ở đâu?

- A. ICCV 2013
- B. CVPR 2015
- C. NeurIPS 2014
- D. ECCV 2016

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. CVPR 2015

**Giải thích:** <!-- TODO -->

</details>

### Câu 682
Nguồn PDF: trang 92

Trong FCN, các conv layers cuối (fully convolutional) tạo ra output có kích thước gì?

- A. 1×1 (vector)
- B. H×W (spatial map, cùng hoặc nhỏ hơn input) với C channels (classes)
- C. N×1 (vector theo batch)
- D. 3×3

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. H×W (spatial map, cùng hoặc nhỏ hơn input) với C channels (classes)

**Giải thích:** <!-- TODO -->

</details>

### Câu 683
Nguồn PDF: trang 92

Điều nào đúng về stride trong convolution ảnh hưởng đến segmentation?

- A. Stride lớn hơn cho resolution cao hơn
- B. Stride lớn → giảm resolution → mất spatial detail → cần upsampling cho dense prediction
- C. Stride không ảnh hưởng
- D. Stride nhỏ cho kết quả kém hơn

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Stride lớn → giảm resolution → mất spatial detail → cần upsampling cho dense prediction

**Giải thích:** <!-- TODO -->

</details>

### Câu 684
Nguồn PDF: trang 93

Điều nào đúng về "Semantic" trong Semantic Segmentation?

- A. Phân vùng pixel ngẫu nhiên
- B. Mỗi pixel được gán nhãn class có ngữ nghĩa (semantic label) như "cat", "road", "sky"
- C. Chỉ phân vùng foreground/background
- D. Phân biệt từng cá thể

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Mỗi pixel được gán nhãn class có ngữ nghĩa (semantic label) như "cat", "road", "sky"

**Giải thích:** <!-- TODO -->

</details>

### Câu 685
Nguồn PDF: trang 93

Điều nào đúng về Object Detection vs Image Classification?

- A. Chúng giống nhau
- B. Classification gán 1 label cho cả ảnh; Detection localize và classify nhiều objects
- C. Detection dễ hơn Classification
- D. Classification cần bounding box

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Classification gán 1 label cho cả ảnh; Detection localize và classify nhiều objects

**Giải thích:** <!-- TODO -->

</details>

### Câu 686
Nguồn PDF: trang 93

"Objectness score" trong RPN là gì?

- A. Confidence phân loại class
- B. Xác suất một anchor box chứa một đối tượng (bất kể class)
- C. IoU với ground truth
- D. Kích thước của object

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Xác suất một anchor box chứa một đối tượng (bất kể class)

**Giải thích:** <!-- TODO -->

</details>

### Câu 687
Nguồn PDF: trang 93

Điều nào đúng về Hard Negative Mining?

- A. Tìm thêm positive samples
- B. Chủ động chọn negative samples khó (high loss) trong training để tăng performance
- C. Loại bỏ outliers
- D. Augment negative examples

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Chủ động chọn negative samples khó (high loss) trong training để tăng performance

**Giải thích:** <!-- TODO -->

</details>

### Câu 688
Nguồn PDF: trang 93

Điều nào đúng về Class Imbalance trong object detection?

- A. Không có imbalance
- B. Rất nhiều negative (background) so với positive (object) anchors → cần sampling strategies
- C. Nhiều positive hơn negative
- D. Luôn cân bằng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Rất nhiều negative (background) so với positive (object) anchors → cần sampling strategies

**Giải thích:** <!-- TODO -->

</details>

### Câu 689
Nguồn PDF: trang 93

Điều nào đúng về mAP@0.5 trong COCO evaluation?

- A. Dùng IoU threshold = 0.5 để xác định TP/FP
- B. Tính AP tại IoU threshold = 0.5 trung bình qua các classes
- C. Chỉ đánh giá small objects
- D. Tính AP tại tất cả IoU thresholds

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Tính AP tại IoU threshold = 0.5 trung bình qua các classes

**Giải thích:** <!-- TODO -->

</details>

### Câu 690
Nguồn PDF: trang 93

Điều nào đúng về mAP@[0.5:0.95] trong COCO?

- A. Chỉ tại IoU=0.5
- B. Average AP tại IoU từ 0.5 đến 0.95 với step 0.05 → đánh giá toàn diện hơn
- C. Chỉ cho large objects
- D. Không phải standard metric

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Average AP tại IoU từ 0.5 đến 0.95 với step 0.05 → đánh giá toàn diện hơn

**Giải thích:** <!-- TODO -->

</details>

### Câu 691
Nguồn PDF: trang 94

Điều nào KHÔNG đúng về R-CNN family so với YOLO?

- A. R-CNN chính xác hơn
- B. R-CNN nhanh hơn để inference
- C. YOLO phù hợp real-time hơn
- D. R-CNN có separate proposal stage

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. R-CNN nhanh hơn để inference

**Giải thích:** <!-- TODO -->

</details>

### Câu 692
Nguồn PDF: trang 94

Điều nào đúng về "Deformable Convolutional Networks"?

- A. Standard grid sampling
- B. Học offset cho grid sampling → adaptive receptive field theo nội dung ảnh
- C. Không thể học
- D. Chỉ dùng cho rotation

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Học offset cho grid sampling → adaptive receptive field theo nội dung ảnh

**Giải thích:** <!-- TODO -->

</details>

### Câu 693
Nguồn PDF: trang 94

Điều nào đúng về RetinaNet?

- A. Two-stage detector
- B. One-stage detector với FPN + Focal Loss → đạt accuracy cao ngang two- stage
- C. Chỉ detect 1 object
- D. Không dùng anchor boxes

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. One-stage detector với FPN + Focal Loss → đạt accuracy cao ngang two- stage

**Giải thích:** <!-- TODO -->

</details>

### Câu 694
Nguồn PDF: trang 94

Điều nào đúng về Point Cloud (đám mây điểm 3D) trong CV?

- A. Không thể xử lý bằng deep learning
- B. PointNet học features trực tiếp từ point cloud; dùng trong 3D object detection
- C. Chỉ dùng trong robot
- D. Giống ảnh 2D

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. PointNet học features trực tiếp từ point cloud; dùng trong 3D object detection

**Giải thích:** <!-- TODO -->

</details>

### Câu 695
Nguồn PDF: trang 94

Điều nào đúng về difference giữa Semantic Segmentation và Scene Understanding?

- A. Chúng giống nhau
- B. Scene Understanding là broader task bao gồm segmentation, depth estimation, object relationships
- C. Scene Understanding chỉ classify toàn ảnh
- D. Semantic Segmentation là superset

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Scene Understanding là broader task bao gồm segmentation, depth estimation, object relationships

**Giải thích:** <!-- TODO -->

</details>

### Câu 696
Nguồn PDF: trang 94

GAN (Generative Adversarial Network) trong CV được dùng để làm gì? (Chọn tất cả đúng)

- A. Image synthesis
- B. Image inpainting
- C. Style transfer
- D. Data augmentation

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Image synthesis; B. Image inpainting; C. Style transfer; D. Data augmentation

**Giải thích:** <!-- TODO -->

</details>

### Câu 697
Nguồn PDF: trang 94

Điều nào đúng về Conditional GAN (cGAN)?

- A. Không thể kiểm soát output
- B. Sinh ảnh dựa trên điều kiện đầu vào (class label, text, sketch)
- C. Chỉ cho binary output
- D. Không cần discriminator

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Sinh ảnh dựa trên điều kiện đầu vào (class label, text, sketch)

**Giải thích:** <!-- TODO -->

</details>

### Câu 698
Nguồn PDF: trang 94

Điều nào đúng về Autoencoder trong CV?

- A. Chỉ dùng cho compression
- B. Học compressed representation; encoder: input → latent code; decoder: latent code → reconstruct
- C. Cần labeled data
- D. Không thể dùng cho segmentation

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Học compressed representation; encoder: input → latent code; decoder: latent code → reconstruct

**Giải thích:** <!-- TODO -->

</details>

### Câu 699
Nguồn PDF: trang 95

Variational Autoencoder (VAE) khác AE ở điểm nào?

- A. Không có encoder
- B. Latent space là distribution (Gaussian) thay vì point; có thể sample để generate new data
- C. Chỉ cho classification
- D. Không có decoder

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Latent space là distribution (Gaussian) thay vì point; có thể sample để generate new data

**Giải thích:** <!-- TODO -->

</details>

### Câu 700
Nguồn PDF: trang 95

Điều nào đúng về Video Object Segmentation (VOS)?

- A. Chỉ segment frame đầu tiên
- B. Propagate segmentation mask qua các frames; cần temporal consistency
- C. Không cần tracking
- D. Giống single-image segmentation

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Propagate segmentation mask qua các frames; cần temporal consistency

**Giải thích:** <!-- TODO -->

</details>

### Câu 701
Nguồn PDF: trang 95

Điều nào đúng về class activation mapping (CAM)?

- A. Tìm thêm classes
- B. Visualize vùng ảnh quan trọng cho classification decision bằng cách dùng GAP + weights
- C. Data augmentation
- D. Regularization

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Visualize vùng ảnh quan trọng cho classification decision bằng cách dùng GAP + weights

**Giải thích:** <!-- TODO -->

</details>

### Câu 702
Nguồn PDF: trang 95

Điều nào đúng về Test-Time Augmentation (TTA)?

- A. Augment training data
- B. Apply augmentations at test time và average predictions → tăng accuracy
- C. Giảm inference time
- D. Không cần trained model

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Apply augmentations at test time và average predictions → tăng accuracy

**Giải thích:** <!-- TODO -->

</details>

### Câu 703
Nguồn PDF: trang 95

Điều nào đúng về model pruning trong deep learning?

- A. Tăng số layers
- B. Loại bỏ redundant weights/filters → model nhỏ hơn, nhanh hơn với ít accuracy loss
- C. Thêm regularization
- D. Tăng training time

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Loại bỏ redundant weights/filters → model nhỏ hơn, nhanh hơn với ít accuracy loss

**Giải thích:** <!-- TODO -->

</details>

### Câu 704
Nguồn PDF: trang 95

Điều nào đúng về Squeeze-and-Excitation (SE) block?

- A. Spatial attention
- B. Channel attention: recalibrate channel feature responses adaptively
- C. Self-attention
- D. Temporal attention

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Channel attention: recalibrate channel feature responses adaptively

**Giải thích:** <!-- TODO -->

</details>

### Câu 705
Nguồn PDF: trang 95

Điều nào đúng về CBAM (Convolutional Block Attention Module)?

- A. Chỉ channel attention
- B. Kết hợp channel attention + spatial attention để refine features
- C. Chỉ spatial attention
- D. Không liên quan đến attention

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Kết hợp channel attention + spatial attention để refine features

**Giải thích:** <!-- TODO -->

</details>

### Câu 706
Nguồn PDF: trang 96

Điều nào đúng về ShuffleNet?

- A. Kiến trúc cho accuracy cao nhất
- B. Dùng channel shuffle và depthwise conv → lightweight cho mobile
- C. Chỉ dùng 1×1 conv
- D. Không thể chạy real-time

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Dùng channel shuffle và depthwise conv → lightweight cho mobile

**Giải thích:** <!-- TODO -->

</details>

### Câu 707
Nguồn PDF: trang 96

Điều nào đúng về onnx (Open Neural Network Exchange)?

- A. Ngôn ngữ lập trình
- B. Định dạng trung gian cho phép chuyển model giữa các framework (PyTorch, TF, etc.)
- C. Dataset format
- D. Hardware accelerator

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Định dạng trung gian cho phép chuyển model giữa các framework (PyTorch, TF, etc.)

**Giải thích:** <!-- TODO -->

</details>

### Câu 708
Nguồn PDF: trang 96

Điều nào đúng về Semi-Supervised Learning trong CV?

- A. Không dùng unlabeled data
- B. Kết hợp labeled và unlabeled data; pseudo-labeling hoặc consistency regularization
- C. Chỉ dùng labeled data
- D. Giống Self-supervised hoàn toàn

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Kết hợp labeled và unlabeled data; pseudo-labeling hoặc consistency regularization

**Giải thích:** <!-- TODO -->

</details>

### Câu 709
Nguồn PDF: trang 96

Điều nào đúng về Few-Shot Learning trong CV?

- A. Cần nhiều labeled data
- B. Học nhận dạng class mới với rất ít examples (1-shot, 5-shot); dùng meta- learning
- C. Chỉ dùng 1 class
- D. Không thể fine-tune

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Học nhận dạng class mới với rất ít examples (1-shot, 5-shot); dùng meta- learning

**Giải thích:** <!-- TODO -->

</details>

### Câu 710
Nguồn PDF: trang 96

Điều nào đúng về Active Learning trong CV?

- A. Model tự động train không cần người
- B. Chọn intelligently những samples có ích nhất để labeling → giảm annotation effort
- C. Không cần human annotation
- D. Luôn kém hơn fully supervised

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Chọn intelligently những samples có ích nhất để labeling → giảm annotation effort

**Giải thích:** <!-- TODO -->

</details>

### Câu 711
Nguồn PDF: trang 96

Điều nào đúng về Domain Adaptation trong CV?

- A. Không có domain shift
- B. Adapt model trained on source domain để hoạt động tốt trên target domain khác phân phối
- C. Chỉ dùng khi datasets giống nhau
- D. Không liên quan đến transfer learning

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Adapt model trained on source domain để hoạt động tốt trên target domain khác phân phối

**Giải thích:** <!-- TODO -->

</details>

### Câu 712
Nguồn PDF: trang 96

Điều nào đúng về Augmented Reality (AR) và CV?

- A. AR không cần CV
- B. AR dùng CV (SLAM, object recognition, pose estimation) để overlay virtual objects lên real world
- C. AR chỉ dùng GPS
- D. CV làm chậm AR

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. AR dùng CV (SLAM, object recognition, pose estimation) để overlay virtual objects lên real world

**Giải thích:** <!-- TODO -->

</details>

### Câu 713
Nguồn PDF: trang 96

Điều nào đúng về 6DoF pose estimation?

- A. Chỉ estimate orientation
- B. Estimate cả 3D position và 3D orientation (6 degrees of freedom) của object
- C. Chỉ estimate position
- D. Chỉ dùng trong robotics

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Estimate cả 3D position và 3D orientation (6 degrees of freedom) của object

**Giải thích:** <!-- TODO -->

</details>

### Câu 714
Nguồn PDF: trang 97

Điều nào đúng về Visual SLAM (Simultaneous Localization and Mapping)?

- A. Chỉ dùng GPS
- B. Đồng thời xây dựng bản đồ môi trường và định vị camera trong bản đồ đó
- C. Không cần camera
- D. Chỉ trong môi trường trong nhà

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Đồng thời xây dựng bản đồ môi trường và định vị camera trong bản đồ đó

**Giải thích:** <!-- TODO -->

</details>

### Câu 715
Nguồn PDF: trang 97

Điều nào đúng về stereo vision (thị giác lập thể)?

- A. Dùng 1 camera
- B. Dùng 2 cameras để ước lượng depth qua disparity
- C. Chỉ hoạt động ban ngày
- D. Không thể tính depth chính xác

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Dùng 2 cameras để ước lượng depth qua disparity

**Giải thích:** <!-- TODO -->

</details>

### Câu 716
Nguồn PDF: trang 97

Disparity trong stereo vision liên quan đến depth như thế nào?

- A. Tỉ lệ thuận
- B. Tỉ lệ nghịch: depth Z = baseline × focal_length / disparity
- C. Không liên quan
- D. Bằng nhau

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Tỉ lệ nghịch: depth Z = baseline × focal_length / disparity

**Giải thích:** <!-- TODO -->

</details>

### Câu 717
Nguồn PDF: trang 97

Điều nào đúng về depth estimation từ monocular camera?

- A. Không thể ước lượng depth
- B. Có thể học depth với supervised (gt depth) hoặc self-supervised (photometric consistency)
- C. Chính xác như stereo
- D. Không cần neural network

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Có thể học depth với supervised (gt depth) hoặc self-supervised (photometric consistency)

**Giải thích:** <!-- TODO -->

</details>

### Câu 718
Nguồn PDF: trang 97

Điều nào đúng về LiDAR so với camera trong autonomous driving?

- A. Camera cho depth trực tiếp
- B. LiDAR cho depth trực tiếp và chính xác; Camera cho texture/color nhưng depth là implicit
- C. Chúng cho kết quả giống nhau
- D. Camera tốt hơn LiDAR trong đêm tối

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. LiDAR cho depth trực tiếp và chính xác; Camera cho texture/color nhưng depth là implicit

**Giải thích:** <!-- TODO -->

</details>

### Câu 719
Nguồn PDF: trang 97

Điều nào đúng về Occupancy Grid Mapping?

- A. Chỉ dùng cho 2D maps
- B. Biểu diễn không gian 3D bằng grid ô voxels, mỗi ô có xác suất occupied/free
- C. Không dùng sensor
- D. Chỉ trong nhà

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Biểu diễn không gian 3D bằng grid ô voxels, mỗi ô có xác suất occupied/free

**Giải thích:** <!-- TODO -->

</details>

### Câu 720
Nguồn PDF: trang 97

Điều nào đúng về bird's-eye view (BEV) trong autonomous driving?

- A. Xem ảnh từ camera side
- B. Transform perspective từ camera view sang overhead (top-down) view để dễ planning
- C. Dùng drone
- D. Không thể từ camera mặt trước

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Transform perspective từ camera view sang overhead (top-down) view để dễ planning

**Giải thích:** <!-- TODO -->

</details>


## CÂU HỎI TỔNG HỢP - LIÊN CHƯƠNG

### Câu 721
Nguồn PDF: trang 98

Pipeline hoàn chỉnh của hệ thống nhận dạng đối tượng là gì?

- A. Chỉ CNN
- B. Thu nhận ảnh → Tiền xử lý → Trích đặc trưng → Phân loại/Detection → Kết quả
- C. Chỉ phân vùng
- D. Chỉ thresholding

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Thu nhận ảnh → Tiền xử lý → Trích đặc trưng → Phân loại/Detection → Kết quả

**Giải thích:** <!-- TODO -->

</details>

### Câu 722
Nguồn PDF: trang 98

Kỹ thuật nào giải quyết bài toán detection trong điều kiện occlusion nặng?

- A. Simple thresholding
- B. Part-based model, anchor boxes với multi-scale features, và robust training với augmentation
- C. Histogram equalization
- D. Gaussian filter

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Part-based model, anchor boxes với multi-scale features, và robust training với augmentation

**Giải thích:** <!-- TODO -->

</details>

### Câu 723
Nguồn PDF: trang 98

Trong CV pipeline thực tế, vấn đề nào thường gặp nhất?

- A. Thiếu RAM
- B. Biến đổi chiếu sáng, viewpoint, scale, và occlusion
- C. Ảnh quá nhỏ
- D. Thiếu GPU

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Biến đổi chiếu sáng, viewpoint, scale, và occlusion

**Giải thích:** <!-- TODO -->

</details>

### Câu 724
Nguồn PDF: trang 98

Điều nào đúng về quan hệ giữa resolution ảnh và accuracy?

- A. Resolution cao luôn tốt hơn
- B. Tùy task: detection small objects cần resolution cao; computation tăng với resolution
- C. Resolution thấp tốt hơn
- D. Không có quan hệ

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Tùy task: detection small objects cần resolution cao; computation tăng với resolution

**Giải thích:** <!-- TODO -->

</details>

### Câu 725
Nguồn PDF: trang 98

Khi nào nên dùng traditional CV thay vì Deep Learning?

- A. Không bao giờ
- B. Khi có ít data, cần interpretability, hoặc task đơn giản đủ để rule- based
- C. Khi có nhiều data
- D. Luôn luôn dùng DL

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Khi có ít data, cần interpretability, hoặc task đơn giản đủ để rule- based

**Giải thích:** <!-- TODO -->

</details>

### Câu 726
Nguồn PDF: trang 98

Điều nào đúng về end-to-end learning?

- A. Cần nhiều hand-crafted features
- B. Học trực tiếp từ raw input đến output mà không cần pipeline phức tạp
- C. Chỉ dùng cho classification
- D. Chậm hơn pipelined approach

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Học trực tiếp từ raw input đến output mà không cần pipeline phức tạp

**Giải thích:** <!-- TODO -->

</details>

### Câu 727
Nguồn PDF: trang 98

Điều nào đúng về ứng dụng CV trong agriculture (nông nghiệp)?

- A. Không có ứng dụng
- B. Phát hiện sâu bệnh, đánh giá mùa màng, autonomous farming robots
- C. Chỉ dùng để chụp ảnh
- D. Chỉ dùng thermal cameras

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Phát hiện sâu bệnh, đánh giá mùa màng, autonomous farming robots

**Giải thích:** <!-- TODO -->

</details>

### Câu 728
Nguồn PDF: trang 99

Điều nào đúng về edge computing trong CV?

- A. Tất cả inference trên cloud
- B. Inference tại device (camera, robot) giảm latency và privacy concerns
- C. Cần nhiều bandwidth
- D. Không thể chạy deep learning

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Inference tại device (camera, robot) giảm latency và privacy concerns

**Giải thích:** <!-- TODO -->

</details>

### Câu 729
Nguồn PDF: trang 99

Điều nào đúng về ethical concerns trong CV?

- A. CV không có vấn đề đạo đức
- B. Privacy (face recognition surveillance), bias trong datasets, deepfakes
- C. Chỉ có technical challenges
- D. Không cần quan tâm

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Privacy (face recognition surveillance), bias trong datasets, deepfakes

**Giải thích:** <!-- TODO -->

</details>

### Câu 730
Nguồn PDF: trang 99

Điều nào đúng về future directions của CV?

- A. CV đã đạt đỉnh
- B. 3D understanding, multi-modal learning, efficient models, và general purpose models
- C. Chỉ cần cải thiện accuracy
- D. Không có hướng mới

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. 3D understanding, multi-modal learning, efficient models, và general purpose models

**Giải thích:** <!-- TODO -->

</details>

### Câu 731
Nguồn PDF: trang 99

Mối quan hệ giữa Image Processing và Computer Vision là gì?

- A. Image Processing bao gồm Computer Vision
- B. Image Processing (xử lý pixel) là nền tảng cho Computer Vision (hiểu ngữ nghĩa)
- C. Chúng hoàn toàn độc lập
- D. Computer Vision bao gồm mọi Image Processing

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Image Processing (xử lý pixel) là nền tảng cho Computer Vision (hiểu ngữ nghĩa)

**Giải thích:** <!-- TODO -->

</details>

### Câu 732
Nguồn PDF: trang 99

Điều nào đúng về evaluation protocol trong CV?

- A. Chỉ dùng training accuracy
- B. Cần train/validation/test split; dùng held-out test set để report performance
- C. Dùng toàn bộ data để train
- D. Không cần test set

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Cần train/validation/test split; dùng held-out test set để report performance

**Giải thích:** <!-- TODO -->

</details>

### Câu 733
Nguồn PDF: trang 99

Điều nào đúng về benchmark comparison trong CV?

- A. Mọi paper đều dùng cùng metric
- B. Quan trọng dùng cùng dataset, split, và metric để fair comparison
- C. Không cần fair comparison
- D. Chỉ cần accuracy

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Quan trọng dùng cùng dataset, split, và metric để fair comparison

**Giải thích:** <!-- TODO -->

</details>

### Câu 734
Nguồn PDF: trang 99

Điều nào đúng về generalization trong deep learning?

- A. Model train tốt luôn generalize tốt
- B. Cần regularization (dropout, BN, weight decay) và diverse training data để generalize
- C. Không thể đánh giá
- D. Chỉ cần nhiều data

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Cần regularization (dropout, BN, weight decay) và diverse training data để generalize

**Giải thích:** <!-- TODO -->

</details>

### Câu 735
Nguồn PDF: trang 99

Điều nào đúng về overfitting trong CNN?

- A. Model perform tốt trên cả train và test
- B. Model perform tốt trên train, kém trên test; cần regularization
- C. Luôn tốt
- D. Chỉ xảy ra với small models

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Model perform tốt trên train, kém trên test; cần regularization

**Giải thích:** <!-- TODO -->

</details>

### Câu 736
Nguồn PDF: trang 100

Điều nào đúng về underfitting trong CNN?

- A. Model perform tốt trên train, kém trên test
- B. Model perform kém trên cả train và test; cần complex model hoặc more training
- C. Không phải vấn đề
- D. Chỉ xảy ra với large datasets

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Model perform kém trên cả train và test; cần complex model hoặc more training

**Giải thích:** <!-- TODO -->

</details>

### Câu 737
Nguồn PDF: trang 100

Kỹ thuật nào giúp giảm inference time của CNN?

- A. Tăng depth
- B. Quantization (int8), pruning, knowledge distillation, architecture optimization
- C. Thêm augmentation
- D. Tăng batch size

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Quantization (int8), pruning, knowledge distillation, architecture optimization

**Giải thích:** <!-- TODO -->

</details>

### Câu 738
Nguồn PDF: trang 100

Điều nào đúng về Cross-Validation trong CV?

- A. Chỉ dùng 1 fold
- B. Chia data thành K folds, rotate train/val; đánh giá robust hơn với limited data
- C. Không cần với deep learning
- D. Tăng training time không đáng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Chia data thành K folds, rotate train/val; đánh giá robust hơn với limited data

**Giải thích:** <!-- TODO -->

</details>

### Câu 739
Nguồn PDF: trang 100

Điều nào đúng về confusion matrix trong classification?

- A. Chỉ hiển thị accuracy
- B. Ma trận N×N hiển thị TP, FP, FN, TN cho mỗi class → phân tích lỗi chi tiết
- C. Chỉ dùng với 2 classes
- D. Không cần với deep learning

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Ma trận N×N hiển thị TP, FP, FN, TN cho mỗi class → phân tích lỗi chi tiết

**Giải thích:** <!-- TODO -->

</details>

### Câu 740
Nguồn PDF: trang 100

Điều nào đúng về online learning trong CV?

- A. Training offline
- B. Model cập nhật liên tục từ data stream mới, không cần retrain toàn bộ
- C. Cần tất cả data trước
- D. Chỉ dùng cho NLP

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Model cập nhật liên tục từ data stream mới, không cần retrain toàn bộ

**Giải thích:** <!-- TODO -->

</details>

### Câu 741
Nguồn PDF: trang 100

Điều nào đúng về Explainable AI (XAI) trong CV?

- A. Không quan trọng
- B. Kỹ thuật giúp hiểu tại sao model đưa ra prediction → tin tưởng và debug
- C. Chỉ cần cho NLP
- D. Làm giảm accuracy

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Kỹ thuật giúp hiểu tại sao model đưa ra prediction → tin tưởng và debug

**Giải thích:** <!-- TODO -->

</details>

### Câu 742
Nguồn PDF: trang 100

Khi nào nên dùng Semantic Segmentation vs Object Detection?

- A. Chúng giống nhau
- B. Segmentation khi cần pixel-level understanding; Detection khi chỉ cần biết vị trí và class
- C. Luôn dùng Segmentation
- D. Luôn dùng Detection

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Segmentation khi cần pixel-level understanding; Detection khi chỉ cần biết vị trí và class

**Giải thích:** <!-- TODO -->

</details>

### Câu 743
Nguồn PDF: trang 101

Điều nào đúng về Image Caption Generation?

- A. Không liên quan đến CV
- B. Kết hợp CNN (visual features) + RNN/Transformer (language) để mô tả ảnh bằng text
- C. Chỉ dùng language model
- D. Chỉ cần 1 word output

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Kết hợp CNN (visual features) + RNN/Transformer (language) để mô tả ảnh bằng text

**Giải thích:** <!-- TODO -->

</details>

### Câu 744
Nguồn PDF: trang 101

Điều nào đúng về Visual Question Answering (VQA)?

- A. Chỉ dùng text
- B. Trả lời câu hỏi về ảnh; cần hiểu cả visual content và ngôn ngữ
- C. Không cần ảnh
- D. Chỉ cho close-ended questions

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Trả lời câu hỏi về ảnh; cần hiểu cả visual content và ngôn ngữ

**Giải thích:** <!-- TODO -->

</details>

### Câu 745
Nguồn PDF: trang 101

Điều nào đúng về multi-modal learning trong CV?

- A. Chỉ dùng 1 modality
- B. Kết hợp nhiều modalities (image, text, audio, 3D) để học better representations
- C. Phức tạp hơn nhưng kém chính xác
- D. Chỉ cho video

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Kết hợp nhiều modalities (image, text, audio, 3D) để học better representations

**Giải thích:** <!-- TODO -->

</details>

### Câu 746
Nguồn PDF: trang 101

Điều nào đúng về Diffusion Models trong CV?

- A. Chỉ loại bỏ nhiễu trong ảnh
- B. Generative model: học reverse diffusion để generate high-quality images; DALL-E 2, Stable Diffusion
- C. Classification model
- D. Chỉ dùng với audio

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Generative model: học reverse diffusion để generate high-quality images; DALL-E 2, Stable Diffusion

**Giải thích:** <!-- TODO -->

</details>

### Câu 747
Nguồn PDF: trang 101

Điều nào đúng về zero-shot learning trong CV?

- A. Cần many examples của target class
- B. Recognize classes not seen during training, dựa trên semantic description
- C. Không thể thực hiện
- D. Chỉ với 2 classes

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Recognize classes not seen during training, dựa trên semantic description

**Giải thích:** <!-- TODO -->

</details>

### Câu 748
Nguồn PDF: trang 101

Điều nào đúng về Foundation Models trong CV?

- A. Nhỏ và task-specific
- B. Large-scale pre-trained models (SAM, CLIP) có thể adapt cho nhiều downstream tasks
- C. Chỉ cho NLP
- D. Không cần fine-tuning

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Large-scale pre-trained models (SAM, CLIP) có thể adapt cho nhiều downstream tasks

**Giải thích:** <!-- TODO -->

</details>

### Câu 749
Nguồn PDF: trang 101

Điều nào đúng về SAM (Segment Anything Model)?

- A. Chỉ segment 1 class
- B. Foundation model cho segmentation; zero-shot với prompt (point, box, text)
- C. Cần fine-tuning
- D. Chỉ cho indoor images

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Foundation model cho segmentation; zero-shot với prompt (point, box, text)

**Giải thích:** <!-- TODO -->

</details>

### Câu 750
Nguồn PDF: trang 101

Điều nào đúng về Transformer attention mechanism trong ViT?

- A. Chỉ local attention
- B. Self-attention cho phép mỗi patch "attend" đến tất cả patches khác → global context
- C. Không thể xử lý ảnh
- D. Chậm hơn CNN trong mọi trường hợp

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Self-attention cho phép mỗi patch "attend" đến tất cả patches khác → global context

**Giải thích:** <!-- TODO -->

</details>

### Câu 751
Nguồn PDF: trang 102

Điều nào đúng về cách SIFT được tích hợp trong BoW pipeline?

- A. SIFT thay thế BoW
- B. SIFT trích local features → vector quantization thành visual words → histogram = BoW representation
- C. BoW không cần features
- D. SIFT chỉ cho detection

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. SIFT trích local features → vector quantization thành visual words → histogram = BoW representation

**Giải thích:** <!-- TODO -->

</details>

### Câu 752
Nguồn PDF: trang 102

Điều nào đúng về Histogram of Optical Flow (HOF)?

- A. Histogram màu của flow
- B. Histogram hướng và độ lớn optical flow → đặc trưng mô tả local motion pattern
- C. Không liên quan đến optical flow
- D. Chỉ tính cho grayscale

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Histogram hướng và độ lớn optical flow → đặc trưng mô tả local motion pattern

**Giải thích:** <!-- TODO -->

</details>

### Câu 753
Nguồn PDF: trang 102

Điều nào đúng về 3D Convolutional Networks (C3D)?

- A. Standard 2D conv
- B. Conv 3D xử lý video clips: kernel có chiều thời gian → learn spatio- temporal features
- C. Chỉ cho ảnh 3D
- D. Không thể train

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Conv 3D xử lý video clips: kernel có chiều thời gian → learn spatio- temporal features

**Giải thích:** <!-- TODO -->

</details>

### Câu 754
Nguồn PDF: trang 102

Điều nào đúng về Non-local means denoising?

- A. Dùng local window chỉ
- B. Exploit self-similarity trong ảnh: weighted average từ patches tương tự trên toàn ảnh
- C. Chỉ cho salt & pepper noise
- D. Là morphological method

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Exploit self-similarity trong ảnh: weighted average từ patches tương tự trên toàn ảnh

**Giải thích:** <!-- TODO -->

</details>

### Câu 755
Nguồn PDF: trang 102

Điều nào đúng về Bilateral Filter?

- A. Chỉ làm mờ theo không gian
- B. Làm trơn theo cả không gian (spatial) và intensity → edge-preserving smooth
- C. Không liên quan đến edges
- D. Giống Gaussian filter

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Làm trơn theo cả không gian (spatial) và intensity → edge-preserving smooth

**Giải thích:** <!-- TODO -->

</details>

### Câu 756
Nguồn PDF: trang 102

Điều nào đúng về Guided Filter?

- A. Không cần guide image
- B. Dùng guidance image để preserve structure trong filtered output; edge- aware filter
- C. Giống bilateral
- D. Chỉ cho color

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Dùng guidance image để preserve structure trong filtered output; edge- aware filter

**Giải thích:** <!-- TODO -->

</details>

### Câu 757
Nguồn PDF: trang 102

Điều nào đúng về CLAHE (Contrast Limited Adaptive Histogram Equalization)?

- A. Global equalization
- B. Adaptive HE trên local tiles với clip limit để tránh amplify noise quá mức
- C. Không giới hạn contrast
- D. Giống standard HE

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Adaptive HE trên local tiles với clip limit để tránh amplify noise quá mức

**Giải thích:** <!-- TODO -->

</details>

### Câu 758
Nguồn PDF: trang 103

Điều nào đúng về Image Registration?

- A. Đăng ký tên ảnh
- B. Align nhiều ảnh của cùng cảnh chụp ở thời điểm, góc độ, hoặc modality khác nhau
- C. Phân vùng ảnh
- D. Nén ảnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Align nhiều ảnh của cùng cảnh chụp ở thời điểm, góc độ, hoặc modality khác nhau

**Giải thích:** <!-- TODO -->

</details>

### Câu 759
Nguồn PDF: trang 103

Điều nào đúng về epipolar geometry?

- A. Liên quan đến circular objects
- B. Geometric relationship giữa 2 cameras: epipolar line constraint giảm matching từ 2D → 1D
- C. Chỉ với parallel cameras
- D. Không liên quan đến stereo

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Geometric relationship giữa 2 cameras: epipolar line constraint giảm matching từ 2D → 1D

**Giải thích:** <!-- TODO -->

</details>

### Câu 760
Nguồn PDF: trang 103

Điều nào đúng về Fundamental Matrix (F matrix)?

- A. 3×3 ma trận identity
- B. Biểu diễn epipolar geometry: xR^T F xL = 0 cho corresponding points
- C. Chỉ cho calibrated cameras
- D. Rank 3

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Biểu diễn epipolar geometry: xR^T F xL = 0 cho corresponding points

**Giải thích:** <!-- TODO -->

</details>

### Câu 761
Nguồn PDF: trang 103

Điều nào đúng về camera calibration?

- A. Không cần thiết
- B. Xác định intrinsic (focal length, principal point, distortion) và extrinsic parameters
- C. Chỉ cần 1 ảnh
- D. Chỉ cho fisheye

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Xác định intrinsic (focal length, principal point, distortion) và extrinsic parameters

**Giải thích:** <!-- TODO -->

</details>

### Câu 762
Nguồn PDF: trang 103

Điều nào đúng về Perspective Projection?

- A. Bảo toàn kích thước đối tượng
- B. Vật thể xa nhỏ hơn gần → lines converge to vanishing points
- C. Bảo toàn song song
- D. Không liên quan đến camera

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Vật thể xa nhỏ hơn gần → lines converge to vanishing points

**Giải thích:** <!-- TODO -->

</details>

### Câu 763
Nguồn PDF: trang 103

Điều nào đúng về Orthographic Projection?

- A. Lines converge
- B. Parallel projection: không có perspective distortion; kích thước không phụ thuộc depth
- C. Giống perspective
- D. Không thể model

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Parallel projection: không có perspective distortion; kích thước không phụ thuộc depth

**Giải thích:** <!-- TODO -->

</details>

### Câu 764
Nguồn PDF: trang 103

Điều nào đúng về lens distortion?

- A. Không ảnh hưởng đến ảnh
- B. Radial distortion (barrel/pincushion) và tangential; cần calibration để undistort
- C. Chỉ với fisheye
- D. Không thể hiệu chỉnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Radial distortion (barrel/pincushion) và tangential; cần calibration để undistort

**Giải thích:** <!-- TODO -->

</details>

### Câu 765
Nguồn PDF: trang 104

Điều nào đúng về phương trình brightness constancy trong optical flow?

- A. I(x+u, y+v, t+1) ≠ I(x, y, t)
- B. I(x+u, y+v, t+1) = I(x, y, t): intensity không đổi khi point di chuyển
- C. Chỉ đúng với static camera
- D. Không thể xảy ra

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. I(x+u, y+v, t+1) = I(x, y, t): intensity không đổi khi point di chuyển

**Giải thích:** <!-- TODO -->

</details>

### Câu 766
Nguồn PDF: trang 104

Điều nào đúng về Photometric Stereo?

- A. Dùng 2 cameras
- B. Dùng 1 camera và nhiều nguồn sáng khác nhau để recover surface normals
- C. Chỉ cho colored objects
- D. Cần depth sensor

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Dùng 1 camera và nhiều nguồn sáng khác nhau để recover surface normals

**Giải thích:** <!-- TODO -->

</details>

### Câu 767
Nguồn PDF: trang 104

Điều nào đúng về Shape from Shading?

- A. Cần multiple images
- B. Recover surface normals và depth từ shading patterns trong 1 ảnh
- C. Không thể làm từ 1 ảnh
- D. Chỉ dùng với rough surfaces

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Recover surface normals và depth từ shading patterns trong 1 ảnh

**Giải thích:** <!-- TODO -->

</details>

### Câu 768
Nguồn PDF: trang 104

Điều nào đúng về Normalized Cross-Correlation (NCC)?

- A. Bị ảnh hưởng bởi brightness và contrast
- B. Bất biến với additive brightness và multiplicative contrast change
- C. Không thể dùng cho color images
- D. Giống SSD

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Bất biến với additive brightness và multiplicative contrast change

**Giải thích:** <!-- TODO -->

</details>

### Câu 769
Nguồn PDF: trang 104

Điều nào đúng về joint bilateral filter?

- A. Dùng intensity của ảnh lọc làm guide
- B. Dùng một ảnh khác (higher resolution hoặc color) làm guidance image
- C. Giống bilateral
- D. Không edge-preserving

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Dùng một ảnh khác (higher resolution hoặc color) làm guidance image

**Giải thích:** <!-- TODO -->

</details>

### Câu 770
Nguồn PDF: trang 104

Điều nào đúng về Random Forest trong traditional CV?

- A. Chỉ cho regression
- B. Ensemble of decision trees; robust và versatile cho classification, detection, segmentation
- C. Kém hơn SVM
- D. Không thể dùng với visual features

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Ensemble of decision trees; robust và versatile cho classification, detection, segmentation

**Giải thích:** <!-- TODO -->

</details>

### Câu 771
Nguồn PDF: trang 104

Điều nào đúng về SVM (Support Vector Machine) với kernel trick?

- A. Chỉ cho linear separable data
- B. Kernel trick (RBF, polynomial) map data sang higher-dimensional space → nonlinear boundaries
- C. Không cần kernel
- D. Chậm hơn kNN

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Kernel trick (RBF, polynomial) map data sang higher-dimensional space → nonlinear boundaries

**Giải thích:** <!-- TODO -->

</details>

### Câu 772
Nguồn PDF: trang 104

Điều nào đúng về Bag of Words model trong image retrieval?

- A. Dùng full image comparison
- B. Represent image as histogram of visual words; efficient retrieval bằng inverted index
- C. Chỉ cho text
- D. Không cần clustering

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Represent image as histogram of visual words; efficient retrieval bằng inverted index

**Giải thích:** <!-- TODO -->

</details>

### Câu 773
Nguồn PDF: trang 105

Điều nào đúng về vocabulary tree (Nister & Stewenius)?

- A. Flat vocabulary
- B. Hierarchical k-means tạo tree vocabulary; efficient search O(log K) thay vì O(K)
- C. Chỉ 2 levels
- D. Không thể scale lên lớn

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Hierarchical k-means tạo tree vocabulary; efficient search O(log K) thay vì O(K)

**Giải thích:** <!-- TODO -->

</details>

### Câu 774
Nguồn PDF: trang 105

Điều nào đúng về compact descriptors?

- A. Luôn kém chính xác hơn full descriptors
- B. Binary descriptors (BRIEF, ORB, BRISK) ngắn → tìm kiếm nhanh với Hamming distance
- C. Cần nhiều bộ nhớ hơn
- D. Không thể matching

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Binary descriptors (BRIEF, ORB, BRISK) ngắn → tìm kiếm nhanh với Hamming distance

**Giải thích:** <!-- TODO -->

</details>

### Câu 775
Nguồn PDF: trang 105

Điều nào đúng về image retrieval với deep features?

- A. Kém hơn SIFT-based
- B. CNN features (từ pooling layers) tốt cho retrieval; compact với PCA/hashing
- C. Không thể dùng CNN
- D. Chỉ cho exact match

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. CNN features (từ pooling layers) tốt cho retrieval; compact với PCA/hashing

**Giải thích:** <!-- TODO -->

</details>

### Câu 776
Nguồn PDF: trang 105

Điều nào đúng về weakly supervised learning?

- A. Cần pixel-level annotations
- B. Dùng noisy hoặc coarse annotations; image-level labels để học localization
- C. Không thể học
- D. Giống supervised

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Dùng noisy hoặc coarse annotations; image-level labels để học localization

**Giải thích:** <!-- TODO -->

</details>

### Câu 777
Nguồn PDF: trang 105

Điều nào đúng về model ensemble trong CV?

- A. Dùng 1 model tốt nhất
- B. Kết hợp predictions từ nhiều models → giảm variance và tăng accuracy
- C. Làm chậm inference
- D. Không cải thiện accuracy

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Kết hợp predictions từ nhiều models → giảm variance và tăng accuracy

**Giải thích:** <!-- TODO -->

</details>

### Câu 778
Nguồn PDF: trang 105

Điều nào đúng về Hyperparameter tuning trong deep learning?

- A. Hyperparameters tự học
- B. Learning rate, batch size, network architecture cần tuning qua experiments hoặc AutoML
- C. Không quan trọng
- D. Luôn dùng default values

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Learning rate, batch size, network architecture cần tuning qua experiments hoặc AutoML

**Giải thích:** <!-- TODO -->

</details>

### Câu 779
Nguồn PDF: trang 105

Điều nào đúng về Learning Rate Scheduling?

- A. Giữ learning rate cố định
- B. Giảm dần learning rate theo epochs (step decay, cosine annealing) → better convergence
- C. Tăng dần learning rate
- D. Không ảnh hưởng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Giảm dần learning rate theo epochs (step decay, cosine annealing) → better convergence

**Giải thích:** <!-- TODO -->

</details>

### Câu 780
Nguồn PDF: trang 106

Điều nào đúng về Gradient Clipping?

- A. Cắt giảm model size
- B. Giới hạn gradient norm để tránh exploding gradient problem
- C. Tăng gradient
- D. Chỉ dùng với RNN

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Giới hạn gradient norm để tránh exploding gradient problem

**Giải thích:** <!-- TODO -->

</details>

### Câu 781
Nguồn PDF: trang 106

Điều nào đúng về Focal Loss vs Cross-Entropy Loss?

- A. Chúng giống nhau
- B. Focal Loss down-weights easy (well-classified) examples, focuses on hard examples
- C. Focal Loss không phụ thuộc confidence
- D. Cross-Entropy tốt hơn

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Focal Loss down-weights easy (well-classified) examples, focuses on hard examples

**Giải thích:** <!-- TODO -->

</details>

### Câu 782
Nguồn PDF: trang 106

Điều nào đúng về GIoU (Generalized IoU) Loss?

- A. Giống IoU Loss
- B. Khắc phục IoU Loss bằng cách xem xét smallest enclosing box → non-zero gradient khi không overlap
- C. Chỉ cho regression
- D. Không cải thiện so với IoU

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Khắc phục IoU Loss bằng cách xem xét smallest enclosing box → non-zero gradient khi không overlap

**Giải thích:** <!-- TODO -->

</details>

### Câu 783
Nguồn PDF: trang 106

Điều nào đúng về Decoupled Head trong detection?

- A. Kết hợp classification và regression
- B. Tách biệt classification branch và regression branch → mỗi head tối ưu riêng
- C. Chỉ 1 output
- D. Không cải thiện

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Tách biệt classification branch và regression branch → mỗi head tối ưu riêng

**Giải thích:** <!-- TODO -->

</details>

### Câu 784
Nguồn PDF: trang 106

Điều nào đúng về Mosaic Augmentation (YOLOv4)?

- A. 1 ảnh
- B. Ghép 4 ảnh thành 1 → model thấy nhiều contexts, tăng robustness
- C. Chỉ resize
- D. Làm mờ ảnh

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Ghép 4 ảnh thành 1 → model thấy nhiều contexts, tăng robustness

**Giải thích:** <!-- TODO -->

</details>

### Câu 785
Nguồn PDF: trang 106

Điều nào đúng về CutMix Augmentation?

- A. Cắt và bỏ vùng ngẫu nhiên
- B. Cắt patch từ ảnh A và paste vào ảnh B; labels được mix theo tỉ lệ diện tích
- C. Blur vùng ngẫu nhiên
- D. Chỉ resize

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Cắt patch từ ảnh A và paste vào ảnh B; labels được mix theo tỉ lệ diện tích

**Giải thích:** <!-- TODO -->

</details>

### Câu 786
Nguồn PDF: trang 106

Điều nào đúng về Mixup Augmentation?

- A. Mix pixels ngẫu nhiên
- B. Linear interpolation giữa 2 training samples và labels: x̃=λx_i+(1-λ)x_j
- C. Chỉ mix labels
- D. Random erase

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Linear interpolation giữa 2 training samples và labels: x̃=λx_i+(1-λ)x_j

**Giải thích:** <!-- TODO -->

</details>

### Câu 787
Nguồn PDF: trang 106

Điều nào đúng về Label Smoothing?

- A. Tăng confidence của predictions
- B. Thay one-hot labels bằng soft labels (ε/K cho non-target, 1-ε+ε/K cho target) → regularization
- C. Làm tròn labels
- D. Không ảnh hưởng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Thay one-hot labels bằng soft labels (ε/K cho non-target, 1-ε+ε/K cho target) → regularization

**Giải thích:** <!-- TODO -->

</details>

### Câu 788
Nguồn PDF: trang 107

Điều nào đúng về Cosine Annealing learning rate schedule?

- A. Step decay đơn giản
- B. LR giảm theo cosine curve từ max về min, có thể restart
- C. Tăng LR theo thời gian
- D. LR cố định

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. LR giảm theo cosine curve từ max về min, có thể restart

**Giải thích:** <!-- TODO -->

</details>

### Câu 789
Nguồn PDF: trang 107

Điều nào đúng về Layer-wise Adaptive Rate Scaling (LARS)?

- A. Giống SGD
- B. Adaptive LR cho từng layer dựa trên ratio weight norm / gradient norm → phù hợp large batch
- C. Không thể scale với batch size
- D. Chỉ cho linear layers

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Adaptive LR cho từng layer dựa trên ratio weight norm / gradient norm → phù hợp large batch

**Giải thích:** <!-- TODO -->

</details>

### Câu 790
Nguồn PDF: trang 107

Điều nào đúng về Neural Network Quantization?

- A. Tăng precision
- B. Giảm bit-width của weights/activations (float32 → int8) → model nhỏ hơn, nhanh hơn
- C. Tăng model size
- D. Chỉ cho inference

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Giảm bit-width của weights/activations (float32 → int8) → model nhỏ hơn, nhanh hơn

**Giải thích:** <!-- TODO -->

</details>

### Câu 791
Nguồn PDF: trang 107

Điều nào đúng về Vocabulary Bag of Words và TF-IDF?

- A. TF-IDF giảm weight của visual words xuất hiện nhiều
- B. TF-IDF tăng weight của discriminative (distinctive) visual words, giảm weight của common ones
- C. TF-IDF không liên quan đến visual words
- D. TF-IDF không dùng trong image retrieval

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. TF-IDF tăng weight của discriminative (distinctive) visual words, giảm weight của common ones

**Giải thích:** <!-- TODO -->

</details>

### Câu 792
Nguồn PDF: trang 107

Điều nào đúng về kNN (k-Nearest Neighbor) trong image classification?

- A. Cần training phase phức tạp
- B. Không có training (lazy learning); classify dựa trên k neighbors gần nhất trong feature space
- C. Dùng gradient descent
- D. Chỉ cho binary classification

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Không có training (lazy learning); classify dựa trên k neighbors gần nhất trong feature space

**Giải thích:** <!-- TODO -->

</details>

### Câu 793
Nguồn PDF: trang 107

Điều nào đúng về Naive Bayes trong image classification?

- A. Không có assumptions
- B. Giả định feature independence; P(class|features) ∝ P(features|class) × P(class)
- C. Cần deep features
- D. Không thể dùng với visual features

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Giả định feature independence; P(class|features) ∝ P(features|class) × P(class)

**Giải thích:** <!-- TODO -->

</details>

### Câu 794
Nguồn PDF: trang 107

Điều nào đúng về Fisher Vector?

- A. Giống BoW
- B. Encode distribution of local descriptors relative to GMM model; more expressive than BoW
- C. Không dùng GMM
- D. Chỉ dùng 1 Gaussian

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Encode distribution of local descriptors relative to GMM model; more expressive than BoW

**Giải thích:** <!-- TODO -->

</details>

### Câu 795
Nguồn PDF: trang 108

Điều nào đúng về VLAD (Vector of Locally Aggregated Descriptors)?

- A. Giống BoW histogram
- B. Tổng sum của residuals (descriptor - centroid) cho từng visual word → rich representation
- C. Không dùng k-means
- D. Binary representation

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Tổng sum của residuals (descriptor - centroid) cho từng visual word → rich representation

**Giải thích:** <!-- TODO -->

</details>

### Câu 796
Nguồn PDF: trang 108

Điều nào đúng về ứng dụng image retrieval trong thực tế?

- A. Chỉ academic
- B. Google Image Search, Pinterest visual search, e-commerce visual search
- C. Chỉ cho medical images
- D. Không thể scale lên

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Google Image Search, Pinterest visual search, e-commerce visual search

**Giải thích:** <!-- TODO -->

</details>

### Câu 797
Nguồn PDF: trang 108

Điều nào đúng về ANN (Approximate Nearest Neighbor) search?

- A. Tìm exact nearest neighbor
- B. Tìm approximate NN nhanh hơn (FAISS, LSH, HNSW) → scalable với large databases
- C. Kém chính xác hơn và không nhanh hơn
- D. Chỉ dùng với small datasets

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Tìm approximate NN nhanh hơn (FAISS, LSH, HNSW) → scalable với large databases

**Giải thích:** <!-- TODO -->

</details>

### Câu 798
Nguồn PDF: trang 108

Điều nào đúng về Product Quantization (PQ)?

- A. Không compress
- B. Chia descriptor thành sub-vectors, quantize từng sub-vector riêng → compact codes
- C. Chỉ cho 2D data
- D. Không dùng trong retrieval

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Chia descriptor thành sub-vectors, quantize từng sub-vector riêng → compact codes

**Giải thích:** <!-- TODO -->

</details>

### Câu 799
Nguồn PDF: trang 108

Điều nào đúng về attention mechanism trong vision-language models?

- A. Chỉ self-attention
- B. Cross-attention giữa text tokens và image tokens → align visual và linguistic features
- C. Không liên quan đến vision
- D. Chỉ cho translation

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Cross-attention giữa text tokens và image tokens → align visual và linguistic features

**Giải thích:** <!-- TODO -->

</details>

### Câu 800
Nguồn PDF: trang 108

Điều nào đúng về Segment Anything Model (SAM)?

- A. Chỉ segment 80 COCO classes
- B. Zero-shot segmentation với prompts (points, boxes, masks); trained on SA-1B với 1B masks
- C. Cần fine-tuning
- D. Chỉ cho indoor scenes

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Zero-shot segmentation với prompts (points, boxes, masks); trained on SA-1B với 1B masks

**Giải thích:** <!-- TODO -->

</details>

### Câu 801
Nguồn PDF: trang 108

Điều nào đúng về Dense Prediction Tasks?

- A. Chỉ cho classification
- B. Tasks yêu cầu prediction cho mỗi pixel: semantic seg, depth, optical flow, surface normal
- C. Chỉ cho detection
- D. Không cần encoder-decoder

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Tasks yêu cầu prediction cho mỗi pixel: semantic seg, depth, optical flow, surface normal

**Giải thích:** <!-- TODO -->

</details>

### Câu 802
Nguồn PDF: trang 109

Điều nào đúng về image-to-image translation (pix2pix)?

- A. Chỉ resize ảnh
- B. Learn mapping giữa pairs of images (sketch→photo, day→night) using conditional GAN
- C. Không cần paired data
- D. Chỉ cho grayscale

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Learn mapping giữa pairs of images (sketch→photo, day→night) using conditional GAN

**Giải thích:** <!-- TODO -->

</details>

### Câu 803
Nguồn PDF: trang 109

Điều nào đúng về CycleGAN?

- A. Cần paired training data
- B. Unpaired image translation: dùng cycle consistency loss để learn mapping giữa 2 domains
- C. Giống pix2pix
- D. Không thể train

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Unpaired image translation: dùng cycle consistency loss để learn mapping giữa 2 domains

**Giải thích:** <!-- TODO -->

</details>

### Câu 804
Nguồn PDF: trang 109

Điều nào đúng về Super Resolution trong CV?

- A. Giảm resolution
- B. Upscale low-resolution image to high-resolution; SRCNN, SRGAN, ESRGAN
- C. Chỉ làm sắc nét edges
- D. Không cần deep learning

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Upscale low-resolution image to high-resolution; SRCNN, SRGAN, ESRGAN

**Giải thích:** <!-- TODO -->

</details>

### Câu 805
Nguồn PDF: trang 109

Điều nào đúng về Deformable DETR?

- A. Chậm hơn DETR
- B. Cải thiện DETR bằng deformable attention: attend chỉ K sampling points thay vì full spatial
- C. Kém chính xác hơn
- D. Không dùng attention

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Cải thiện DETR bằng deformable attention: attend chỉ K sampling points thay vì full spatial

**Giải thích:** <!-- TODO -->

</details>

### Câu 806
Nguồn PDF: trang 109

Điều nào đúng về Robust PCA (RPCA) trong CV?

- A. Giống PCA
- B. Decompose matrix thành low-rank (background) + sparse (foreground) components
- C. Không thể cho video
- D. Chỉ cho image compression

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Decompose matrix thành low-rank (background) + sparse (foreground) components

**Giải thích:** <!-- TODO -->

</details>

### Câu 807
Nguồn PDF: trang 109

Điều nào đúng về random sample trong RANSAC?

- A. Phải lấy tất cả điểm
- B. Lấy minimum subset ngẫu nhiên (minimal sample set) để ước lượng model
- C. Lấy điểm gần biên
- D. Lấy điểm sáng nhất

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Lấy minimum subset ngẫu nhiên (minimal sample set) để ước lượng model

**Giải thích:** <!-- TODO -->

</details>

### Câu 808
Nguồn PDF: trang 109

Điều nào đúng về Image Segmentation vs Image Parsing?

- A. Chúng giống nhau
- B. Parsing là higher-level: không chỉ segment mà còn label theo semantic hierarchy
- C. Parsing chỉ cho text
- D. Segmentation phức tạp hơn

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Parsing là higher-level: không chỉ segment mà còn label theo semantic hierarchy

**Giải thích:** <!-- TODO -->

</details>

### Câu 809
Nguồn PDF: trang 110

Điều nào đúng về Principal Component Analysis (PCA) và Eigenfaces?

- A. PCA không thể dùng cho faces
- B. PCA giảm chiều face images; eigenvectors (eigenfaces) là principal directions; project face lên subspace
- C. Cần 3D faces
- D. Không thể recognize faces

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. PCA giảm chiều face images; eigenvectors (eigenfaces) là principal directions; project face lên subspace

**Giải thích:** <!-- TODO -->

</details>

### Câu 810
Nguồn PDF: trang 110

Điều nào đúng về histogram intersection distance trong image comparison?

- A. Euclidean distance
- B. D(h1,h2) = Σ min(h1_i, h2_i) → measure overlap between histograms
- C. Chi-squared distance
- D. Cosine similarity

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. D(h1,h2) = Σ min(h1_i, h2_i) → measure overlap between histograms

**Giải thích:** <!-- TODO -->

</details>

### Câu 811
Nguồn PDF: trang 110

Điều nào đúng về Canny detector và optimal filtering theory?

- A. Không có lý thuyết tối ưu
- B. Canny derived optimally: minimize false detections (SNR) và localization error, single response
- C. Chỉ dựa trên thực nghiệm
- D. Kém hơn Sobel về mặt lý thuyết

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Canny derived optimally: minimize false detections (SNR) và localization error, single response

**Giải thích:** <!-- TODO -->

</details>

### Câu 812
Nguồn PDF: trang 110

Điều nào đúng về image processing trong frequency domain?

- A. Luôn tốt hơn spatial
- B. Thuận lợi cho periodicnoise removal, large kernel filtering
- C. Luôn kém hơn spatial
- D. Không thể dùng với ảnh màu

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Thuận lợi cho periodicnoise removal, large kernel filtering

**Giải thích:** <!-- TODO -->

</details>

### Câu 813
Nguồn PDF: trang 110

Điều nào đúng về cross-scale features trong multi-scale detection?

- A. Detect only at 1 scale
- B. Detect small objects ở high-resolution (early) layers, large objects ở low-resolution (later) layers
- C. Không phụ thuộc scale
- D. Chỉ detect large objects

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Detect small objects ở high-resolution (early) layers, large objects ở low-resolution (later) layers

**Giải thích:** <!-- TODO -->

</details>

### Câu 814
Nguồn PDF: trang 110

Điều nào đúng về class activation maps (CAMs) trong weakly supervised detection?

- A. Cần bbox annotations
- B. GAP + FC weights → CAM localizes discriminative region → weak localization không cần bbox
- C. Không thể localize
- D. Cần segmentation mask

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. GAP + FC weights → CAM localizes discriminative region → weak localization không cần bbox

**Giải thích:** <!-- TODO -->

</details>

### Câu 815
Nguồn PDF: trang 110

Điều nào đúng về Mean Average Precision tại multiple IoU thresholds (mAP@0.5:0.95)?

- A. Stricter than mAP@0.5
- B. Yêu cầu localization chính xác hơn → tổng thể đánh giá detection quality tốt hơn
- C. Luôn thấp hơn mAP@0.5
- D. Cả A, B, C

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** D. Cả A, B, C

**Giải thích:** <!-- TODO -->

</details>

### Câu 816
Nguồn PDF: trang 111

Điều nào đúng về scene text detection và recognition?

- A. Chỉ cho printed text
- B. CRAFT, EAST detect text regions; CRNN/TrOCR recognize text; challenge: varied font, angle
- C. Không cần CV
- D. Chỉ cho horizontal text

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. CRAFT, EAST detect text regions; CRNN/TrOCR recognize text; challenge: varied font, angle

**Giải thích:** <!-- TODO -->

</details>

### Câu 817
Nguồn PDF: trang 111

Điều nào đúng về Face Detection vs Face Recognition?

- A. Chúng giống nhau
- B. Detection: locate faces in image; Recognition: identify who the person is
- C. Recognition dễ hơn Detection
- D. Detection cần labeled faces

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Detection: locate faces in image; Recognition: identify who the person is

**Giải thích:** <!-- TODO -->

</details>

### Câu 818
Nguồn PDF: trang 111

Điều nào đúng về Viola-Jones face detector?

- A. Dùng CNN
- B. Dùng Haar-like features với integral image và AdaBoost cascade; real- time
- C. Dùng SIFT
- D. Dùng Hough Transform

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Dùng Haar-like features với integral image và AdaBoost cascade; real- time

**Giải thích:** <!-- TODO -->

</details>

### Câu 819
Nguồn PDF: trang 111

Điều nào đúng về Face Alignment?

- A. Không liên quan đến landmarks
- B. Localize facial landmarks (eyes, nose, mouth corners) để normalize face before recognition
- C. Chỉ cho 2D faces
- D. Không cần trước recognition

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Localize facial landmarks (eyes, nose, mouth corners) để normalize face before recognition

**Giải thích:** <!-- TODO -->

</details>

### Câu 820
Nguồn PDF: trang 111

Điều nào đúng về Metric Learning trong face recognition?

- A. Không cần deep learning
- B. Learn embedding space sao cho same-identity pairs gần nhau, different pairs xa nhau
- C. Chỉ cho classification
- D. Không liên quan đến distance

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Learn embedding space sao cho same-identity pairs gần nhau, different pairs xa nhau

**Giải thích:** <!-- TODO -->

</details>

### Câu 821
Nguồn PDF: trang 111

Triplet Loss trong face recognition tối ưu gì?

- A. Maximize distance giữa anchor và positive
- B. Minimize d(anchor, positive) và maximize d(anchor, negative) với margin
- C. Chỉ maximize negative distance
- D. Không có margin

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Minimize d(anchor, positive) và maximize d(anchor, negative) với margin

**Giải thích:** <!-- TODO -->

</details>

### Câu 822
Nguồn PDF: trang 111

Điều nào đúng về ArcFace loss?

- A. Giống Softmax loss
- B. Additive angular margin penalty → discriminative feature embedding cho face recognition
- C. Không dùng margin
- D. Chỉ cho 2 classes

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Additive angular margin penalty → discriminative feature embedding cho face recognition

**Giải thích:** <!-- TODO -->

</details>

### Câu 823
Nguồn PDF: trang 111

Điều nào đúng về Liveness Detection trong face recognition?

- A. Chỉ check face exists
- B. Anti-spoofing: phân biệt real face vs spoofing attempt (photo, video replay, mask)
- C. Không cần
- D. Luôn 100% accurate

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Anti-spoofing: phân biệt real face vs spoofing attempt (photo, video replay, mask)

**Giải thích:** <!-- TODO -->

</details>

### Câu 824
Nguồn PDF: trang 112

Điều nào đúng về Action Recognition với skeleton data?

- A. Chỉ dùng RGB
- B. GCN (Graph Convolutional Network) xử lý skeleton graph → robust với clothing/background
- C. Cần full body segmentation
- D. Không thể recognize

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. GCN (Graph Convolutional Network) xử lý skeleton graph → robust với clothing/background

**Giải thích:** <!-- TODO -->

</details>

### Câu 825
Nguồn PDF: trang 112

Điều nào đúng về Pedestrian Detection trong autonomous driving?

- A. Chỉ dùng camera
- B. Combine camera (texture/appearance) + LiDAR (3D geometry) → robust all- weather
- C. Không cần GPU
- D. Chỉ trong daylight

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Combine camera (texture/appearance) + LiDAR (3D geometry) → robust all- weather

**Giải thích:** <!-- TODO -->

</details>

### Câu 826
Nguồn PDF: trang 112

Điều nào đúng về Lane Detection challenges?

- A. Luôn có clear lane markings
- B. Faded markings, shadows, occlusion, bad weather, intersections không có markings
- C. Chỉ straight lanes
- D. Không cần CV

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Faded markings, shadows, occlusion, bad weather, intersections không có markings

**Giải thích:** <!-- TODO -->

</details>

### Câu 827
Nguồn PDF: trang 112

Điều nào đúng về traffic sign detection và recognition?

- A. Chỉ detect
- B. 2-stage: detect sign regions → classify sign type; challenge: varying light, scale, occlusion
- C. Chỉ recognize
- D. Không dùng trong thực tế

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. 2-stage: detect sign regions → classify sign type; challenge: varying light, scale, occlusion

**Giải thích:** <!-- TODO -->

</details>

### Câu 828
Nguồn PDF: trang 112

Điều nào đúng về Cross-Domain Adaptation trong detection?

- A. Source = target domain
- B. Adapt detector trained on synthetic (simulation) data để work on real- world data
- C. Không cần
- D. Chỉ cho classification

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Adapt detector trained on synthetic (simulation) data để work on real- world data

**Giải thích:** <!-- TODO -->

</details>

### Câu 829
Nguồn PDF: trang 112

Điều nào đúng về 3D Object Detection từ point clouds?

- A. Giống 2D detection
- B. Cần xử lý sparse, unordered 3D data; PointNet++, VoxelNet, PointPillars
- C. Không thể từ point cloud
- D. Chỉ dùng ảnh 2D

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Cần xử lý sparse, unordered 3D data; PointNet++, VoxelNet, PointPillars

**Giải thích:** <!-- TODO -->

</details>

### Câu 830
Nguồn PDF: trang 112

Điều nào đúng về Real-time vs Batch inference?

- A. Chúng giống nhau
- B. Real-time: latency < 100ms, phù hợp autonomous driving, robotics; Batch: throughput cao, offline
- C. Real-time luôn tốt hơn
- D. Batch luôn nhanh hơn

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Real-time: latency < 100ms, phù hợp autonomous driving, robotics; Batch: throughput cao, offline

**Giải thích:** <!-- TODO -->

</details>

### Câu 831
Nguồn PDF: trang 113

Điều nào đúng về mixed precision training?

- A. Dùng int8 cho tất cả
- B. Kết hợp float16 (fast) và float32 (precision); giảm memory và tăng tốc không mất accuracy
- C. Chỉ float64
- D. Không thể với CNN

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Kết hợp float16 (fast) và float32 (precision); giảm memory và tăng tốc không mất accuracy

**Giải thích:** <!-- TODO -->

</details>

### Câu 832
Nguồn PDF: trang 113

Điều nào đúng về Model Card và Data Card trong responsible AI?

- A. Không quan trọng
- B. Tài liệu mô tả model capabilities, limitations, intended use; và dataset characteristics, biases
- C. Chỉ cần cho NLP
- D. Legal requirement only

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Tài liệu mô tả model capabilities, limitations, intended use; và dataset characteristics, biases

**Giải thích:** <!-- TODO -->

</details>

### Câu 833
Nguồn PDF: trang 113

Điều nào đúng về Fairness trong CV systems?

- A. Không liên quan đến CV
- B. Đảm bảo model hoạt động tốt đồng đều across demographic groups; kiểm tra bias
- C. Chỉ cần cho NLP
- D. Tự động đạt được với big data

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Đảm bảo model hoạt động tốt đồng đều across demographic groups; kiểm tra bias

**Giải thích:** <!-- TODO -->

</details>

### Câu 834
Nguồn PDF: trang 113

Điều nào đúng về Privacy-Preserving CV?

- A. Không thể bảo vệ privacy với CV
- B. Federated learning, differential privacy, on-device processing để giữ data private
- C. Phải gửi data lên cloud
- D. Không cần thiết

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Federated learning, differential privacy, on-device processing để giữ data private

**Giải thích:** <!-- TODO -->

</details>

### Câu 835
Nguồn PDF: trang 113

Điều nào đúng về lidar point cloud processing trong autonomous driving?

- A. Giống xử lý ảnh 2D
- B. Cần xử lý irregular, sparse 3D data; range image, voxelization, hoặc raw point methods
- C. Không cần deep learning
- D. Chỉ cho indoor

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Cần xử lý irregular, sparse 3D data; range image, voxelization, hoặc raw point methods

**Giải thích:** <!-- TODO -->

</details>

### Câu 836
Nguồn PDF: trang 113

Điều nào đúng về Image Quality Assessment (IQA)?

- A. Chỉ dùng PSNR
- B. No-reference (blind) IQA: BRISQUE, NIQE không cần reference; full- reference: SSIM, PSNR
- C. Không thể đánh giá không có reference
- D. Chỉ perceptual metrics

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. No-reference (blind) IQA: BRISQUE, NIQE không cần reference; full- reference: SSIM, PSNR

**Giải thích:** <!-- TODO -->

</details>

### Câu 837
Nguồn PDF: trang 113

Điều nào đúng về Fréchet Inception Distance (FID) trong generative models?

- A. Đo compression ratio
- B. Đo similarity giữa distribution của real và generated images trong feature space của InceptionNet
- C. Chỉ cho autoencoders
- D. Không dùng real images

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Đo similarity giữa distribution của real và generated images trong feature space của InceptionNet

**Giải thích:** <!-- TODO -->

</details>

### Câu 838
Nguồn PDF: trang 114

Điều nào đúng về image forensics trong CV?

- A. Chỉ detect JPEG compression
- B. Phát hiện image manipulation, deepfakes, splice detection; quan trọng cho misinformation
- C. Không thể detect deepfakes
- D. Chỉ academic

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Phát hiện image manipulation, deepfakes, splice detection; quan trọng cho misinformation

**Giải thích:** <!-- TODO -->

</details>

### Câu 839
Nguồn PDF: trang 114

Điều nào đúng về Adversarial Examples trong CV?

- A. Random noise
- B. Carefully crafted perturbations invisible to humans nhưng fool CV models → security concern
- C. Không thể attack modern models
- D. Chỉ xảy ra với toy models

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Carefully crafted perturbations invisible to humans nhưng fool CV models → security concern

**Giải thích:** <!-- TODO -->

</details>

### Câu 840
Nguồn PDF: trang 114

Điều nào đúng về Adversarial Training?

- A. Không hiệu quả
- B. Train với adversarial examples để tăng model robustness
- C. Giảm accuracy trên clean images
- D. Chỉ cho NLP

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Train với adversarial examples để tăng model robustness

**Giải thích:** <!-- TODO -->

</details>

### Câu 841
Nguồn PDF: trang 114

Điều nào đúng về Siamese Network cho image similarity?

- A. Cần 1 input
- B. 2 branches chia sẻ weights xử lý 2 images; compute similarity từ feature embeddings
- C. Không thể compare images
- D. Cần 4 inputs

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. 2 branches chia sẻ weights xử lý 2 images; compute similarity từ feature embeddings

**Giải thích:** <!-- TODO -->

</details>

### Câu 842
Nguồn PDF: trang 114

Điều nào đúng về Metric Learning vs Classification approach cho image similarity?

- A. Chúng giống nhau
- B. Metric learning tốt hơn cho open-set recognition; classification tốt cho closed-set
- C. Classification luôn tốt hơn
- D. Metric learning chỉ cho faces

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Metric learning tốt hơn cho open-set recognition; classification tốt cho closed-set

**Giải thích:** <!-- TODO -->

</details>

### Câu 843
Nguồn PDF: trang 114

Điều nào đúng về R-CNN và training procedure?

- A. End-to-end training
- B. Multi-stage training: pretrain CNN on ImageNet → fine-tune → train SVM → bbox regression
- C. Không cần ImageNet
- D. Chỉ 1 stage

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Multi-stage training: pretrain CNN on ImageNet → fine-tune → train SVM → bbox regression

**Giải thích:** <!-- TODO -->

</details>

### Câu 844
Nguồn PDF: trang 114

Điều nào đúng về Faster R-CNN training?

- A. Không thể end-to-end
- B. Alternating training hoặc approximate joint training: RPN và detection network share conv
- C. Luôn dùng alternating
- D. Không share features

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Alternating training hoặc approximate joint training: RPN và detection network share conv

**Giải thích:** <!-- TODO -->

</details>

### Câu 845
Nguồn PDF: trang 115

Điều nào đúng về Anchor-Free detection (CenterNet, FCOS)?

- A. Cần anchor boxes
- B. Predict object center, size directly; simpler, no anchor hyperparameters
- C. Kém chính xác hơn anchor-based
- D. Không thể detect small objects

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Predict object center, size directly; simpler, no anchor hyperparameters

**Giải thích:** <!-- TODO -->

</details>

### Câu 846
Nguồn PDF: trang 115

Điều nào đúng về FCOS (Fully Convolutional One-Stage Object Detection)?

- A. Anchor-based
- B. Anchor-free: predict distance từ location đến 4 sides của bbox + centerness score
- C. Two-stage
- D. Không dùng FPN

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Anchor-free: predict distance từ location đến 4 sides của bbox + centerness score

**Giải thích:** <!-- TODO -->

</details>

### Câu 847
Nguồn PDF: trang 115

Điều nào đúng về CenterNet (Objects as Points)?

- A. Dùng anchors
- B. Represent object bởi center point → detect center, regress size và other properties
- C. Two-stage
- D. Cần NMS bắt buộc

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Represent object bởi center point → detect center, regress size và other properties

**Giải thích:** <!-- TODO -->

</details>

### Câu 848
Nguồn PDF: trang 115

Điều nào đúng về knowledge trong deep learning models?

- A. Stored trong parameters duy nhất
- B. Distributed across parameters; different layers học different level features
- C. Không thể extract
- D. Stored externally

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Distributed across parameters; different layers học different level features

**Giải thích:** <!-- TODO -->

</details>

### Câu 849
Nguồn PDF: trang 115

Điều nào đúng về continual learning (lifelong learning)?

- A. Học 1 task và quên
- B. Learn new tasks mà không catastrophically forgetting old tasks
- C. Không thể với deep learning
- D. Cần retrain toàn bộ

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Learn new tasks mà không catastrophically forgetting old tasks

**Giải thích:** <!-- TODO -->

</details>

### Câu 850
Nguồn PDF: trang 115

Điều nào đúng về catastrophic forgetting?

- A. Model nhớ tất cả
- B. Khi train trên task mới, model bị quên task cũ vì weights bị overwritten
- C. Chỉ xảy ra với RNN
- D. Không phải vấn đề thực tế

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Khi train trên task mới, model bị quên task cũ vì weights bị overwritten

**Giải thích:** <!-- TODO -->

</details>

### Câu 851
Nguồn PDF: trang 115

Elastic Weight Consolidation (EWC) giải quyết vấn đề gì?

- A. Overfitting
- B. Catastrophic forgetting: regularize important weights cho task trước khi học task mới
- C. Underfitting
- D. Class imbalance

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Catastrophic forgetting: regularize important weights cho task trước khi học task mới

**Giải thích:** <!-- TODO -->

</details>

### Câu 852
Nguồn PDF: trang 116

Điều nào đúng về Neural Radiance Fields (NeRF)?

- A. Reconstruction từ 1 ảnh
- B. Implicit 3D scene representation: MLP maps (x,y,z,θ,φ) → color+density; novel view synthesis
- C. Chỉ cho indoor scenes
- D. Không thể render new views

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Implicit 3D scene representation: MLP maps (x,y,z,θ,φ) → color+density; novel view synthesis

**Giải thích:** <!-- TODO -->

</details>

### Câu 853
Nguồn PDF: trang 116

Điều nào đúng về Gaussian Splatting?

- A. Dùng implicit representation
- B. Represent scene bằng 3D Gaussian primitives; real-time rendering bằng splatting
- C. Chậm hơn NeRF
- D. Không thể novel view synthesis

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Represent scene bằng 3D Gaussian primitives; real-time rendering bằng splatting

**Giải thích:** <!-- TODO -->

</details>

### Câu 854
Nguồn PDF: trang 116

Điều nào đúng về LangSAM (Language Segment Anything)?

- A. Chỉ segment người
- B. Kết hợp language models với SAM: text prompt → segment bất kỳ object được mô tả bằng text
- C. Cần bounding box
- D. Không zero-shot

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Kết hợp language models với SAM: text prompt → segment bất kỳ object được mô tả bằng text

**Giải thích:** <!-- TODO -->

</details>

### Câu 855
Nguồn PDF: trang 116

Điều nào đúng về Grounding DINO?

- A. Chỉ detect pre-defined classes
- B. Open-set object detection: detect bất kỳ object nào được mô tả bằng text phrase
- C. Cần fine-tuning
- D. Không thể open-vocabulary

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Open-set object detection: detect bất kỳ object nào được mô tả bằng text phrase

**Giải thích:** <!-- TODO -->

</details>

### Câu 856
Nguồn PDF: trang 116

Điều nào đúng về LLaVA (Large Language and Vision Assistant)?

- A. Chỉ cho text
- B. Multi-modal model kết hợp vision encoder (CLIP) với LLM; visual instruction following
- C. Không thể xử lý images
- D. Chỉ cho image captioning

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Multi-modal model kết hợp vision encoder (CLIP) với LLM; visual instruction following

**Giải thích:** <!-- TODO -->

</details>

### Câu 857
Nguồn PDF: trang 116

Điều nào đúng về Depth Completion?

- A. Tạo depth từ màu
- B. Complete sparse depth (từ LiDAR) thành dense depth map dùng guidance từ RGB image
- C. Giảm depth resolution
- D. Không cần camera

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Complete sparse depth (từ LiDAR) thành dense depth map dùng guidance từ RGB image

**Giải thích:** <!-- TODO -->

</details>

### Câu 858
Nguồn PDF: trang 116

Điều nào đúng về 4D perception trong autonomous driving?

- A. Chỉ 2D detection
- B. 3D detection + temporal dimension: track objects qua time, predict motion
- C. Chỉ LiDAR
- D. Không thể

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. 3D detection + temporal dimension: track objects qua time, predict motion

**Giải thích:** <!-- TODO -->

</details>

### Câu 859
Nguồn PDF: trang 116

Điều nào đúng về Occupancy Flow trong AV?

- A. Gas flow
- B. Dense 3D occupancy prediction + flow (velocity) cho mỗi voxel → holistic scene understanding
- C. Chỉ 2D
- D. Không dùng deep learning

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Dense 3D occupancy prediction + flow (velocity) cho mỗi voxel → holistic scene understanding

**Giải thích:** <!-- TODO -->

</details>

### Câu 860
Nguồn PDF: trang 117

Điều nào đúng về end-to-end autonomous driving?

- A. Cần manual rules
- B. Direct mapping từ sensors → actions bằng deep learning; challenge: safety và interpretability
- C. Không thể
- D. Chỉ cho parking

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Direct mapping từ sensors → actions bằng deep learning; challenge: safety và interpretability

**Giải thích:** <!-- TODO -->

</details>

### Câu 861
Nguồn PDF: trang 117

Điều nào đúng về bài toán Object Detection trong điều kiện đêm?

- A. Giống điều kiện ban ngày
- B. Cần infrared/thermal camera hoặc night-specific augmentation; challenging với RGB only
- C. Không thể detect
- D. Chỉ cần brightness adjustment

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Cần infrared/thermal camera hoặc night-specific augmentation; challenging với RGB only

**Giải thích:** <!-- TODO -->

</details>

### Câu 862
Nguồn PDF: trang 117

Điều nào đúng về Feature Alignment trong domain adaptation?

- A. Không cần align
- B. Minimize distribution gap giữa source và target features → discriminator-based hoặc moment matching
- C. Chỉ augmentation
- D. Không hiệu quả

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Minimize distribution gap giữa source và target features → discriminator-based hoặc moment matching

**Giải thích:** <!-- TODO -->

</details>

### Câu 863
Nguồn PDF: trang 117

Điều nào đúng về Semi-supervised Object Detection?

- A. Cần tất cả labeled
- B. Dùng pseudo-labels từ teacher model trên unlabeled data để train student
- C. Không thể
- D. Chỉ cho classification

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Dùng pseudo-labels từ teacher model trên unlabeled data để train student

**Giải thích:** <!-- TODO -->

</details>

### Câu 864
Nguồn PDF: trang 117

Điều nào đúng về DINO (Self-distillation with no labels)?

- A. Supervised
- B. Self-supervised pre-training với teacher-student framework; emergent properties: segmentation
- C. Cần labels
- D. Chỉ cho text

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Self-supervised pre-training với teacher-student framework; emergent properties: segmentation

**Giải thích:** <!-- TODO -->

</details>

### Câu 865
Nguồn PDF: trang 117

Điều nào đúng về MAE (Masked Autoencoder)?

- A. Mask text
- B. Self-supervised: mask 75% patches → reconstruct masked patches → learn rich visual representations
- C. Cần labels
- D. Chỉ cho NLP

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Self-supervised: mask 75% patches → reconstruct masked patches → learn rich visual representations

**Giải thích:** <!-- TODO -->

</details>

### Câu 866
Nguồn PDF: trang 117

Điều nào đúng về BEVFormer trong autonomous driving?

- A. Chỉ dùng front camera
- B. Transform multi-camera features vào BEV representation dùng spatial cross-attention
- C. Dùng LiDAR only
- D. 2D processing only

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Transform multi-camera features vào BEV representation dùng spatial cross-attention

**Giải thích:** <!-- TODO -->

</details>

### Câu 867
Nguồn PDF: trang 118

Điều nào đúng về One-Shot Object Detection?

- A. Cần nhiều examples mỗi class
- B. Detect new class với chỉ 1 support example; dùng metric learning hoặc meta-learning
- C. Không thể
- D. Giống standard detection

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Detect new class với chỉ 1 support example; dùng metric learning hoặc meta-learning

**Giải thích:** <!-- TODO -->

</details>

### Câu 868
Nguồn PDF: trang 118

Điều nào đúng về Instance Segmentation challenges?

- A. Dễ hơn semantic segmentation
- B. Cần distinguish instances của cùng class; challenge: overlapping objects, varying scale
- C. Không cần class
- D. Chỉ 1 instance

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Cần distinguish instances của cùng class; challenge: overlapping objects, varying scale

**Giải thích:** <!-- TODO -->

</details>

### Câu 869
Nguồn PDF: trang 118

Điều nào đúng về SOLQ (Instance Segmentation with Sequence- to-Sequence Learning)?

- A. Dùng CNN only
- B. Unified framework dùng Transformer để jointly detect và segment, query- based
- C. Không dùng Transformer
- D. Chỉ cho detection

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Unified framework dùng Transformer để jointly detect và segment, query- based

**Giải thích:** <!-- TODO -->

</details>

### Câu 870
Nguồn PDF: trang 118

Điều nào đúng về CondInst (Conditional Instance Segmentation)?

- A. Cần RoI Pooling
- B. Generate instance-specific conv weights dynamically để produce mask without RoI operation
- C. Slow inference
- D. Dùng fixed masks

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Generate instance-specific conv weights dynamically để produce mask without RoI operation

**Giải thích:** <!-- TODO -->

</details>

### Câu 871
Nguồn PDF: trang 118

Điều nào đúng về QueryInst?

- A. RoI-based
- B. End-to-end instance segmentation với object queries; dynamic mask heads per query
- C. Không parallel
- D. Chỉ 80 classes

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. End-to-end instance segmentation với object queries; dynamic mask heads per query

**Giải thích:** <!-- TODO -->

</details>

### Câu 872
Nguồn PDF: trang 118

Điều nào đúng về SAM và Foundation Models?

- A. Chỉ cho specific domain
- B. Foundation model được trained ở scale lớn → general capabilities → adapt nhiều tasks
- C. Cần fine-tuning
- D. Không zero-shot

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Foundation model được trained ở scale lớn → general capabilities → adapt nhiều tasks

**Giải thích:** <!-- TODO -->

</details>

### Câu 873
Nguồn PDF: trang 118

Điều nào đúng về bài toán Video Instance Segmentation (VIS)?

- A. Segment từng frame độc lập
- B. Detect, segment, và track instances across video frames simultaneously
- C. Chỉ cần static segmentation
- D. Không cần temporal consistency

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Detect, segment, và track instances across video frames simultaneously

**Giải thích:** <!-- TODO -->

</details>

### Câu 874
Nguồn PDF: trang 119

Điều nào đúng về multi-view 3D reconstruction?

- A. Chỉ cần 1 ảnh
- B. Dùng nhiều ảnh từ góc khác nhau để reconstruct geometry 3D của scene
- C. Không cần camera calibration
- D. Chỉ cho indoor

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Dùng nhiều ảnh từ góc khác nhau để reconstruct geometry 3D của scene

**Giải thích:** <!-- TODO -->

</details>

### Câu 875
Nguồn PDF: trang 119

Điều nào đúng về MVSNet?

- A. Single-view
- B. Learning-based multi-view stereo: cost volume từ features matching → depth estimation
- C. Traditional photogrammetry
- D. Không thể scale

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Learning-based multi-view stereo: cost volume từ features matching → depth estimation

**Giải thích:** <!-- TODO -->

</details>

### Câu 876
Nguồn PDF: trang 119

Điều nào đúng về Differentiable Rendering?

- A. Non-differentiable
- B. Render images từ 3D model theo cách differentiable → learn 3D từ 2D supervision
- C. Chỉ forward pass
- D. Không có gradient

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Render images từ 3D model theo cách differentiable → learn 3D từ 2D supervision

**Giải thích:** <!-- TODO -->

</details>

### Câu 877
Nguồn PDF: trang 119

Điều nào đúng về Transformer vs CNN cho vision tasks?

- A. Transformer luôn tốt hơn
- B. CNN tốt với limited data và translation equivariance; Transformer tốt với large data và global context
- C. CNN luôn tốt hơn
- D. Chúng hoàn toàn giống nhau

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. CNN tốt với limited data và translation equivariance; Transformer tốt với large data và global context

**Giải thích:** <!-- TODO -->

</details>

### Câu 878
Nguồn PDF: trang 119

Điều nào đúng về Swin Transformer?

- A. Full global self-attention
- B. Shifted window attention: hierarchical features, linear complexity với image size
- C. Chỉ cho NLP
- D. No hierarchical features

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Shifted window attention: hierarchical features, linear complexity với image size

**Giải thích:** <!-- TODO -->

</details>

### Câu 879
Nguồn PDF: trang 119

Điều nào đúng về DeiT (Data-efficient Image Transformer)?

- A. Cần JFT-300M
- B. ViT trained efficiently on ImageNet only với distillation từ CNN teacher
- C. Cần multiple datasets
- D. Kém hơn ViT

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. ViT trained efficiently on ImageNet only với distillation từ CNN teacher

**Giải thích:** <!-- TODO -->

</details>

### Câu 880
Nguồn PDF: trang 119

Điều nào đúng về BEiT (BERT Pre-training for Image Transformers)?

- A. Supervised
- B. Self-supervised: mask patches → predict visual tokens (dVAE codes); BERT-style for vision
- C. Cần labels
- D. Chỉ cho classification

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Self-supervised: mask patches → predict visual tokens (dVAE codes); BERT-style for vision

**Giải thích:** <!-- TODO -->

</details>

### Câu 881
Nguồn PDF: trang 119

Điều nào đúng về InternImage?

- A. Standard conv
- B. Large-scale vision foundation model dùng deformable conv operator; SoTA across multiple tasks
- C. Transformer only
- D. Chỉ cho detection

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Large-scale vision foundation model dùng deformable conv operator; SoTA across multiple tasks

**Giải thích:** <!-- TODO -->

</details>

### Câu 882
Nguồn PDF: trang 120

Điều nào đúng về EVA (Exploring the Limits of Masked Visual Representation Learning)?

- A. Supervised only
- B. Large-scale vision model trained với CLIP text-image alignment + masked image modeling
- C. Chỉ masking
- D. Không dùng language supervision

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Large-scale vision model trained với CLIP text-image alignment + masked image modeling

**Giải thích:** <!-- TODO -->

</details>

### Câu 883
Nguồn PDF: trang 120

Điều nào đúng về Florence (Microsoft)?

- A. Task-specific model
- B. Universal foundation model trained on large-scale image-text data cho diverse vision tasks
- C. Không thể generalize
- D. Chỉ cho NLP

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Universal foundation model trained on large-scale image-text data cho diverse vision tasks

**Giải thích:** <!-- TODO -->

</details>

### Câu 884
Nguồn PDF: trang 120

Điều nào đúng về xử lý ảnh nhiễu bằng Deep Learning?

- A. Giống traditional methods
- B. DnCNN, FFDNet, NBNet học directly từ noisy-clean pairs; outperform traditional BM3D
- C. Kém hơn traditional
- D. Không thể train cho denoising

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. DnCNN, FFDNet, NBNet học directly từ noisy-clean pairs; outperform traditional BM3D

**Giải thích:** <!-- TODO -->

</details>

### Câu 885
Nguồn PDF: trang 120

Điều nào đúng về Semi-supervised Semantic Segmentation?

- A. Cần tất cả pixel labeled
- B. Dùng labeled + unlabeled data; consistency regularization, pseudo- labeling
- C. Không thể
- D. Cần bounding boxes

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Dùng labeled + unlabeled data; consistency regularization, pseudo- labeling

**Giải thích:** <!-- TODO -->

</details>

### Câu 886
Nguồn PDF: trang 120

Điều nào đúng về Dataset Annotation cho CV?

- A. Tự động hoàn toàn
- B. Cần human annotators cho high-quality labels; crowdsourcing (Amazon Mechanical Turk) phổ biến
- C. Không cần label
- D. Chỉ 1 người annotate

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Cần human annotators cho high-quality labels; crowdsourcing (Amazon Mechanical Turk) phổ biến

**Giải thích:** <!-- TODO -->

</details>

### Câu 887
Nguồn PDF: trang 120

Điều nào đúng về Class Activation Map (CAM) và Grad-CAM?

- A. Chúng giống nhau
- B. CAM cần GAP và FC; Grad-CAM tổng quát hơn, dùng gradient → không cần thay đổi architecture
- C. Grad-CAM cần GAP
- D. CAM không cần FC

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. CAM cần GAP và FC; Grad-CAM tổng quát hơn, dùng gradient → không cần thay đổi architecture

**Giải thích:** <!-- TODO -->

</details>

### Câu 888
Nguồn PDF: trang 120

Điều nào đúng về Object Detection trong Medical Imaging?

- A. Giống natural images
- B. Challenges: class imbalance (lesions rare), small objects, 3D data (CT/MRI slices)
- C. Dễ hơn natural images
- D. Không cần deep learning

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Challenges: class imbalance (lesions rare), small objects, 3D data (CT/MRI slices)

**Giải thích:** <!-- TODO -->

</details>

### Câu 889
Nguồn PDF: trang 121

Điều nào đúng về Document Understanding trong CV?

- A. Chỉ cần OCR
- B. Kết hợp OCR + layout analysis + semantic understanding; LayoutLM kết hợp text và spatial info
- C. Không liên quan đến CV
- D. Chỉ cho printed documents

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Kết hợp OCR + layout analysis + semantic understanding; LayoutLM kết hợp text và spatial info

**Giải thích:** <!-- TODO -->

</details>

### Câu 890
Nguồn PDF: trang 121

Điều nào đúng về Video Object Detection?

- A. Giống single image detection
- B. Exploit temporal information để cải thiện accuracy; challenges: motion blur, occlusion
- C. Không cần temporal
- D. Chậm hơn không dùng temporal

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Exploit temporal information để cải thiện accuracy; challenges: motion blur, occlusion

**Giải thích:** <!-- TODO -->

</details>

### Câu 891
Nguồn PDF: trang 121

Điều nào đúng về Relation Networks trong few-shot learning?

- A. Dùng metric learning cơ bản
- B. Learn to compare: extract features cho query và support, learn similarity function
- C. Không thể với 1-shot
- D. Cần fine-tuning

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Learn to compare: extract features cho query và support, learn similarity function

**Giải thích:** <!-- TODO -->

</details>

### Câu 892
Nguồn PDF: trang 121

Điều nào đúng về MAML (Model-Agnostic Meta-Learning)?

- A. Chỉ cho specific architecture
- B. Meta-learn initialization sao cho vài gradient steps → good performance on new task
- C. Không cần inner loop
- D. Không thể fast adaptation

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Meta-learn initialization sao cho vài gradient steps → good performance on new task

**Giải thích:** <!-- TODO -->

</details>

### Câu 893
Nguồn PDF: trang 121

Điều nào đúng về Prototypical Networks trong few-shot learning?

- A. Dùng parameters phức tạp
- B. Represent each class bởi prototype (mean) của support features; classify bằng nearest prototype
- C. Cần nhiều examples
- D. Không metric-based

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Represent each class bởi prototype (mean) của support features; classify bằng nearest prototype

**Giải thích:** <!-- TODO -->

</details>

### Câu 894
Nguồn PDF: trang 121

Điều nào đúng về Open Vocabulary Detection?

- A. Chỉ detect pre-defined classes
- B. Detect object được described bởi free-form text; không giới hạn vocabulary
- C. Không thể generalize
- D. Cần fine-tuning

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Detect object được described bởi free-form text; không giới hạn vocabulary

**Giải thích:** <!-- TODO -->

</details>

### Câu 895
Nguồn PDF: trang 121

Điều nào đúng về Image Anomaly Detection?

- A. Detect normal samples
- B. Detect samples khác biệt với normal distribution; dùng trong quality control, medical
- C. Cần labeled anomalies
- D. Chỉ classification

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Detect samples khác biệt với normal distribution; dùng trong quality control, medical

**Giải thích:** <!-- TODO -->

</details>

### Câu 896
Nguồn PDF: trang 122

Computer Vision gắn kết hai yếu tố chính nào?

- A. Hardware và Software
- B. Pixel values và Semantic information
- C. Camera và Display
- D. Input và Output

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Pixel values và Semantic information

**Giải thích:** <!-- TODO -->

</details>

### Câu 897
Nguồn PDF: trang 122

Tại sao Gaussian filter được coi là "natural" smoothing filter?

- A. Vì nó tự nhiên trong tự nhiên
- B. Vì nó mô phỏng cách mắt người (và nhiều hệ thống quang học) tự nhiên làm mờ ảnh
- C. Vì kernel nhỏ nhất
- D. Vì dễ implement nhất

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Vì nó mô phỏng cách mắt người (và nhiều hệ thống quang học) tự nhiên làm mờ ảnh

**Giải thích:** <!-- TODO -->

</details>

### Câu 898
Nguồn PDF: trang 122

Tại sao cần cả Canny detector và Hough Transform trong một pipeline CV thực tế?

- A. Chỉ cần 1 trong 2
- B. Canny tìm edge pixels; Hough fit geometric model (line/circle) vào các edge pixels
- C. Chúng thay thế nhau
- D. Hough chạy trước Canny

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Canny tìm edge pixels; Hough fit geometric model (line/circle) vào các edge pixels

**Giải thích:** <!-- TODO -->

</details>

### Câu 899
Nguồn PDF: trang 122

Điều gì kết nối Low-level, Middle-level, và High-level vision trong pipeline tổng thể?

- A. Không có kết nối
- B. Output của level thấp hơn là input cho level cao hơn; bottom-up và top- down interaction
- C. Chỉ bottom-up
- D. Chỉ top-down

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Output của level thấp hơn là input cho level cao hơn; bottom-up và top- down interaction

**Giải thích:** <!-- TODO -->

</details>

### Câu 900
Nguồn PDF: trang 122

Trong thực tế, hệ thống CV thành công cần những yếu tố nào? (Chọn tất cả đúng)

- A. Dữ liệu đủ lớn và đa dạng
- B. Kiến trúc model phù hợp với task
- C. Training procedure đúng
- D. Evaluation và deployment được thiết kế tốt

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** A. Dữ liệu đủ lớn và đa dạng; B. Kiến trúc model phù hợp với task; C. Training procedure đúng; D. Evaluation và deployment được thiết kế tốt

**Giải thích:** <!-- TODO -->

</details>

### Câu 901
Nguồn PDF: trang 122

Kỹ thuật học sâu (Deep Learning) trong CV có thể coi như phiên bản "learned" của gì trong CV truyền thống?

- A. Histogram
- B. Feature extraction pipeline (từ hand-crafted features như SIFT, HOG sang learned features)
- C. Morphological operations
- D. Thresholding

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Feature extraction pipeline (từ hand-crafted features như SIFT, HOG sang learned features)

**Giải thích:** <!-- TODO -->

</details>

### Câu 902
Nguồn PDF: trang 123

SIFT → BoW → kNN là pipeline cho task nào?

- A. Object detection
- B. Image classification/retrieval truyền thống
- C. Segmentation
- D. Tracking

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Image classification/retrieval truyền thống

**Giải thích:** <!-- TODO -->

</details>

### Câu 903
Nguồn PDF: trang 123

FCN → Decoder → Softmax là pipeline cho task nào?

- A. Object detection
- B. Semantic segmentation
- C. Image classification
- D. Optical flow

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Semantic segmentation

**Giải thích:** <!-- TODO -->

</details>

### Câu 904
Nguồn PDF: trang 123

Camera → Preprocessing → CNN → RPN → RoI Pool → Classify+Regress là pipeline của?

- A. YOLO
- B. Faster R-CNN
- C. FCN
- D. U-Net

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Faster R-CNN

**Giải thích:** <!-- TODO -->

</details>

### Câu 905
Nguồn PDF: trang 123

Trong nghiên cứu CV, điều gì quan trọng nhất để đánh giá một phương pháp mới?

- A. Tốc độ training
- B. Kết quả trên benchmark chuẩn (standard dataset) với fair comparison
- C. Số parameters
- D. Code ngắn

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Kết quả trên benchmark chuẩn (standard dataset) với fair comparison

**Giải thích:** <!-- TODO -->

</details>

### Câu 906
Nguồn PDF: trang 123

Gradient Descent tìm minimum của loss function theo nguyên lý nào?

- A. Tìm global minimum
- B. Iteratively move weights in direction of negative gradient → giảm loss từng bước
- C. Random search
- D. Analytical solution

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Iteratively move weights in direction of negative gradient → giảm loss từng bước

**Giải thích:** <!-- TODO -->

</details>

### Câu 907
Nguồn PDF: trang 123

Tại sao Deep Learning cần nhiều dữ liệu hơn traditional ML?

- A. Vì DL chậm hơn
- B. Vì DL học nhiều parameters hơn từ dữ liệu; cần nhiều examples để generalize
- C. Vì DL dùng nhiều features hơn
- D. Vì DL training dài hơn

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Vì DL học nhiều parameters hơn từ dữ liệu; cần nhiều examples để generalize

**Giải thích:** <!-- TODO -->

</details>

### Câu 908
Nguồn PDF: trang 123

Điều nào tốt nhất mô tả tradeoff giữa model complexity và generalization?

- A. Model phức tạp hơn luôn tốt hơn
- B. Bias-variance tradeoff: model quá đơn giản → underfitting; quá phức tạp → overfitting
- C. Model đơn giản luôn tốt hơn
- D. Không có tradeoff

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Bias-variance tradeoff: model quá đơn giản → underfitting; quá phức tạp → overfitting

**Giải thích:** <!-- TODO -->

</details>

### Câu 909
Nguồn PDF: trang 124

Khi thiếu dữ liệu labeled, chiến lược nào hiệu quả nhất?

- A. Train từ scratch
- B. Transfer learning từ large pre-trained model + fine-tune, kết hợp data augmentation
- C. Giảm model size
- D. Tăng learning rate

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Transfer learning từ large pre-trained model + fine-tune, kết hợp data augmentation

**Giải thích:** <!-- TODO -->

</details>

### Câu 910
Nguồn PDF: trang 124

Phương pháp nào tốt nhất để deploy CV model trên edge devices?

- A. Dùng full-size model
- B. Model compression (quantization, pruning, knowledge distillation) + efficient architecture
- C. Tăng model size
- D. Dùng cloud inference

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Model compression (quantization, pruning, knowledge distillation) + efficient architecture

**Giải thích:** <!-- TODO -->

</details>

### Câu 911
Nguồn PDF: trang 124

Điều nào là xu hướng chính của CV hiện đại?

- A. Quay về traditional methods
- B. Foundation models, self-supervised learning, và multi-modal learning
- C. Chỉ dùng CNNs
- D. Giảm model size

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Foundation models, self-supervised learning, và multi-modal learning

**Giải thích:** <!-- TODO -->

</details>

### Câu 912
Nguồn PDF: trang 124

Tại sao self-supervised learning quan trọng trong CV?

- A. Vì nó nhanh hơn supervised
- B. Vì annotation tốn kém và khó; SSL học từ unlabeled data → scalable với large data
- C. Vì cho kết quả tốt hơn supervised
- D. Vì không cần GPU

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Vì annotation tốn kém và khó; SSL học từ unlabeled data → scalable với large data

**Giải thích:** <!-- TODO -->

</details>

### Câu 913
Nguồn PDF: trang 124

Điều gì là hạn chế lớn nhất của deep learning trong CV hiện tại?

- A. Không đủ accurate
- B. Cần nhiều labeled data, interpretability thấp, robustness issues
- C. Quá nhanh
- D. Quá đơn giản

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Cần nhiều labeled data, interpretability thấp, robustness issues

**Giải thích:** <!-- TODO -->

</details>

### Câu 914
Nguồn PDF: trang 124

Tại sao benchmark evaluation (như ImageNet, COCO) quan trọng trong CV?

- A. Vì chúng tự động chọn best model
- B. Cung cấp standard comparison platform để track progress và compare methods fairly
- C. Vì free
- D. Vì dễ dùng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Cung cấp standard comparison platform để track progress và compare methods fairly

**Giải thích:** <!-- TODO -->

</details>

### Câu 915
Nguồn PDF: trang 124

Điều nào đúng về mối quan hệ giữa CV và AI tổng quát?

- A. Không có quan hệ
- B. CV là component quan trọng của AI; giúp machines "see" và understand visual world
- C. CV = AI
- D. AI không cần CV

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. CV là component quan trọng của AI; giúp machines "see" và understand visual world

**Giải thích:** <!-- TODO -->

</details>

### Câu 916
Nguồn PDF: trang 124

Mục tiêu cuối cùng của Computer Vision là gì?

- A. Xử lý pixel tốt hơn
- B. Đạt được visual intelligence ngang hoặc vượt human, cho phép machines truly understand visual world
- C. Chỉ detect objects
- D. Nén ảnh tốt hơn

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Đạt được visual intelligence ngang hoặc vượt human, cho phép machines truly understand visual world

**Giải thích:** <!-- TODO -->

</details>

### Câu 917
Nguồn PDF: trang 125

Điều nào đúng về ResNet-50 so với ResNet-101?

- A. ResNet-50 sâu hơn
- B. ResNet-101 có nhiều layers hơn (101 vs 50) → thường chính xác hơn nhưng chậm hơn
- C. ResNet-50 chính xác hơn
- D. Chúng giống nhau

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. ResNet-101 có nhiều layers hơn (101 vs 50) → thường chính xác hơn nhưng chậm hơn

**Giải thích:** <!-- TODO -->

</details>

### Câu 918
Nguồn PDF: trang 125

Tại sao cần image pyramid trong SIFT nhưng không cần trong BoW inference?

- A. Không cần pyramid trong SIFT
- B. SIFT cần pyramid để phát hiện keypoints ở các scales; BoW dùng features đã scale-invariant
- C. BoW cần pyramid
- D. Không có sự khác biệt

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. SIFT cần pyramid để phát hiện keypoints ở các scales; BoW dùng features đã scale-invariant

**Giải thích:** <!-- TODO -->

</details>

### Câu 919
Nguồn PDF: trang 125

Điều nào đúng về Otsu thresholding trong điều kiện illumination không đồng đều?

- A. Hoạt động tốt
- B. Otsu thường thất bại; cần local/adaptive thresholding như CLAHE
- C. Cho kết quả tốt nhất
- D. Không cần thay thế

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Otsu thường thất bại; cần local/adaptive thresholding như CLAHE

**Giải thích:** <!-- TODO -->

</details>

### Câu 920
Nguồn PDF: trang 125

Tại sao Watershed thường cần post-processing?

- A. Quá chậm
- B. Over-segmentation nghiêm trọng; cần merge small regions hoặc marker- controlled approach
- C. Kết quả không bao giờ đúng
- D. Tốn quá nhiều bộ nhớ

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Over-segmentation nghiêm trọng; cần merge small regions hoặc marker- controlled approach

**Giải thích:** <!-- TODO -->

</details>

### Câu 921
Nguồn PDF: trang 125

Điều nào đúng về local features vs global features cho image retrieval?

- A. Chỉ dùng global
- B. Local features (SIFT, BoW) tốt cho partial matching và occlusion; global features tốt cho efficiency
- C. Chỉ dùng local
- D. Không có sự khác biệt

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Local features (SIFT, BoW) tốt cho partial matching và occlusion; global features tốt cho efficiency

**Giải thích:** <!-- TODO -->

</details>

### Câu 922
Nguồn PDF: trang 125

Tại sao Lucas-Kanade thất bại với textureless regions?

- A. Vì ma trận ATA singular → không có nghiệm duy nhất
- B. Vì textureless → Ix ≈ 0, Iy ≈ 0 → structure matrix singular → optical flow không xác định
- C. Vì sai giả thiết brightness constancy
- D. Vì tốn quá nhiều bộ nhớ

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Vì textureless → Ix ≈ 0, Iy ≈ 0 → structure matrix singular → optical flow không xác định

**Giải thích:** <!-- TODO -->

</details>

### Câu 923
Nguồn PDF: trang 125

Điều nào đúng về quan hệ giữa Convolution Theorem và xử lý ảnh hiệu quả?

- A. Không có quan hệ
- B. Convolution trong spatial domain = multiplication trong frequency domain → lọc large kernel nhanh hơn
- C. Ngược lại
- D. Chỉ cho 1D

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Convolution trong spatial domain = multiplication trong frequency domain → lọc large kernel nhanh hơn

**Giải thích:** <!-- TODO -->

</details>

### Câu 924
Nguồn PDF: trang 126

Tại sao scale-space trong SIFT dùng Gaussian pyramid?

- A. Gaussian nhanh nhất
- B. Gaussian là đơn là "causally correct" scale-space (Lindeberg): không tạo ra extrema mới khi scale tăng
- C. Vì đơn giản nhất
- D. Không có lý do đặc biệt

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Gaussian là đơn là "causally correct" scale-space (Lindeberg): không tạo ra extrema mới khi scale tăng

**Giải thích:** <!-- TODO -->

</details>

### Câu 925
Nguồn PDF: trang 126

Điều nào đúng về ứng dụng GLCM trong phân loại vải (fabric classification)?

- A. Dùng histogram màu
- B. GLCM features mô tả đặc trưng texture của vải → phân biệt loại vải khác nhau
- C. Chỉ dùng HOG
- D. Không thể

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. GLCM features mô tả đặc trưng texture của vải → phân biệt loại vải khác nhau

**Giải thích:** <!-- TODO -->

</details>

### Câu 926
Nguồn PDF: trang 126

Điều nào đúng về Long, Shelhamer, Darrell CVPR 2015 và đóng góp của nó?

- A. Giới thiệu CNN cho classification
- B. Giới thiệu FCN: first end-to-end training cho dense semantic segmentation với CNN
- C. Giới thiệu SIFT
- D. Giới thiệu R-CNN

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Giới thiệu FCN: first end-to-end training cho dense semantic segmentation với CNN

**Giải thích:** <!-- TODO -->

</details>

### Câu 927
Nguồn PDF: trang 126

Tại sao DeepLab dùng atrous convolution thay vì giảm stride?

- A. Vì nhanh hơn
- B. Giảm stride → pooling → mất resolution; atrous conv tăng receptive field không mất resolution
- C. Vì đơn giản hơn
- D. Vì ít parameters hơn

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Giảm stride → pooling → mất resolution; atrous conv tăng receptive field không mất resolution

**Giải thích:** <!-- TODO -->

</details>

### Câu 928
Nguồn PDF: trang 126

Điều nào đúng về pixel labeling trong semantic segmentation output?

- A. Mỗi pixel có 1 floating point value
- B. Mỗi pixel được gán label class (integer), biểu diễn đối tượng pixel đó thuộc về
- C. Mỗi pixel có RGB value
- D. Mỗi pixel có binary value

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Mỗi pixel được gán label class (integer), biểu diễn đối tượng pixel đó thuộc về

**Giải thích:** <!-- TODO -->

</details>

### Câu 929
Nguồn PDF: trang 126

Tại sao Instance Segmentation khó hơn Semantic Segmentation?

- A. Cần nhiều classes hơn
- B. Cần không chỉ segment per-class mà còn distinguish individual instances của cùng class
- C. Cần ảnh lớn hơn
- D. Cần nhiều GPU hơn

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Cần không chỉ segment per-class mà còn distinguish individual instances của cùng class

**Giải thích:** <!-- TODO -->

</details>

### Câu 930
Nguồn PDF: trang 127

Điều nào đúng về UperNet trong semantic segmentation?

- A. Encoder-only
- B. Unified Perceptual Parsing Network: FPN-based decoder, multi-task segmentation
- C. Chỉ cho instance segmentation
- D. Không dùng FPN

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Unified Perceptual Parsing Network: FPN-based decoder, multi-task segmentation

**Giải thích:** <!-- TODO -->

</details>

### Câu 931
Nguồn PDF: trang 127

Điều nào đúng về ứng dụng optical flow cho video compression?

- A. Không liên quan
- B. Motion estimation/compensation: predict frame từ reference + motion vectors → chỉ encode residual
- C. Làm tăng kích thước
- D. Chỉ cho audio

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Motion estimation/compensation: predict frame từ reference + motion vectors → chỉ encode residual

**Giải thích:** <!-- TODO -->

</details>

### Câu 932
Nguồn PDF: trang 127

Điều nào đúng về SLAM và Computer Vision?

- A. SLAM chỉ dùng IMU
- B. Visual SLAM dùng camera features (ORB, SIFT) để simultaneously localize và build map
- C. Không liên quan
- D. Chỉ cho indoor

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Visual SLAM dùng camera features (ORB, SIFT) để simultaneously localize và build map

**Giải thích:** <!-- TODO -->

</details>

### Câu 933
Nguồn PDF: trang 127

Điều nào đúng về 3D reconstruction từ stereo cameras?

- A. Chỉ cần disparity
- B. Disparity → depth → 3D point cloud; cần camera calibration và stereo matching
- C. Không cần calibration
- D. Chỉ cho binocular cameras

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Disparity → depth → 3D point cloud; cần camera calibration và stereo matching

**Giải thích:** <!-- TODO -->

</details>

### Câu 934
Nguồn PDF: trang 127

Điều nào đúng về nghiên cứu thị giác sinh học (biological vision) ảnh hưởng CV?

- A. Không ảnh hưởng
- B. Hierarchical feature processing (simple→complex cells, Hubel & Wiesel) lấy cảm hứng cho CNN
- C. Chỉ ảnh hưởng đến hardware
- D. Chỉ về màu sắc

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Hierarchical feature processing (simple→complex cells, Hubel & Wiesel) lấy cảm hứng cho CNN

**Giải thích:** <!-- TODO -->

</details>

### Câu 935
Nguồn PDF: trang 127

Điều nào đúng về Convolutional Neural Network và receptive field?

- A. Tất cả neurons có cùng RF
- B. Neurons ở layers sâu hơn có larger RF → capture global context tốt hơn
- C. RF giảm với depth
- D. RF không phụ thuộc depth

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Neurons ở layers sâu hơn có larger RF → capture global context tốt hơn

**Giải thích:** <!-- TODO -->

</details>

### Câu 936
Nguồn PDF: trang 127

Điều nào đúng về ứng dụng CV trong retail (bán lẻ)?

- A. Không có ứng dụng
- B. Inventory management, customer behavior analysis, cashierless checkout (Amazon Go)
- C. Chỉ bảo mật
- D. Chỉ online retail

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Inventory management, customer behavior analysis, cashierless checkout (Amazon Go)

**Giải thích:** <!-- TODO -->

</details>

### Câu 937
Nguồn PDF: trang 127

Điều nào đúng về CV trong sports analytics?

- A. Không liên quan
- B. Player tracking, action recognition, automated highlight generation, performance analysis
- C. Chỉ broadcast
- D. Chỉ cho 1 sport

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Player tracking, action recognition, automated highlight generation, performance analysis

**Giải thích:** <!-- TODO -->

</details>

### Câu 938
Nguồn PDF: trang 128

Điều nào đúng về thách thức của CV trong điều kiện weather phức tạp?

- A. CV không bị ảnh hưởng
- B. Rain, fog, snow làm giảm visibility, alter appearance → cần domain adaptation hoặc robust models
- C. Chỉ ảnh hưởng đến color
- D. Chỉ ảnh hưởng đến night

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Rain, fog, snow làm giảm visibility, alter appearance → cần domain adaptation hoặc robust models

**Giải thích:** <!-- TODO -->

</details>

### Câu 939
Nguồn PDF: trang 128

Điều nào đúng về CV system deployment trong production?

- A. Giống academic experiment
- B. Cần handle edge cases, model monitoring, gradual rollout, A/B testing
- C. Không cần monitoring
- D. Chỉ cần model accuracy

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Cần handle edge cases, model monitoring, gradual rollout, A/B testing

**Giải thích:** <!-- TODO -->

</details>

### Câu 940
Nguồn PDF: trang 128

Điều nào đúng về ảnh hưởng của AlexNet với sự phát triển của deep CV?

- A. Không quan trọng
- B. Đánh dấu sự bùng nổ của deep learning trong CV; chứng minh CNN superiority trên ImageNet 2012
- C. Chỉ cho classification
- D. Chỉ ảnh hưởng academic

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Đánh dấu sự bùng nổ của deep learning trong CV; chứng minh CNN superiority trên ImageNet 2012

**Giải thích:** <!-- TODO -->

</details>

### Câu 941
Nguồn PDF: trang 128

Điều nào đúng về Computer Vision as a Service (CVaaS)?

- A. Không tồn tại
- B. Cloud APIs (Google Vision API, AWS Rekognition, Azure CV) cho phép access CV capabilities dễ dàng
- C. Chỉ cho large enterprises
- D. Không thể dùng cho real-time

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Cloud APIs (Google Vision API, AWS Rekognition, Azure CV) cho phép access CV capabilities dễ dàng

**Giải thích:** <!-- TODO -->

</details>

### Câu 942
Nguồn PDF: trang 128

Điều nào đúng về Green AI trong bối cảnh CV?

- A. Màu sắc xanh
- B. Giảm carbon footprint của training: efficient architectures, model compression, renewable energy
- C. Không liên quan
- D. Chỉ cho NLP

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Giảm carbon footprint của training: efficient architectures, model compression, renewable energy

**Giải thích:** <!-- TODO -->

</details>

### Câu 943
Nguồn PDF: trang 128

Điều nào đúng về Computer Vision trong inspection công nghiệp?

- A. Chỉ cho ảnh màu
- B. Detect defects (scratches, cracks, missing components) trên dây chuyền sản xuất
- C. Cần human verification mọi lúc
- D. Không chính xác

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Detect defects (scratches, cracks, missing components) trên dây chuyền sản xuất

**Giải thích:** <!-- TODO -->

</details>

### Câu 944
Nguồn PDF: trang 128

Điều nào đúng về Embedded Computer Vision?

- A. Cần powerful GPU
- B. Run CV algorithms trên resource-constrained devices (MCU, FPGA, edge AI chips)
- C. Không thể cho real-time
- D. Cần cloud connectivity

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Run CV algorithms trên resource-constrained devices (MCU, FPGA, edge AI chips)

**Giải thích:** <!-- TODO -->

</details>

### Câu 945
Nguồn PDF: trang 129

Điều nào đúng về Computer Vision trong education?

- A. Không có ứng dụng
- B. Engagement monitoring, handwriting recognition, automated grading, AR learning
- C. Chỉ cho online learning
- D. Privacy không phải concern

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Engagement monitoring, handwriting recognition, automated grading, AR learning

**Giải thích:** <!-- TODO -->

</details>

### Câu 946
Nguồn PDF: trang 129

Điều nào đúng về Computer Vision trong entertainment?

- A. Không liên quan
- B. Motion capture cho VFX, deepfake, VR/AR, video game AI, content moderation
- C. Chỉ cho movies
- D. Không cần real-time

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Motion capture cho VFX, deepfake, VR/AR, video game AI, content moderation

**Giải thích:** <!-- TODO -->

</details>

### Câu 947
Nguồn PDF: trang 129

Điều nào đúng về Computer Vision trong environmental monitoring?

- A. Chỉ dùng GPS
- B. Satellite/drone imagery để monitor deforestation, ocean plastic, wildlife tracking
- C. Chỉ cho climate research
- D. Không cần CV

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Satellite/drone imagery để monitor deforestation, ocean plastic, wildlife tracking

**Giải thích:** <!-- TODO -->

</details>

### Câu 948
Nguồn PDF: trang 129

Điều nào đúng về Computer Vision trong construction?

- A. Không có ứng dụng
- B. Safety monitoring (PPE detection), progress tracking, defect inspection, BIM integration
- C. Chỉ cho documentation
- D. Không chính xác

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Safety monitoring (PPE detection), progress tracking, defect inspection, BIM integration

**Giải thích:** <!-- TODO -->

</details>

### Câu 949
Nguồn PDF: trang 129

Điều nào đúng về tương lai của Human-Machine Interaction với CV?

- A. Chỉ keyboard và mouse
- B. Gesture recognition, gaze tracking, emotion recognition → natural và intuitive interaction
- C. Không cần CV
- D. Chỉ voice

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Gesture recognition, gaze tracking, emotion recognition → natural và intuitive interaction

**Giải thích:** <!-- TODO -->

</details>

### Câu 950
Nguồn PDF: trang 129

Điều gì sẽ là thách thức lớn nhất của CV trong thập kỷ tới?

- A. Thiếu computational power
- B. Achieving robust generalization, reducing data hunger, ensuring safety và fairness
- C. Thiếu datasets
- D. Thiếu algorithms

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Achieving robust generalization, reducing data hunger, ensuring safety và fairness

**Giải thích:** <!-- TODO -->

</details>

### Câu 951
Nguồn PDF: trang 130

Điều nào đúng về tính chất kết hợp của convolution trong xây dựng CNN deep layers?

- A. Không có tính kết hợp
- B. I*(h*g) = (I*h)*g → có thể biểu diễn nhiều conv liên tiếp như conv với 1 equivalent filter
- C. Chỉ cho 1D
- D. Chỉ với Gaussian filters

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. I*(h*g) = (I*h)*g → có thể biểu diễn nhiều conv liên tiếp như conv với 1 equivalent filter

**Giải thích:** <!-- TODO -->

</details>

### Câu 952
Nguồn PDF: trang 130

Tại sao Local Binary Pattern (LBP) robust với illumination changes?

- A. Dùng giá trị tuyệt đối
- B. LBP encode relative order (>) của pixel với hàng xóm, không phải absolute values → illumination monotonic changes không ảnh hưởng
- C. Vì normalized
- D. Vì dùng grayscale

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. LBP encode relative order (>) của pixel với hàng xóm, không phải absolute values → illumination monotonic changes không ảnh hưởng

**Giải thích:** <!-- TODO -->

</details>

### Câu 953
Nguồn PDF: trang 130

Trong khung hình thuyết (projective geometry), homogeneous coordinates dùng để làm gì?

- A. Biểu diễn màu sắc
- B. Cho phép biểu diễn thống nhất tất cả projective transformations bằng matrix multiplication; xử lý được points at infinity
- C. Compress ảnh
- D. Tính histogram

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Cho phép biểu diễn thống nhất tất cả projective transformations bằng matrix multiplication; xử lý được points at infinity

**Giải thích:** <!-- TODO -->

</details>

### Câu 954
Nguồn PDF: trang 130

Điều nào đúng về Gram matrix trong Neural Style Transfer?

- A. Biểu diễn content của ảnh
- B. Gram(F) = F^T F; capture feature correlations → biểu diễn style (texture) của ảnh
- C. Tính gradient
- D. Biểu diễn edges

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Gram(F) = F^T F; capture feature correlations → biểu diễn style (texture) của ảnh

**Giải thích:** <!-- TODO -->

</details>

### Câu 955
Nguồn PDF: trang 130

Điều nào đúng về Perceptual Loss trong image generation?

- A. Giống pixel-level MSE
- B. Compute loss trong feature space của pre-trained VGG → perceptually meaningful similarities
- C. Chỉ cho face
- D. Không dùng pre-trained model

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Compute loss trong feature space của pre-trained VGG → perceptually meaningful similarities

**Giải thích:** <!-- TODO -->

</details>

### Câu 956
Nguồn PDF: trang 130

Điều nào đúng về spectral normalization trong GAN discriminator?

- A. Không cần normalization
- B. Normalize weights bằng spectral norm → Lipschitz constraint → training stability
- C. Giống batch norm
- D. Chỉ cho generator

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Normalize weights bằng spectral norm → Lipschitz constraint → training stability

**Giải thích:** <!-- TODO -->

</details>

### Câu 957
Nguồn PDF: trang 130

Điều nào đúng về Wasserstein GAN (WGAN)?

- A. Dùng JS divergence
- B. Dùng Wasserstein distance thay vì JS divergence → stable training và meaningful gradients
- C. Kém ổn định hơn standard GAN
- D. Không thể train

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Dùng Wasserstein distance thay vì JS divergence → stable training và meaningful gradients

**Giải thích:** <!-- TODO -->

</details>

### Câu 958
Nguồn PDF: trang 131

Điều nào đúng về Capsule Networks (Hinton)?

- A. Giống CNN
- B. Neurons encode pose information (position, rotation) của part; routing- by-agreement thay vì pooling
- C. Không có routing
- D. Kém hơn CNN

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Neurons encode pose information (position, rotation) của part; routing- by-agreement thay vì pooling

**Giải thích:** <!-- TODO -->

</details>

### Câu 959
Nguồn PDF: trang 131

Điều nào đúng về attention rollout trong Transformer vision models?

- A. Không thể visualize attention
- B. Combine attention weights qua layers để visualize overall attention từ output token đến input patches
- C. Giống Grad-CAM
- D. Chỉ cho NLP

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Combine attention weights qua layers để visualize overall attention từ output token đến input patches

**Giải thích:** <!-- TODO -->

</details>

### Câu 960
Nguồn PDF: trang 131

Điều nào đúng về ViT patch size trade-off?

- A. Smaller patches luôn tốt hơn
- B. Smaller patches → finer detail, nhiều tokens, tốn computation hơn; larger patches → ít tokens, coarser
- C. Patch size không quan trọng
- D. Chỉ 16×16 hoạt động

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Smaller patches → finer detail, nhiều tokens, tốn computation hơn; larger patches → ít tokens, coarser

**Giải thích:** <!-- TODO -->

</details>

### Câu 961
Nguồn PDF: trang 131

Điều nào đúng về multi-head attention trong ViT?

- A. Chỉ 1 head
- B. Multiple attention heads learn different aspects của relationships giữa patches
- C. Không có attention
- D. Chỉ self-attention

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Multiple attention heads learn different aspects của relationships giữa patches

**Giải thích:** <!-- TODO -->

</details>

### Câu 962
Nguồn PDF: trang 131

Tại sao positional encoding cần thiết trong ViT?

- A. Vì ViT không có convolution
- B. Vì self-attention permutation-invariant; positional encoding inject spatial information về order của patches
- C. Không cần
- D. Vì patches không có position

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Vì self-attention permutation-invariant; positional encoding inject spatial information về order của patches

**Giải thích:** <!-- TODO -->

</details>

### Câu 963
Nguồn PDF: trang 131

Điều nào đúng về knowledge in pre-trained vision models?

- A. Chỉ học low-level features
- B. Hierarchical: early layers → edges/colors, mid layers → textures/parts, late layers → objects/concepts
- C. Chỉ học colors
- D. Không học được useful features

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Hierarchical: early layers → edges/colors, mid layers → textures/parts, late layers → objects/concepts

**Giải thích:** <!-- TODO -->

</details>

### Câu 964
Nguồn PDF: trang 131

Điều nào đúng về Deformable Attention trong Deformable DETR?

- A. Attend tất cả spatial locations
- B. Attend chỉ K sampling locations per query → linear complexity, faster convergence
- C. Không có attention
- D. Chỉ local attention

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Attend chỉ K sampling locations per query → linear complexity, faster convergence

**Giải thích:** <!-- TODO -->

</details>

### Câu 965
Nguồn PDF: trang 132

Điều nào đúng về bipartite matching trong DETR?

- A. Hungarian không tối ưu
- B. Hungarian algorithm tìm unique 1-to-1 matching giữa predictions và ground truths → eliminate NMS
- C. Không cần matching
- D. Tất cả predictions matched

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Hungarian algorithm tìm unique 1-to-1 matching giữa predictions và ground truths → eliminate NMS

**Giải thích:** <!-- TODO -->

</details>

### Câu 966
Nguồn PDF: trang 132

Điều nào đúng về masked self-attention trong generation models?

- A. Attend tất cả positions
- B. Attend chỉ previous tokens (causal mask) để prevent attending to future tokens trong autoregressive generation
- C. Không có masking
- D. Attend random subset

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Attend chỉ previous tokens (causal mask) để prevent attending to future tokens trong autoregressive generation

**Giải thích:** <!-- TODO -->

</details>

### Câu 967
Nguồn PDF: trang 132

Điều nào đúng về Contrastive Language-Image Pre-training (CLIP)?

- A. Chỉ học visual features
- B. Maximize cosine similarity giữa correct image-text pairs và minimize cho incorrect pairs → shared embedding
- C. Chỉ học text features
- D. Cần labeled categories

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Maximize cosine similarity giữa correct image-text pairs và minimize cho incorrect pairs → shared embedding

**Giải thích:** <!-- TODO -->

</details>

### Câu 968
Nguồn PDF: trang 132

Điều nào đúng về ALIGN (A Large-scale ImaGe and Noisy-text embedding)?

- A. Cần clean data
- B. Scale up noisy image-text data (1.8B pairs) → surpass CLIP với simpler training
- C. Chỉ 400M pairs
- D. Cần manual curation

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Scale up noisy image-text data (1.8B pairs) → surpass CLIP với simpler training

**Giải thích:** <!-- TODO -->

</details>

### Câu 969
Nguồn PDF: trang 132

Điều nào đúng về Prompt Engineering trong vision-language models?

- A. Không ảnh hưởng đến performance
- B. Carefully crafted text prompts (template như "a photo of a {class}") → significant improvement
- C. Tự động tối ưu
- D. Chỉ cho NLP

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Carefully crafted text prompts (template như "a photo of a {class}") → significant improvement

**Giải thích:** <!-- TODO -->

</details>

### Câu 970
Nguồn PDF: trang 132

Điều nào đúng về CoOp (Context Optimization)?

- A. Không cần optimization
- B. Learn context tokens (soft prompts) trong embedding space thay vì hand- crafted text
- C. Chỉ cho BERT
- D. Không thể fine-tune prompts

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Learn context tokens (soft prompts) trong embedding space thay vì hand- crafted text

**Giải thích:** <!-- TODO -->

</details>

### Câu 971
Nguồn PDF: trang 132

Điều nào đúng về Adapter trong vision-language fine-tuning?

- A. Fine-tune tất cả weights
- B. Small bottleneck modules inserted vào transformer layers; chỉ train adapters → parameter-efficient
- C. Không thể fine-tune
- D. Giống standard fine-tuning

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Small bottleneck modules inserted vào transformer layers; chỉ train adapters → parameter-efficient

**Giải thích:** <!-- TODO -->

</details>

### Câu 972
Nguồn PDF: trang 133

Điều nào đúng về LoRA (Low-Rank Adaptation) trong CV?

- A. Full fine-tuning
- B. Decompose weight update matrix thành low-rank product → few trainable parameters
- C. Không dùng cho vision
- D. Tăng parameters nhiều

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Decompose weight update matrix thành low-rank product → few trainable parameters

**Giải thích:** <!-- TODO -->

</details>

### Câu 973
Nguồn PDF: trang 133

Điều nào đúng về DINOv2 features trong downstream tasks?

- A. Chỉ cho classification
- B. Strong universal features từ self-supervised DINO pre-training → competitive on diverse tasks without fine-tuning
- C. Cần fine-tuning
- D. Kém hơn supervised

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Strong universal features từ self-supervised DINO pre-training → competitive on diverse tasks without fine-tuning

**Giải thích:** <!-- TODO -->

</details>

### Câu 974
Nguồn PDF: trang 133

Điều nào đúng về Scale-MAE?

- A. Standard MAE
- B. MAE với scale-aware learning: mask prediction conditioned on scale → better multi-scale representation
- C. Không liên quan đến scale
- D. Chỉ cho small images

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. MAE với scale-aware learning: mask prediction conditioned on scale → better multi-scale representation

**Giải thích:** <!-- TODO -->

</details>

### Câu 975
Nguồn PDF: trang 133

Điều nào đúng về Image Tokenization trong generation models?

- A. Dùng raw pixels
- B. Convert images thành discrete tokens (VQ-VAE codes) hoặc continuous embeddings cho autoregressive generation
- C. Không cần tokenization
- D. Chỉ 256 tokens

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Convert images thành discrete tokens (VQ-VAE codes) hoặc continuous embeddings cho autoregressive generation

**Giải thích:** <!-- TODO -->

</details>

### Câu 976
Nguồn PDF: trang 133

Điều nào đúng về Stable Diffusion và Latent Diffusion Models?

- A. Diffusion trong pixel space
- B. Diffusion trong latent space của pre-trained autoencoder → computationally efficient
- C. Không dùng VAE
- D. Chỉ cho inpainting

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Diffusion trong latent space của pre-trained autoencoder → computationally efficient

**Giải thích:** <!-- TODO -->

</details>

### Câu 977
Nguồn PDF: trang 133

Điều nào đúng về DDPM (Denoising Diffusion Probabilistic Models)?

- A. Single-step generation
- B. Gradually add Gaussian noise → learn to denoise; sample bằng reversed process qua T steps
- C. Không có noise
- D. Chỉ cho audio

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Gradually add Gaussian noise → learn to denoise; sample bằng reversed process qua T steps

**Giải thích:** <!-- TODO -->

</details>

### Câu 978
Nguồn PDF: trang 133

Điều nào đúng về Classifier-Free Guidance trong diffusion?

- A. Cần external classifier
- B. Train conditional và unconditional model jointly → guide generation với interpolated score
- C. Không cần conditioning
- D. Kém hơn classifier guidance

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Train conditional và unconditional model jointly → guide generation với interpolated score

**Giải thích:** <!-- TODO -->

</details>

### Câu 979
Nguồn PDF: trang 134

Điều nào đúng về 3D Gaussian Splatting so với NeRF?

- A. Slower rendering
- B. Explicit Gaussian primitives → real-time rendering; NeRF → slow implicit ray marching
- C. Lower quality
- D. Không thể train từ images

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Explicit Gaussian primitives → real-time rendering; NeRF → slow implicit ray marching

**Giải thích:** <!-- TODO -->

</details>

### Câu 980
Nguồn PDF: trang 134

Điều nào đúng về Instant NeRF (iNGP - Instant Neural Graphics Primitives)?

- A. Chậm như NeRF gốc
- B. Multiresolution hash encoding → training trong phút thay vì giờ
- C. Không dùng hash
- D. Kém chất lượng hơn NeRF

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Multiresolution hash encoding → training trong phút thay vì giờ

**Giải thích:** <!-- TODO -->

</details>

### Câu 981
Nguồn PDF: trang 134

Điều nào đúng về test-time compute scaling trong vision models?

- A. Không có effect
- B. Inference-time scaling (beam search, majority voting, verifier) → tăng accuracy không cần retrain
- C. Chỉ cho NLP
- D. Làm giảm accuracy

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Inference-time scaling (beam search, majority voting, verifier) → tăng accuracy không cần retrain

**Giải thích:** <!-- TODO -->

</details>

### Câu 982
Nguồn PDF: trang 134

Điều nào đúng về Mixture of Experts (MoE) trong vision?

- A. Tất cả experts được kích hoạt
- B. Sparse MoE: chỉ activate subset of experts per token → more params, same compute
- C. Không thể cho vision
- D. Kém hơn dense model

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Sparse MoE: chỉ activate subset of experts per token → more params, same compute

**Giải thích:** <!-- TODO -->

</details>

### Câu 983
Nguồn PDF: trang 134

Điều nào đúng về Flash Attention?

- A. Approximate attention
- B. IO-aware exact attention: fuse operations, không materialize large attention matrix → faster và less memory
- C. Kém chính xác
- D. Chỉ cho training

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. IO-aware exact attention: fuse operations, không materialize large attention matrix → faster và less memory

**Giải thích:** <!-- TODO -->

</details>

### Câu 984
Nguồn PDF: trang 134

Điều nào đúng về scaling laws trong vision models?

- A. Không có scaling laws
- B. Performance cải thiện predictably với model size, data, và compute → guide model development
- C. Chỉ cho language models
- D. Performance ngừng cải thiện sớm

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Performance cải thiện predictably với model size, data, và compute → guide model development

**Giải thích:** <!-- TODO -->

</details>

### Câu 985
Nguồn PDF: trang 134

Điều nào đúng về Emergent Capabilities trong large vision models?

- A. Không có emergent capabilities
- B. Khả năng mới xuất hiện đột ngột khi scale lên: few-shot learning, reasoning, zero-shot
- C. Chỉ tăng accuracy
- D. Chỉ cho language models

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Khả năng mới xuất hiện đột ngột khi scale lên: few-shot learning, reasoning, zero-shot

**Giải thích:** <!-- TODO -->

</details>

### Câu 986
Nguồn PDF: trang 135

Điều nào đúng về Interpretability của Transformer attention trong Vision?

- A. Attention maps = explanation
- B. Attention maps không hoàn toàn explain behavior; cần gradient-based methods cho reliable explanation
- C. Không thể interpret
- D. Attention luôn focus đúng

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Attention maps không hoàn toàn explain behavior; cần gradient-based methods cho reliable explanation

**Giải thích:** <!-- TODO -->

</details>

### Câu 987
Nguồn PDF: trang 135

Điều nào đúng về Data Curation tầm quan trọng trong foundation models?

- A. Quantity over quality
- B. Data quality/diversity quan trọng như model architecture; carefully curated data → better models
- C. Không quan trọng
- D. Chỉ cần nhiều data

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Data quality/diversity quan trọng như model architecture; carefully curated data → better models

**Giải thích:** <!-- TODO -->

</details>

### Câu 988
Nguồn PDF: trang 135

Điều nào đúng về evaluation của generative vision models?

- A. Chỉ FID
- B. Multi-dimensional: FID, Inception Score, CLIP score, human evaluation → không có single metric
- C. Chỉ human evaluation
- D. Chỉ pixel accuracy

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Multi-dimensional: FID, Inception Score, CLIP score, human evaluation → không có single metric

**Giải thích:** <!-- TODO -->

</details>

### Câu 989
Nguồn PDF: trang 135

Điều nào đúng về Retrieval Augmented Generation (RAG) trong vision-language?

- A. Chỉ cho NLP
- B. Retrieve relevant images/text from knowledge base → augment generation với external knowledge
- C. Không cần knowledge base
- D. Giống standard generation

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Retrieve relevant images/text from knowledge base → augment generation với external knowledge

**Giải thích:** <!-- TODO -->

</details>

### Câu 990
Nguồn PDF: trang 135

Điều nào đúng về Constitutional AI trong CV applications?

- A. Không liên quan
- B. Design AI systems với built-in principles/constraints để ensure safety và alignment
- C. Chỉ cho chatbots
- D. Làm giảm performance

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Design AI systems với built-in principles/constraints để ensure safety và alignment

**Giải thích:** <!-- TODO -->

</details>

### Câu 991
Nguồn PDF: trang 135

Tại sao Multi-scale feature pyramid quan trọng trong modern detectors?

- A. Không quan trọng
- B. Detect objects ở mọi size: small objects → high-res early features, large → low-res late features
- C. Chỉ cho large objects
- D. Chậm hơn single scale

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Detect objects ở mọi size: small objects → high-res early features, large → low-res late features

**Giải thích:** <!-- TODO -->

</details>

### Câu 992
Nguồn PDF: trang 136

Điều nào đúng về Weight sharing trong CNN và tại sao quan trọng?

- A. Không có weight sharing
- B. Cùng filter áp dụng tại mọi spatial location → dramatically giảm parameters và tăng generalization
- C. Tăng parameters
- D. Chỉ cho square inputs

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Cùng filter áp dụng tại mọi spatial location → dramatically giảm parameters và tăng generalization

**Giải thích:** <!-- TODO -->

</details>

### Câu 993
Nguồn PDF: trang 136

Điều nào đúng về Equivariance vs Invariance trong CNN?

- A. CNN hoàn toàn invariant
- B. Conv layers equivariant với translation (output dịch khi input dịch); pooling tạo partial invariance
- C. Không có equivariance
- D. CNN hoàn toàn equivariant

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Conv layers equivariant với translation (output dịch khi input dịch); pooling tạo partial invariance

**Giải thích:** <!-- TODO -->

</details>

### Câu 994
Nguồn PDF: trang 136

Điều nào đúng về Information Bottleneck Theory trong deep learning?

- A. Không liên quan
- B. Network learns to compress input và retain relevant information về output → understanding generalization
- C. Chỉ cho NLP
- D. Không thể measure

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Network learns to compress input và retain relevant information về output → understanding generalization

**Giải thích:** <!-- TODO -->

</details>

### Câu 995
Nguồn PDF: trang 136

Điều nào đúng về Double Descent phenomenon?

- A. Performance chỉ xấu đi với large models
- B. Performance curve: decrease → increase → decrease lại khi model size/training tăng; belies classical bias-variance
- C. Chỉ xảy ra với small models
- D. Không tồn tại

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Performance curve: decrease → increase → decrease lại khi model size/training tăng; belies classical bias-variance

**Giải thích:** <!-- TODO -->

</details>

### Câu 996
Nguồn PDF: trang 136

Điều nào đúng về Lazy Training trong overparameterized networks?

- A. Model không learn
- B. Weights stay near initialization; model effectively a linear function of parameters
- C. Model diverges
- D. Không thể train

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Weights stay near initialization; model effectively a linear function of parameters

**Giải thích:** <!-- TODO -->

</details>

### Câu 997
Nguồn PDF: trang 136

Tại sao Batch Normalization giúp training với high learning rates?

- A. Không ảnh hưởng
- B. Smooth optimization landscape → less sensitive to initialization và learning rate → can use larger LR
- C. Tăng gradient
- D. Giảm learning rate

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Smooth optimization landscape → less sensitive to initialization và learning rate → can use larger LR

**Giải thích:** <!-- TODO -->

</details>

### Câu 998
Nguồn PDF: trang 136

Điều nào đúng về Neural Scaling Laws (Kaplan et al.)?

- A. Performance không thể predict
- B. L(N,D,C) follow power laws: L ∝ N^(-αN) etc.; giúp predict optimal allocation of compute
- C. Chỉ cho language
- D. Không có power law

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. L(N,D,C) follow power laws: L ∝ N^(-αN) etc.; giúp predict optimal allocation of compute

**Giải thích:** <!-- TODO -->

</details>

### Câu 999
Nguồn PDF: trang 137

Điều nào đúng về tương lai của Computer Vision theo hướng AGI?

- A. CV đã đủ
- B. Cần common sense reasoning, causal understanding, và robust generalization → gap giữa CV và AGI còn lớn
- C. CV = AGI
- D. Không liên quan

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Cần common sense reasoning, causal understanding, và robust generalization → gap giữa CV và AGI còn lớn

**Giải thích:** <!-- TODO -->

</details>

### Câu 1000
Nguồn PDF: trang 137

Điều nào tổng kết đúng nhất về sứ mệnh của môn học Thị giác Máy tính (IT5409)?

- A. Học thuật toán lọc ảnh
- B. Trang bị kiến thức nền tảng từ Low-level đến High-level vision, từ traditional methods đến deep learning, để giải quyết các bài toán thực tế về hiểu thế giới thực qua hình ảnh
- C. Chỉ học Deep Learning
- D. Chỉ học xử lý ảnh cơ bản

<details>
<summary>Hiện đáp án và giải thích</summary>

**Đáp án:** B. Trang bị kiến thức nền tảng từ Low-level đến High-level vision, từ traditional methods đến deep learning, để giải quyết các bài toán thực tế về hiểu thế giới thực qua hình ảnh

**Giải thích:** <!-- TODO -->

</details>
