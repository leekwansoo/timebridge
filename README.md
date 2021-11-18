# timebridge
# 새로운 기능
# 사진 Multi 로 올리기 multiload.html
# video file play 및 edit 하기: videopage.html   videoedit.html

# File 변경
# list.html: video play 됨, image: 가장 최근에 upload 된 순서대로 정렬됨 db.collection('product').(doc.id).(orderBy("date")).get()
# detail.html: list 에서 detail.html 로 넘어올때 file type 이면 videopage.html 로 넘어감
# edit.html: list.html 에서 바로 수정 Button 눌렀을때, edit.html 로 넘어간후 edit.html 에서 filetype 검사하여 mp4 video file 인 경우 videoedit.html 로 넘김
# edit.html 및 videoedit.html 에 file delete 기능 추가: file delete firestore DB 와 storage 에 있는 url 주소의 image file 도 같이 삭제됨
