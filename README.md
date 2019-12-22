# FinalProjectWebScience

# 1. File CrawlCommentFromTiki: Crawl comment từ trang Tiki https://tiki.vn/?utm_source=google&utm_medium=cpc&utm_campaign=SEA_YBR_GGL_TXT_SBR_ALL_VN_ALL_UNK_UNK_C.ALL_X.7602151122_Y.80058006606_Q.e_K.Tiki_W.DT_R.392788512410_L.HP&gclid=Cj0KCQiAovfvBRCRARIsADEmbRKWMmpI5GPnIJIMBT311EdeWLxKea_Um3e4iUR8_zyqUHwRiAJiRIAaArtxEALw_wcB
## - Bước 1: Trong từng mục sản phẩm từ trang chủ Tiki (ví dụ: mục Điện thoại - Máy tính bảng, mục Điện tử - Điện lạnh, ...)
## lấy tất cả các link sản phẩm trong 5 trang đầu tiên của mỗi mục, sau đó lưu tất cả các link đã tìm được vào file ProductLinkTiki.csv
## - Bước 2: Vào từng link trong file ProductLinkTiki.csv để lấy comment và rating của từng comment, dữ liệu thô thu được lưu vào file Data.csv
## - Bước 3: Sau khi có file Data.csv thì tiến hành tiền xử lí, cho ra kết quả là file data_clean.csv


# 2. File modelAnalystSecmentVietnamese.py: Train và Test model phân loại các comment. Dùng 2 model để so sánh kết quả phân loại
## - Model 1: 
