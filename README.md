# Bai <? phiên bản xml = " 1.0 " ?>
< chuyển đổi tập tin thuật  toán = " 2.11 " >
    < thuộc tính >
        < tên thuộc tính  = " tên " giá trị = " " /> 
        < tên thuộc tính  = " tác giả " value = " Quản trị viên " /> 
        < tên thuộc tính  = " về " giá trị = " " /> 
        < tên thuộc tính  = " đã lưu " value = " 2019-03-10 08:51:20 PM " /> 
        < tên thuộc tính  = " đã tạo " value = " QWRtaW5pc3RyYXRvcjs5TFRFQ1RYNjhTWERYN0M7MjAxOS0wMy0xMDswODozNDoxNyBQTTszNzQ0 " /> 
        < Thuộc tính  tên = " sửa "  giá trị = " QWRtaW5pc3RyYXRvcjs5TFRFQ1RYNjhTWERYN0M7MjAxOS0wMy0xMDswODo1MToyMCBQTTszOzM4NDc = " />
    </ thuộc tính >
    < function  name = " Main "  type = " Không "  biến = " " >
        < tham số />
        < cơ thể >
            < khai báo  name = " a "  type = " Real "  mảng = " Sai "  size = " " />
            < khai báo  name = " b "  type = " Real "  mảng = " Sai "  size = " " />
            < khai báo  name = " c "  type = " Real "  mảng = " Sai "  size = " " />
            < khai báo  name = " x1 "  type = " Real "  mảng = " Sai "  size = " " />
            < khai báo  name = " x2 "  type = " Real "  mảng = " Sai "  size = " " />
            < khai báo  name = " d "  type = " Real "  mảng = " Sai "  size = " " />
            < biểu thức đầu ra  = " & quot; Vao a, b, c: & quot; " newline = " True " /> 
            < biến đầu vào  = " a " />
            < biến đầu vào  = " b " />
            < biến đầu vào  = " c " />
            < if  biểu thức = " a == 0 " >
                < thì >
                    < biểu thức đầu ra  = " & quot; Ph & # 432; & # 417; ng tr & # 236; nh b & # 7853; c nh & # 7845; t & quot; " newline = " Đúng " /> 
                    < điểm dừng />
                </ thì >
                < khác >
                    < biểu thức đầu ra  = " & quot; Ph & # 432; & # 417; ng tr & # 236; nh b & # 7853; c hai & quot; " newline = " Đúng " /> 
                    < gán  biến = " d "  biểu thức = " b ^ 2 - 4 * a * c " />
                    < if  biểu thức = " d & gt; = 0 " >
                        < thì >
                            < nếu  biểu thức = " d = 0 " >
                                < thì >
                                    < biểu thức đầu ra  = " & quot; Ph & # 432; & # 417; ng tr & # 236; nh c & # 243; nghi & # 7879; mk & # 233; p x1 = x2 & quot; " newline = " Đúng " /> 
                                    < gán  biến = " x1 "  biểu thức = " -b / (2 * a) " />
                                    < đầu ra  biểu thức = " x1 "  newline = " Đúng " />
                                </ thì >
                                < khác >
                                    < biểu thức đầu ra  = " & quot; Ph & # 432; & # 417; ng tr & # 236; nh c & # 243; hai nghi & # 7879; m ph & # 226; n bi & # 7879; t & quot; " dòng mới = " Đúng " /> 
                                    < gán  biến = " x1 "  biểu thức = " (-b-sqrt (d)) / (2 * a) " />
                                    < gán  biến = " x2 "  biểu thức = " (-b + sqrt (d)) / (2 * a) " />
                                    < đầu ra  biểu thức = " x1 "  newline = " Đúng " />
                                    < biểu thức đầu ra  = " x2 " newline = " Đúng " /> 
                                </ khác >
                            </ nếu >
                        </ thì >
                        < khác >
                            < biểu thức đầu ra  = " & quot; Ph & # 432; & # 417; ng tr & # 236; nh kh & # 244; ng c & # 243; nghi & # 7879; m & # 7921; c & quot; " dòng mới = " Đúng " /> 
                        </ khác >
                    </ nếu >
                </ khác >
            </ nếu >
        </ cơ thể >
    </ chức năng >
</ thuật toán >
