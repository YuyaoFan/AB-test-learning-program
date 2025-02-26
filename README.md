# ABtest-learning-program

该项目笔记使用ab测试方法模拟了某网站采用黑色页面替代白色页面对用户活跃性和转化率的影响。

详情请见Jupyter notebook。

使用tableau对该数据集中的各项数据指标进行刻画如下：

---

![仪表板 1](https://github.com/user-attachments/assets/72092f35-b407-4135-8d45-5b28251af4e6)

### **图表 1：A/B测试表现汇总**
该图表为A/B测试结果的概述，展示了页面浏览量、停留时间的占比以及箱线图进行进一步的可视化展示。

- **页面浏览量与停留时间比较**：A组和B组在页面浏览量和停留时间上的占比几乎相等，存在一些微小的差异。
- **转化率**：B组的转化率（71.96%）明显高于A组（28.04%）。
- **结论**：虽然A组与B组在页面浏览量和停留时间上的差异较小，但B组的转化率明显更高，表明治疗变体在提高转化行为方面表现更好。

---

![设备与活跃性](https://github.com/user-attachments/assets/91a5590c-61c8-4975-9095-eafc5a44d32c)

### **图表 2：设备与用户活跃度对用户参与度的影响**
该图表展示了设备类型和用户活跃度对平均停留时间和页面浏览量的影响。

- **设备使用情况**：**移动设备**用户在各个活跃度等级下的停留时间和页面浏览量均高于**桌面设备**用户。
- **活跃度等级**：活跃度较高的用户（如“非常活跃”和“活跃”级别）在页面停留时间和浏览量上表现更好。
- **转化率**：活跃用户的转化率普遍较高，不论是使用移动设备还是桌面设备。在“非常活跃”用户中，转化率也较为显著。
- **结论**：移动设备用户尤其是活跃用户的参与度较高，且表现出更强的转化率。


---

![地理位置](https://github.com/user-attachments/assets/6b417895-b7a8-4285-a612-ad31f45b2e57)

### **图表 3：不同地理位置A/B组转化率与用户参与度差异**
该图表展示了在不同地理位置下，A组与B组的转化率和用户参与度（页面浏览量和停留时间）的比较。

- **转化率**：实验组（B组）在多个位置的转化率较高，尤其是在**英格兰**和**苏格兰**，转化率差异最为显著。
- **页面浏览量与停留时间**：实验组（B组）在页面浏览量和停留时间上也普遍高于对照组（A组），这表明实验组的用户参与度更高。
- **结论**：在大多数地理位置下，实验组的转化率和用户参与度表现更优，特别是在英格兰和苏格兰。
---

通过这些分析可以看出，实验组（B组）在多个维度上表现更为优越，尤其是在转化率方面，特别是在英格兰地区，而在设备、平均页浏览时间方面两组表现差异不大。
