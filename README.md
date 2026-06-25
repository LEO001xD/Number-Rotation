# 🔄 Number Rotation
 
จงเขียนโปรแกรมสร้างรูปแบบตัวเลขแบบหมุน (Number Rotation) โดยรับจำนวนเต็มบวก `n`
 
ในแต่ละแถว ตัวเลขจะเริ่มจากเลขประจำแถวนั้น และเพิ่มขึ้นทีละ 1 จนครบ `n` ตัว
หากตัวเลขมากกว่า `n` ให้กลับไปเริ่มที่ `1`
 
---
 
## 📥 Input(s)
 
- `n` มีค่าเป็นจำนวนเต็มบวก
- หาก Input ไม่ถูกต้องให้ return `"Error"`
## 📤 Output(s)
 
- return ในรูปแบบของ `string`
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
