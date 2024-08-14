### 연습중입니다.
- 파이썬코드 실습
- 모코코 귀여워
- 깃허브 어려워

# 이미지 파일 경로
image_path = 'D:/진혁/data/mokoko.png'  # 여기에 이미지 파일 경로를 입력하세요

# 이미지 불러오기
img = mpimg.imread(image_path)

# 이미지 출력
plt.imshow(img)
plt.axis('off')  # 축 레이블 끄기
plt.show()
