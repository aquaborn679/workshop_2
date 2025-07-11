# 🧪 Лабораторная работа №2

## 1.5

### ▸ Примитивы скатываются с горки:
- Dynamic Friction = 0  
- Static Friction = 0  
- Bounciness = 0  
- Friction Combine = Minimum  
- Bounce Combine = Average

### ▸ Примитивы отскакивают от горки:
- Dynamic Friction = 0.5  
- Static Friction = 0.5  
- Bounciness = 0.9  
- Friction Combine = Minimum  
- Bounce Combine = Average

---

## 1.6

### ▸ Скатывание (нет трения):
- Dynamic Friction = 0  
- Static Friction = 0  
- Bounciness = 0  
- Friction Combine = Minimum  
- Bounce Combine = Average

### ▸ Отскок (умеренное трение и высокая прыгучесть):
- Dynamic Friction = 0.5  
- Static Friction = 0.5  
- Bounciness = 0.9  
- Friction Combine = Minimum  
- Bounce Combine = Average

---

## 1.8

### ▸ Для первого звена:

![1_8_1](Images/1_8_1.png)

### ▸ Для остальных:

![1_8_2](Images/1_8_2.png)

---

## 1.11

- **Rigidbody:**  
  Для правильного поведения сцены оба объекта (цепь и коробка) должны иметь компоненты `Rigidbody` с включённым `UseGravity`.  
  Коробка должна падать под действием силы тяжести.  
  Цепь должна иметь `IsKinematic = false`, чтобы корректно взаимодействовать с другими объектами.

- **Collider:**  
  У цепи должен быть `MeshCollider`, чтобы взаимодействовать с коробкой.  
  У коробки также должен быть `MeshCollider` для реагирования на столкновения с цепью.

---

## 1.12

> В этой лабораторной работе я изучил, как работают коллайдеры в Unity  
> и как с их помощью можно создавать реалистичные взаимодействия объектов.  
> Например, я научился настраивать **трение** и **прыгучесть** материалов,  
> чтобы объекты правильно **скатывались с горки** или **отскакивали от неё**.  
> Эти знания полезны для создания игровых механик и симуляций,  
> где объекты взаимодействуют друг с другом при **столкновении** или **падении**.  
> Понимание физики и материалов позволяет делать игры **более динамичными и интересными**.
