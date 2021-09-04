public class Buoi1 {
    public static void main(String[] args) {
        // 1 : Kiểu dữ liệu
        // comment code => đoạn này không thực thi (ctrl + / )
        // String (Kiểu chuỗi) ,
        // int ( kiểu số nguyên) ,
        // long( giống số nguyên mà kích thước lớn hơn)ư
        // float (kiểu số thực => số có phần thập phân 1.2)
        // double (kiểu số thực nhưng kích thước lớn hơn kiểu float)
        // boolean (kiểu luận lý tại vì chỉ có 2 giá trị là true hoặc false)

        // type variable = value
//        String name = "Nguyễn Văn Tèo";
//        int number = 5;
//        long number2 = 10L;
//        float number3 = 1.5f;
//        double number4 = 1.5;
//        boolean isChecked = true;

        // Hàm - phương thức
        // ctrl + shilt + f10
//        System.out.println("Kiểu String " + name);
//        System.out.println("Kiểu int " + number);
//        System.out.println("Kiểu long " + number2);
//        System.out.println("Kiểu float " + number3);
//        System.out.println("Kiểu double " + number4);
//        System.out.println("Kiểu boolean " + isChecked);

        // 2 : Toán tử
//        int a = 5;
//        a = a + 1;
//        a += 1;
//        a++;
//        ++a;
//        int a = 5;
//        int b = 5;
//        int b = a++;
//        int b = ++a;
//        System.out.println("Giá trị của b" + b);
//        System.out.println("Giá trị của b" + a);
//
//        int ketQua = (a++) - (--b) + (--a) - (a--) + (b--) - (b--);
        // 5 - (--b) + (--a) - (a--) + (b--) - (b--); => a = 6 , b = 5
        // 5 - 4 + (--a) - (a--) + (b--) - (b--); => a = 6 , b = 4
        // 5 - 4 + 5 - (a--) + (b--) - (b--); => a = 5 , b = 4
        // 5 - 4 + 5 - 5 + (b--) - (b--); => a = 5 , b = 4
        // 5 - 4 + 5 + 5 - (b--); a = 4, b = 3
        // 5 - 4 + 5 + 4 - 3 =>a = 4, b = 2
        // 2 => a = 4, b = 2
//        System.out.println("Giá trị của b" + a);
//        System.out.println("Giá trị của b" + b);
//        System.out.println("Kết quả biểu thức " + ketQua);

        //       3 : câu điều kiện if else
//            */
//        int a = 5;
//        if (a > 0) {
//            System.out.println("A lớn hơn 0");
//        }else{
//            System.out.println("A bé hoặc bằng 0");
//            }
//        int age = 18;
//        if (age >= 18){
//             System.out.println("lứa tuổi vị thành niên");
//        }else{
//             System.out.println("lứa tuổi dưới vị thành niên");
//        }
//         >= 18 : " lứa tuổi vị thành niên "
//         > 18 : " lứa tuổi dưới vị thành niên"

//        */
//        int a = 5;
//        int b = 5;

//        if (a - b > 0){
//            System.out.println("1");
//        }else {
//            System.out.println("0");
//        }else if (a - b < 0){
//            System.out.println("-1");
//    }

//        */
//    int number1 = 1;
//    int number2 = 1;
//
//    number1 lớn hơn 0 và number1 bằng number2
//    if (number1 > 0 && number1 == number2){
//        System.out.println("number1 khác 0 và bằng number2");
//    }else{
//        System.out.println("không thỏa");
//    }
        int number1 = 0;
        int number2 = 0;

        if (number1 > 0 && number1 == number2){
            System.out.println("number1 lon hon 0 va bang number2");
        }else{
            System.out.println("khong thoa");
        }
    }
}
