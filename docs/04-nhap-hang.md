# Nhập hàng theo đơn đặt hàng của tct

<p class="doc-code">TÀI LIỆU 04 · HƯỚNG DẪN NGHIỆP VỤ KIOTVIET</p>

!!! video "Video hướng dẫn (có giọng đọc)"
    <video controls preload="metadata" playsinline style="width:100%;border-radius:8px" src="../video/04.mp4"></video>

    [:material-download: Tải video về máy](video/04.mp4){ download }

| Thông tin | Nội dung |
|---|---|
| **Mục đích** | Nhập kho hàng NCC giao **theo đúng đơn đặt hàng do TCT (TTĐH) đặt**, đúng số lượng thực nhận, để phiếu nhập khớp với đơn và với hóa đơn thanh toán cho NCC. |
| **Người thực hiện** | Cửa hàng trưởng hoặc nhân viên nhận hàng |
| **Thời điểm** | Ngay khi kiểm đếm xong hàng NCC giao, trước khi bày bán |

!!! tip "Cách đọc"
    Số trong **vòng tròn đỏ** trên ảnh tương ứng với mục <span class="num">1</span> <span class="num">2</span> <span class="num">3</span>… trong phần chữ của bước đó; **khung đỏ** khoanh vùng cần bấm hoặc cần kiểm tra.

## Quy định bắt buộc

!!! important "CHỈ NHẬP KHO THEO ĐƠN ĐẶT HÀNG CỦA TCT (TTĐH) – KHÔNG TỰ TẠO PHIẾU NHẬP (PO)"
    Mọi phiếu nhập phải được tạo bằng nút **Tạo phiếu nhập** trên **đơn đặt hàng nhập (PDN)** của TCT/TTĐH. **Không** dùng nút **+ Nhập hàng** để tự tạo phiếu nhập.

    Lý do: NCC được **thanh toán theo đơn đặt hàng của TCT**. Phiếu nhập tự tạo không gắn với đơn → đơn TTĐH vẫn treo ở trạng thái chờ, số lượng nhập không khớp đơn, **dẫn đến lệch hóa đơn thanh toán cho NCC** (thanh toán thiếu, thừa hoặc trùng).

    Không tìm thấy đơn đặt hàng cho lô hàng đang giao: **không tự tạo phiếu nhập, không bày bán**, báo ngay TTĐH và Bộ phận Hệ thống BU BHBĐ.


## Bước 1. Mở danh sách Đặt hàng nhập

Vào **Mua hàng → Đặt hàng nhập** và tìm đơn của NCC đang giao (cách lọc và tìm chi tiết xem **tài liệu 12**).

<span class="num">1</span> Rê chuột vào menu **Mua hàng**.  
<span class="num">2</span> Chọn **Đặt hàng nhập** (không chọn mục *Nhập hàng*).  

<figure markdown="span">
  ![Menu Mua hàng → Đặt hàng nhập](img/d1_menu_muahang.jpg){ loading=lazy }
  <figcaption>Hình 1. Menu Mua hàng → Đặt hàng nhập</figcaption>
</figure>

## Bước 2. Mở đơn PDN và bấm Tạo phiếu nhập

Bấm vào dòng đơn PDN đúng NCC, đúng ngày đặt; kiểm tra trạng thái và số lượng rồi:

<span class="num">1</span> Bấm **Tạo phiếu nhập**. Hệ thống điền sẵn NCC, mặt hàng và số lượng theo đơn của TCT.  
<span class="num">2</span> **Mở phiếu** chỉ dùng để xem/sửa đơn, không dùng để nhập kho.  
<span class="num">3</span> **Không bấm Hủy**: nút này hủy đơn đặt hàng của TCT.  

<figure markdown="span">
  ![Nút Tạo phiếu nhập trên đơn đặt hàng nhập](img/d6_thaotac.jpg){ loading=lazy }
  <figcaption>Hình 2. Nút Tạo phiếu nhập trên đơn đặt hàng nhập</figcaption>
</figure>

## Bước 3. Kiểm đếm và nhập số lượng thực nhận

<span class="num">1</span> Đếm hàng thực tế và sửa **Số lượng** theo số thực nhận. Con số "/5" bên dưới là số lượng đã đặt. **Không nhập vượt** số lượng đặt.  
<span class="num">2</span> Kiểm tra **Mã đặt hàng nhập** đúng là đơn PDN vừa chọn.  
<span class="num">3</span> Nhập **Số hóa đơn đầu vào** (số hóa đơn của NCC giao kèm hàng).  
<span class="num">4</span> Bấm **Hoàn thành**. Tồn kho cửa hàng được cộng ngay sau bước này.  

**Hàng quản lý theo Lô – Hạn sử dụng:** với các mặt hàng đã chuyển sang quản lý theo lô, nhập đúng **số lô** và **hạn sử dụng** in trên bao bì cho từng dòng hàng trước khi bấm Hoàn thành.

<figure markdown="span">
  ![Phiếu nhập tạo từ đơn đặt hàng (công nợ NCC đã làm mờ)](img/n2_phieunhap.jpg){ loading=lazy }
  <figcaption>Hình 3. Phiếu nhập tạo từ đơn đặt hàng (công nợ NCC đã làm mờ)</figcaption>
</figure>

## Bước 4. Kiểm tra phiếu nhập

<span class="num">1</span> Phiếu mới (mã **PN…**) nằm đầu danh sách **Nhập hàng**; cột **Mã đặt hàng nhập** phải có mã PDN. Phiếu nào **không có mã PDN** là phiếu tự tạo, sai quy định.  
<span class="num">2</span> Trạng thái **Đã nhập hàng** là đã cộng tồn kho.  
<span class="num">3</span> Đối chiếu lại **mặt hàng và số lượng** với hóa đơn/phiếu giao của NCC.  

<figure markdown="span">
  ![Phiếu nhập đã liên kết với đơn đặt hàng](img/n3_ketqua.jpg){ loading=lazy }
  <figcaption>Hình 4. Phiếu nhập đã liên kết với đơn đặt hàng</figcaption>
</figure>

## Lưu ý và lỗi thường gặp

| Tình huống | Cách xử lý |
|---|---|
| Hàng về nhưng không tìm thấy đơn đặt hàng | Kiểm tra lại bộ lọc chi nhánh, trạng thái, thời gian (tài liệu 12). Vẫn không có: không tự tạo phiếu nhập, không bày bán; báo TTĐH và Bộ phận Hệ thống BU BHBĐ. |
| NCC giao thiếu so với đơn | Nhập đúng số thực nhận. Đơn chuyển sang Nhập một phần; lần giao bù tạo tiếp phiếu nhập từ chính đơn đó. |
| NCC giao thừa hoặc giao hàng ngoài đơn | Chỉ nhập đúng số lượng và mặt hàng có trong đơn. Phần thừa / ngoài đơn không nhập, báo TTĐH xử lý. |
| Hàng giao bị hỏng, móp méo, cận date | Không nhận và không nhập phần hàng đó; ghi chú lên phiếu và báo NCC. |
| Lo ngại nhập trùng | Trước khi tạo phiếu, kiểm tra cột Số lượng của đơn (dạng đặt/đã nhập) để biết đã nhập chưa. |
| Đã lỡ tự tạo phiếu nhập không theo đơn | Không tự tạo thêm phiếu để bù. Báo ngay Bộ phận Hệ thống BU BHBĐ kèm mã phiếu PN để xử lý. |

**Phím tắt:** F3: tìm hàng hóa
