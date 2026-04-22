## 示例
### 1. 为9名员工制定为期7天的排班表，需满足以下限制条件：
- 每天分为三个8小时班次。每个班次所需的员工人数不同。
  - A班：00:00-08:00（需要1名员工）
  - B班：08:00-16:00（需要3名员工）
  - C班：16:00-24:00（需要3名员工）
- 每位员工每天最多只能工作一个班次。
- 每个员工的班次数量均等。
- 每位员工在7天内至少休息一天。

软件解决方案:
![image](https://user-images.githubusercontent.com/84350533/195989630-e41d4abd-19a0-4b4e-9808-cd04854909ce.png)
在此轮班安排中，4名员工每周工作48小时，5名员工每周工作40小时。每位员工的轮班时间至少间隔16小时。

### 2. 为 10 名员工制定 7 天的工作计划，并遵守示例 1 中列出的限制条件。
软件解决方案:
![image](https://user-images.githubusercontent.com/84350533/194903255-47e8b605-31fc-4276-b548-bc78046de343.png)
在此轮班安排中，9名员工每周工作40小时，1名员工每周工作32小时。每位员工在7天的周期内至少休息两天，且连续两天轮班类型不同。每位员工的轮班间隔至少为24小时。

### 3. Creating a schedule for a hospital department over a 7-day period, subject to the following constraints:
- Each day is divided into three 8-hour shifts. Each shift type requires different number of employees on different level.
     - A-shift：23:30-07:30（1 Senior Nurse, 1 Nurse and 1 Assistant Nurse required）
     - B-sfhit：07:30-15:30（1 Senior Nurse, 3 Nurses and 2 Assistant Nurses required）
     - C-shift：15:30-23:30（1 Senior Nurse, 2 Nurses and 1 Assistant Nurse required）
- Every day, no nurse works more than one shift.
- No nurse works more than 40 hours in 7-day period.
- Number of shifts are evenly assigned to nurses.
- Each nurse has at least one day off in the 7-day period.
- Nurse01 and Nurse02 do not work on the same shift simultaneously.
- Arrange AssistantNurse1 to work with SeniorNurse1 simultaneously as much as possible

Software solution:
![image](https://user-images.githubusercontent.com/84350533/215545886-3eb0e683-f04e-432d-93f5-15e03530c239.png)
In this shift schedule, the shifts assigned to each employee are different on two consecutive days, and they are spaced by at least 24 hours.
