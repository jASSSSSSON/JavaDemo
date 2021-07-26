# 此项目为基础Java功能测试项目

## section_a

### 请获取控制台输入内容并展示

```java
public class Demo {
    private static String text;

    public static void main(String[] args) {
        input();
        show();
    }

    public static void input() {

    }

    public static void show() {

    }
}
```

## Section B

### 请将Section A中的功能抽象为工具类，并设计一个方法，要求：

- 一共进行三次输入
- 第一次输入计算元素a
- 第二次输入计算方法x,如`+`、`-`、`*`、`/`
- 第三次输入计算元素b
- 输出相应计算结果

```java
public class Demo {
    public static void main(String[] args) {
        Compute.doCompute();
    }
}
```

## Section C

### 请将Section A/B中的功能抽象为工具类，并设计一个方法，要求：

- 程序启动为菜单页，选着录入数据、查询数据和退出
- 若为录入数据，则输入人员信息，编号，姓名，性别，年龄，进行保存
- 若为查询数据，则输入人员编号，显示已录入的信息，若未录入则进行相应提示
- 若用户不退出，则一直循环功能

```java
public class Demo {
    public static void main(String[] args) {
        HumanProfileSystem.run();
    }
}
```