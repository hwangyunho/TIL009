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

## 판다스