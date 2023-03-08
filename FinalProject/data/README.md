### Giới thiệu về dataset
- Million Song là một bộ dữ liệu gồm các tính năng và siêu dữ liệu âm thanh được cung cấp miễn phí cho một triệu bản nhạc nổi tiếng đương thời.
- Bộ dữ liệu Million Song bắt đầu là một dự án hợp tác giữa The Echo Nest và LabROSA. Nó được hỗ trợ một phần bởi NSF.
    + Dataset Source: http://labrosa.ee.columbia.edu/millionsong/
    + Paper: http://ismir2011.ismir.net/papers/OS6-1.pdf
- Nhóm sẽ không sử dụng trực tiếp tập dữ liệu này, nhưng nhóm sẽ sử dụng một số phần của nó. 
    + Tập dữ liệu: Million Song - Recommendation Engines (Gồm có "10000.txt" và "song_data.csv")
    + Link dataset: https://www.kaggle.com/code/mgmarques/million-song-recommendation-engines/data 
- Tập dữ liệu về user (10000.txt) có 3 cột và 2000000 dòng chứa số lượt phát của người dùng ẩn danh cho các bài hát có trong tập dữ liệu triệu bài hát:
    + user_id: ID của người dùng
    + song_id: ID của bài hát
    + listen_count: Lượt nghe của bài hát
- Tập dữ liệu về bài hát (song_data.csv) có 5 cột và 1000000 dòng chứa các thuộc tính của một triệu bài hát:
    + song_id: ID của bài hát
    + title: Tên bài hát
    + release: Tên ablum của bài hát đó (
    + artist_name: Tên nghệ sĩ, ca sĩ
    + year: Năm bài hát được phát hành
