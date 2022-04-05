# Rustの基本

```rust
//「 -> 」の後に戻り値の型を指定する
//引数の型は()の中で指定する。
fn five(f:i32) -> i32{
    //returnは使わないで戻り値をあらわす
    let x:i32=f+10;
    x
}
fn main() {
    let x=five(7);
    println!("the value of x ix {}",x);
}

```
