# 1. Cách flash firmware (mới) cho controller STeMCell
## Bước 1: Cắm cáp usb và bấm 2 lần nút `UPDATE` ở pcb holder/adapter ở dưới bottom case. 
- Sau khoảng 2s sẽ hiện ra USB Drive STeMCell như ảnh:
![image](https://user-images.githubusercontent.com/95753855/177046044-9e225d21-bf4f-4f1e-8506-649992996963.png)

## Bước 2: Kéo thả hoặc copy paste file `bastardkb_..._stemcell.uf2` vào USB Drive STeMCell

## Bước 3: Lặp lại tương tự với bên còn lại nếu dùng Split, test phím và enjoy!

# 2. Cách setup app Vial (tương tự app Via)

## Tải và cài đặt app Vial [ở đây](https://get.vial.today/download/) 
Có thể tải bản portable (chạy trong 1 folder) cho tiện.

## Cắm cáp usb và mở app Vial
![image](https://user-images.githubusercontent.com/95753855/177046865-d175d9e0-9bb2-4955-9a0b-24a160957f76.png)

## Bấm mở thẻ `File` gốc trái màn hình, chọn `Sideload VIA JSON`
![image](https://user-images.githubusercontent.com/95753855/177046891-d1cf46e3-fccc-4689-9f3d-fdc5963ffad9.png)

## Chọn file `.json` tương ứng với tên phím và bấm `Open`

## Cách tải file json: 
- Click vào link `ở đây` ở dưới, trỏ con chuột vào ô `Raw`(bên phải màn hình), click chuột phải và chọn `Save link as`.
![image](https://user-images.githubusercontent.com/95753855/180714132-9cd92a0e-f2e6-4690-842f-2bfd747637b3.png)

### File json cho Scylla [ở đây](https://github.com/Deemen17/bastardkb-guide-vietnamese/blob/main/firmware/scylla/scylla_vial.json)
### File json cho Skeletyl [ở đây](https://github.com/Deemen17/bastardkb-guide-vietnamese/blob/main/firmware/skeletyl/skeletyl_vial.json)

![image](https://user-images.githubusercontent.com/95753855/177046976-53c57afe-ffdc-481f-ada7-79ff7884b85a.png)

## Kết quả
![image](https://user-images.githubusercontent.com/95753855/177047067-b73b56b0-501d-4c12-8016-2e3670c347fe.png)

# Cách keymap cho phím qua app Vial

## Click chọn 1 key muốn sửa (viền blue)
![image](https://user-images.githubusercontent.com/95753855/177047153-ad2e0a34-eae7-4c7e-b720-5fc3e9d886f6.png)
## Chọn keycode muốn sửa ở bảng dưới
- Ví dụ: Mình sửa nút `Esc` thành nút `F1`. Tìm thẻ Basic và chọn key F1
![image](https://user-images.githubusercontent.com/95753855/177047191-d507a91b-a6e8-4a2e-bf36-92d618cba8d9.png)

## Kết quá
![image](https://user-images.githubusercontent.com/95753855/177047309-8a01d5a0-8814-495a-9659-66e3f7a55994.png)

# Cách save và load keymap đã sửa
## Để save keymap, bấm mở thẻ `File` gốc trái màn hình, chọn `Save current layout ...`, hoặc bấm tổ hợp `Ctrl+S`
![image](https://user-images.githubusercontent.com/95753855/177047365-8f4ca8c5-2ae4-4112-9535-e5181898db40.png)

## Đặt tên file và bấm `Save`
![image](https://user-images.githubusercontent.com/95753855/177047454-72d93504-fbd4-49a4-9fbf-edd96c9535de.png)

## Để load keymap đã lưu, bấm mở thẻ `File` gốc trái màn hình, chọn `Load current layout ...`, hoặc bấm tổ hợp `Ctrl+O`
![image](https://user-images.githubusercontent.com/95753855/177047503-f0fddfaa-a17f-4c38-b245-263e8490986e.png)
## Click chọn file `.vil` đã save và chọn `Open`
![image](https://user-images.githubusercontent.com/95753855/177047533-1e7fe5a7-7049-47d1-bf7a-0bb3ebc1af40.png)
## Kết quả
![image](https://user-images.githubusercontent.com/95753855/177047592-46ddc7e2-b15a-4381-8be1-cb8f81481fb9.png)



# Updating




