trươcd khi CSS thì phải reset
nó ăn hết cả trang
*{
    padding:0;
    margin:0;
    border-sizing: horder-
}



element class id <!important>
ctr/ là */


# Layout : thiết kế bố cụ các element theo ý muốn.
1. float
2. position: định vị khối , 
2.1 trạng thái mặc định: static
2.2 relative: vị trí tương đối
<khi một element có thuộc tính position= relativethì nó sẽ lấy vị trí ban đầu làm gốc, khi muốn căn chỉnh khối theo các chiều thì dùng top, right, left, buttom>
2.3 absolute: vị trí tuyệt đối
<nó sẽ ăn theo vị trí của thằng cha chưa nó gânf nhất có thuộc tính là position khác statics thì sẽ lấy vị trí gốc.
nếu không có thằng cha nào chứa nó thì sẽ ăn theo kích thước màn hình>
2.4 fixed 
<công dụng: cố đinh element khi lăn chuột>
2.5 sticky
3. flex: định dạng một chiều
<dùng để : định dạng layout
khi một elemet có thuộc tính display: flex thì sẽ dùng các thuộc tính của flex
cha:flex container con: flex-item
khi thằng cha có thuộc tính display thì các thằng con nămf trên cùng một hàng
flex-direction: để điểu chỉnh trục. trục main - axis thì trục ngang, cross-axis nằm dọc
flex-direction: colum: thì main-axis thì nằm dọc
main-axis ăn theo thuộc tính :justify-content
...:center,space-around:mép tường lề bằng 1/2 ở giữa, space-evenly:cách đều, space-beetwen: sát hai lề và khoảng cách bằng nhau.
cross-axis ăn theo thuộc tính align-item
...:center,>
4. gird: định dạng hai chiều
5. rwd- responsive web designer
