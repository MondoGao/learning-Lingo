# Basic

- lingo 不区分大小写
- 函数行顺序不影响结果
- 默认变量非负

## 函数

- @gin(variable_name): 定义整数变量
- @bin(vn): 定义 0，1 变量
- @free(vn): 定义可负变量
- @sum(集合(下标): 关于集合属性的表达式)

    @SUM(set(i):2a(i)+3b(i))
    
- @FOR(集合(下标)|被约束变量(如下标)#约束(如GT)#约束值:关于集合的属性的约束关系式)

## 集合

```lingo
model:
    sets:
            quarters/1..4/:DEM,RP,OP,INV;
    endsets
end
```