# TIL009



## 넘파이
*  수식 라이브러리, 수치연산, 배열의 객체
-- 동작 속도가 빠르다. / 연속적인 메모리 / 한가지 타입만 처리가능
1. np.array 로 객체생성
2. np.arange 로 객체생성
3.  ndarray(shape[, dtype, buffer, offset, ...]) / shape
> * 3-1.    차원 (Rank, Dimension)을 [] 로 갯수를 늘린다. [[a]] = 2차원, [[[b]]] = 3차원
    아벨 4차원이상 -> 컴
    대상 -> 특징추출(x_독립변수, y_종속변수) -> 도메인 -> 설명(통계_R / python) -> 예측(ML) 
    -> ML + AI = DL (CNN, 이미지 영상)
>  * 3-2. 차원의 종류
        1차원 shape(x,)
        2차원 shape(x,y), 행렬(matrix)
        3차원 shape(x,y,z), (행,열,면) -> (면,행,열) [[[ x,y,z ]]]
        ...n차원 : (x,y,z,,,,,,)
4. 배열과 슬라이싱 _reshape()
5. 불린 인덱싱 : 조건석을 이용한 인덱싱, 조건 검색 필터를 사용한 추출 값 (중요!!)
6. 배열의 형상 다루기 : reshape(), flatten()(편평화), transpose()(전치)
7. numpy의 속성 (Attribute): 멤버변수, 메서드 dtype, shape, ndim, flat, T, size, nbytes

***

## 판다스

1. 시리즈 및 데이터 프레임
2. 시리즈 ( Series) 만들기
3. 데이터 프레임 ( DataFrame) 만들기
4. CSV 파일에서 데이터 프레임 만들기
5. 데이터 참조 및 데이터 조건 검색
6. 열 추가 및 삭제 ,행 추가 및 삭제
7. 데이터 정렬,  통계량
8. 데이터 연결, 결합
