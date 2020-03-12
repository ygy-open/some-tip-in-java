### 最近写算法发现栈有这么个问题

```java
public static void main(String[] args){
        Stack<Boolean> nums = new Stack<>();
        nums.push(false);
        System.out.println(false && nums.pop());
        System.out.println(nums.pop());
    }
// 运行结果
false
false
    
public static void main(String[] args){
        Stack<Boolean> nums = new Stack<>();
        nums.push(false);
        System.out.println(nums.pop());
        System.out.println(nums.pop());
    }
// 运行结果
报错
```

