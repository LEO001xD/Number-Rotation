# 🔄 Number Rotation
 
จงเขียนโปรแกรมสร้างรูปแบบตัวเลขแบบหมุน (Number Rotation) โดยรับจำนวนเต็มบวก `n` แล้ว return ผลลัพธ์เป็น `string` ขนาด `n x n` 
โดยแถวที่ `i` จะประกอบด้วยตัวเลข `i, i+1, i+2, ...` จนครบ `n` ตัว และวนกลับมาที่ `1` เมื่อเกิน `n`
 
---
 
## 📥 Input(s)
 
- `n` มีค่าเป็นจำนวนเต็มบวก
- หาก Input ไม่ถูกต้องให้ return `"Error"`
## 📤 Output(s)
 
- return ในรูปแบบของ `string`
- ตัวเลขภายในแถวเดียวกันคั่นด้วย `" "` (space)
---
 
## ⚙️ Function
 
```python
def number_rotation(n):
 
    return ""
```
 
---
 
## 💡 Example
 
**Input**
```python
print(number_rotation(3))
```
**Output**
```
1 2 3
2 3 1
3 1 2
```
 
---
 
**Input**
```python
print(number_rotation(5))
```
**Output**
```
1 2 3 4 5
2 3 4 5 1
3 4 5 1 2
4 5 1 2 3
5 1 2 3 4
```
 
---
 
**Input**
```python
print(number_rotation(1))
```
**Output**
```
1
```
 
---
 
**Input**
```python
print(number_rotation(0))
```
**Output**
```
Error
```
 
---
