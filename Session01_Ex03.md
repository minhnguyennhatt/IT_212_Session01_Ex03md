## Prompt mới do tôi thiết kế

Bạn là lập trình viên Java có nhiệm vụ kiểm tra lỗi logic nghiệp vụ trong hàm tính VAT 10% dưới đây. Hãy phân tích rủi ro khi `amount <= 0`, sau đó chỉnh sửa code để chặn trường hợp hóa đơn có giá trị âm hoặc bằng 0, vì hóa đơn hợp lệ phải có giá trị lớn hơn 0.

## Đoạn code Java đã được AI sửa đổi

```java
public class TaxCalculator {

    public static double calculateVAT(double amount) {
        if (amount <= 0) {
            throw new IllegalArgumentException("Amount must be greater than 0");
        }

        return amount * 0.1;
    }
}
```
