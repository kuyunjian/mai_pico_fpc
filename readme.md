![本branch的更改](https://github.com/user-attachments/assets/69f36717-a962-4df2-b20e-c53f4f2c931d)

- **Gerber_IO_Board_v3.1_2024-12-14.zip**（IO板）：使用嘉立创EDA制作，可以通过EDA券进行打样。
- **Gerber_Button_Board_2024-12-14.zip**（四个功能键板）：使用嘉立创EDA制作，可以通过EDA券进行打样。
- **Gerber_IO_Touch_Board_v3.0_5_2024-12-14.zip**（触摸板）：使用嘉立创EDA制作，可以通过EDA券进行打样。
- **fpc-button.zip**（按键板）：使用KiCad制作，在嘉立创下单助手中仅能用通用券进行打样。

---
分体板共四个pcb文件，均在 [JOZA-ORANGE](https://github.com/JOZA-ORANGE/mai_pico) 的基础上改进而来

## 更新说明：IO板
-增加了树莓派Pico对应的引脚丝印。  
  - 一侧仅焊接带标点的焊盘。  
  - 另一侧需要全部焊接。

- **读卡器焊盘**：更改为XH2.54接口。

- **按键PCB连接**：更改为12针0.5mm间距的FPC接口。

### 连接方式：
- IO板与按键PCB之间通过**反向连接**的FPC排线连接。
- 其他FPC排线连接均为**同向**连接。
- 按键板之间使用**40mm**的FPC排线进行连接。

---


## 螺丝孔
间距见图
IO板有两个4.1mm的螺丝孔，四个2mm的螺丝孔

![114e6dcc4adc110a4fa8c1913fc8a64f](https://github.com/user-attachments/assets/6a7bf7bb-9047-48ae-b75d-6054797783c1)

  - 暂时没有固定方案，建议使用热熔胶将其固定在读卡器对面。

触摸板有两个4.1mm的螺丝孔，封装宽度小于6mm，可以塞入欧标1515铝型材槽（6.1mm）

![image](https://github.com/user-attachments/assets/cff2464b-36fc-49d4-a9ba-9459b982fc04)

四个按键板有两个4.1mm的螺丝孔，受限于fpc座，无法将其放入槽内

![409c412c33483108aa20477443c17d64](https://github.com/user-attachments/assets/2e6d43b2-4a5c-44df-93f2-915c0af7c65e)


按键板展示

![image](https://github.com/user-attachments/assets/516e0fd7-96c2-4611-89fd-5537afec7769)





---

## 关于该项目：

- 按键PCB与IO板通过12针FPC排线连接。
- 由于技术限制，PCB源文件未能与原理图建立连接。

### 未来更新内容：
- **更宽的按键帽**。
- 适配**分体主板**的**外壳**设计。
- 提供**组装建议**，方便安装。
- 其他**改进与优化**。

敬请期待更多精彩更新！


部分材料：
注意：
![image](https://github.com/user-attachments/assets/f9b46f30-7d6a-469e-85a8-549d63314aa9)


---
---
---
---
---
# Touch Panel and Function Key Boards

The **touch panel** and **four function key boards** can be found in **[JOZA-ORANGE's GitHub branch](https://github.com/JOZA-ORANGE/mai_pico)**.

## IO Board Modifications
The IO board includes the following updates:  
- Added **pin silkscreen** corresponding to the Raspberry Pi Pico.  
  - Only solder pads **with markers** on one side.  
  - Solder **all pads** on the other side.  
- Changed the **card reader pad** to an **XH2.54 connector**.  
- Updated the connection to the button PCB to a **12-pin 0.5mm pitch FPC connector**.  

### Connection Details
- The FPC cable between the IO board and the button PCB is **reversed**.  
- All other FPC connections are **same-direction**.  
- Button boards are connected using **40mm FPC cables**.

Visit the branch for more details and updates.

# About This Project

In this branch's shared link:  
- The **button PCB** is connected via a **12-pin FPC cable**.  
- **Technical limitations** prevent the PCB source file from linking to the schematic.  

## Future Updates
Potential updates may include:  
- **Wider button caps**.  
- **Enclosures** compatible with split mainboards.  
- **Assembly tips** for easier setup.  
- Additional **improvements and enhancements**.

Stay tuned for more exciting developments!



