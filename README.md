# 🎯The optimal AI Aimbot for CS2

**Works on any computer,  just download and run!**

🌐 **Download Page**: [https://optshot.com](https://optshot.com)



## 🚀  Basic Usage

1. Launch the game in either **Fullscreen Windowed** mode or **Windowed** mode:

   > If you choose 'Windowed' mode, please ensure the window remains centered on your screen.

   ![image-20240310150844554](./assets/image-20240310150844554.png)

2. Press the "Start" button or use the hotkey "**F5**".



## ⚙️ Advanced Setting

<img src="./assets/image-20240310160626406.png" alt="image-20240310160626406" style="zoom:67%;" />

### 🖱️ Mouse Calibration

🏃 **Movement Factor**

> The higher this value, the greater the distance the mouse will move.

Due to differences in mouse DPI, game resolution, and in-game Mouse Sensitivity settings, it's necessary to calibrate the mouse movement range to ensure accurate targeting.

Procedure: 

1）Open a practice map and keep the bot stationary. 

2）Slightly move the mouse pointer away from the bot.

3）Press **F6** to execute a single "Capture- Detection - Mouse Movement" precedure.  Adjust this value until a single detection accurately aligns with the character.



⏱️ **Rest Time Factor**

>  Increasing this factor extends the waiting time.

After mouse movement, the screen doesn't immediately change. Therefore, it's necessary to wait for a period before continuing detection; otherwise, premature detection might lead to incorrect mouse movement and significant drift. Typically, a value of 0.3 is appropriate.



### 🚀 Nvidia CUDA Acceleration

By default, the AI detection algorithm runs on the CPU. For Nvidia graphics cards, you can utilize CUDA to accelerate detection speed, usually resulting in a 100% to 300% speed boost.

However, be aware that if your GPU is already exhausted by the game, the detection speed might be slower than CPU. In such cases, you can:

1. Limit CS's maximum frame rate via console command `fps_max 60`.
2. Lower the game's graphics quality or resolution.



## ❔Frequently Asked Questions

**1. Does it support games other than CS2?**

In theory, yes, but the software is not optimized for these games.



**2. How it works?**

The software captures a 640x640 area at the screen center, employs AI object detection (Yolo-V8) to locate characters within it, and then controls the mouse for aiming.

![image-20240310160908513](./assets/image-20240310160908513.png)

> [!WARNING]
> This software is intended for academic purposes only. **Do not use it in live action.** We are not responsible if you get banned!