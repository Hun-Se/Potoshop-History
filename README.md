# Potoshop-History

<img src="images/photoshop.png">

> 소개 : 빔캠프님 특강에서 과제로 주어졌던 History of Potoshop입니다.

> 프로젝트 주소

</br>

## 1. 제작 기간 & 참여 인원

- 2days & 개인프로젝트

</br>

## 2. 사용 기술

#### `Front-end`

- HTML/CSS

</br>

## 3. 핵심 사항

<details>
<summary><b>nagative-margin</b></summary>
<div markdown="1">

```CSS
 .content-main .content-timeline:after {
    content: '';
    background-color: #1c90ff;
    position: absolute;
    width: 2px;
    margin: 70px auto -50px;
    left: 0;
    right: 0;
    top: 0;
    bottom: 0;

}
```

</div>
</details>

- `native-margin`을 이용하여 부모요소를 벗어나는 효과를 주었습니다.

<details>
<summary><b>margin: x%</b></summary>
<div markdown="1">

```CSS
.content-main .content-timeline>li:nth-child(even) {
    margin-left: 52%;
}
```

```CSS
.content-main .content-timeline>li:nth-child(odd) {
    margin-right: 52%;
}
```

</div>
</details>

- margin에 %값을 주어서 해당 비율로 여유공간을 사용하여 각 요소를 정렬하였다.

</br>

## 4.어려웠던점

- 가상선택자를 사용해 만들었던 페이지 가운데 부분 파란색 구분선을 만드는것에 어려움을 느꼇다.
  <details>
  <summary><b>이미지</b></summary>
  <div markdown="1">

    <img src="images/line.png">

    </div>
    </dtails>

<br>
- 선에 위치하는 원모양의 배치는 margin과 position으로 적절한 비율로 정확한 배치를 하였지만, 선의 여백과 길이는 position으로  일일히 px로 배치하느라 정확성이 떨어지는 것 같다.

</br>

## 5. 배운점

- margin에 %를 사용하여 요소들을 정렬하는 방법을 배웠다.
- 가상 선택자 `nth-child(odd)` 와 `nth-child(even)`을 사용하여 홀수와 짝수 자식요소에 스타일을 적용하는 법을 배웠다.
- position을 이용하여 보다 자유로운 레이아웃 배치를 사용할 수 있게 되었다.
- margin-nagative를 사용하여 부모요소에 벗어나는 레이아웃 배치를 할 수 있게 되었다.

## 6. 회고

- margin과 postion등 을 활용하면서 레이아웃을 보다 쉽게 구현 할 수 있게 되었다.
