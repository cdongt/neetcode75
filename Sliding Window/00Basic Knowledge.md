# 📘滑动窗口学习笔记

<br>


## 🧠 基本概念和用途

- **基本概念：** 滑动窗口是一种经典的算法技巧，用于解决数组或字符串中的**子数组**或**子串**问题。
- **应用场景：** 滑动窗口在需要在线性时间内解决**连续子序列**问题时非常有用，如最大/最小子数组和、字符串最长无重复子串等。

<br>
<br>
<br>

## 🌐 与其他知识联系 [待补充]

- **与其他知识的联系：** 滑动窗口常与双指针、动态规划等算法技巧结合，用于优化问题求解。

<br>
<br>
<br>

## 💡 算法/数据结构的核心思想

- **核心思想：** 滑动窗口维护一个窗口，通过滑动窗口的起始和结束位置来处理问题。窗口通常是一个子数组或子串，起始和结束位置不断向右移动。
- **关键步骤：** 
  1. 初始化窗口：设置起始和结束指针，初始化窗口状态。
  2. 移动右边界：增大窗口，将右边界右移并更新窗口状态。
  3. 检查条件：根据问题要求，判断当前窗口是否满足条件,**满足条件才更新结果**。
  4. 移动左边界：缩小窗口，将左边界右移并更新窗口状态。
  5. 重复步骤2-4，直到右边界到达数组末尾。


- **代码模板：**
  ```python
  def slidingWindow(nums):
      left = 0
      right = 0
      while right < len(nums):
          # 移动右边界，更新窗口状态
          # 检查条件是否满足，如果满足则更新结果
          while condition:  # 根据问题要求修改条件
              # 更新结果
              # 移动左边界，更新窗口状态
          # 移动左边界，更新窗口状态

<br>
<br>
<br>

## 🎯 重点关注内容

- **实现细节：** 在具体实现时，需要根据问题的特点设计窗口的移动和条件判断。掌握如何维护窗口的状态。
- **边界情况：** 需要特别注意窗口的左右边界的越界情况，确保算法正确性。
- **复杂度分析：** 滑动窗口通常在 O(N) 时间内完成，空间复杂度为 O(1)。

<br>
<br>
<br>

## 🚀 优化和变种

- **优化方法：** 有时可以通过预处理、缓存等方式优化滑动窗口的求解过程，提高算法效率。
- **变种问题：** 滑动窗口的应用不仅限于连续子数组问题，还可以扩展到其他问题领域。

<br>
<br>
<br>

## 🧩 问题分类

- **问题类型：** 滑动窗口适用于连续子序列和子串问题，如最大子数组和、字符串最长无重复子串等。

<br>
<br>
<br>



