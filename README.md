${\textsf{\color{red}svg 란?}}$<br>

${\textsf{\color{red}svg}}$는 웹에서 벡터 그래픽을 표현하기 위한 XML 기반의 파일 형식이다.<br>
${\textsf{\color{red}벡터 그래픽은}}$픽셀 단위가 아닌 수학적 좌표로 그래픽을 표현하기 때문에, 확대나 축소 시에도 이미지가 깨지지 않고 선명하게 유지된다<br>
${\textsf{\color{red}svg}}$는 직선, 곡선, 다각형 등의 다양한 도형을 정의할 수 있으며, 애니메이션이나 상호작용도 가능하다.<br>
<br>
${\textsf{\color{red}<path> 요소}}$는 SVG에서 가장 유연하고 강력한 도형 요소로, 직선, 곡선, 호, 복잡한 다각형 등 다양한 도형을 그릴 수 있다.<br>
${\textsf{\color{red}d 속성}}$ path 요소에서 경로 데이터를 정의하는 속성입니다. 즉, 어떤 모양을 그릴지 결정하는 명령어들이 들어 있다.<br>
${\textsf{\color{red}d 속성}}$은 일련의 명령어와 좌표로 구성되며, 명령어는 대문자와 소문자로 표시됩니다. 대문자는 절대 좌표를, 소문자는 상대 좌표를 의미한다.<br>
<br>
${\textsf{\color{red}M}}$ (moveto): 시작 지점을 설정함. M x,y<br>
${\textsf{\color{red}L}}$ (lineto): 직선을 그림. L x,y<br>
${\textsf{\color{red}H}}$ (horizontal lineto): 수평선을 그림. H x<br>
${\textsf{\color{red}V}}$ (vertical lineto): 수직선을 그림. V y<br>
${\textsf{\color{red}C}}$ (curveto): 베지어 곡선을 그림. C x1,y1 x2,y2 x,y<br>
${\textsf{\color{red}S}}$ (smooth curveto): 부드러운 베지어 곡선을 그림.<br>
${\textsf{\color{red}Q}}$ (quadratic Bézier curve): 2차 베지어 곡선을 그림. Q x1,y1 x,y<br>
${\textsf{\color{red}T}}$ (smooth quadratic Bézier curveto): 부드러운 2차 베지어 곡선을 그림.<br>
${\textsf{\color{red}A}}$ (elliptical Arc): 타원형 호를 그림. A rx,ry x-axis-rotation large-arc-flag,sweep-flag x,y<br>
${\textsf{\color{red}Z}}$ (closepath): 현재 경로를 닫는다.<br>
<br>
${\textsf{\color{red}stroke 속성}}$은 SVG 도형의 경계선 색상을 정의한다. 이 속성을 사용하면 도형의 외곽선, 즉 테두리의 색상을 설정할 수 있다.(rgb 적용도 가능하다) border-shadow랑 비슷?<br>
${\textsf{\color{red}즉. 도형의 경계선 색상과 스타일을 정의함.}}$<br>
<br>
${\textsf{\color{red}fill 속성}}$은 SVG 도형의 내부 색상을 정의한다. 이 속성을 사용하여 도형의 내부를 색상으로 채울 수 있다.(rgb 적용도 가능) backgroud-color 랑 비슷? <br>
${\textsf{\color{red}즉. 도형의 내부 색상과 스타일을 정의함.}}$



