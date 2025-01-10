## 上马自动签到 [![Run Auto Sign](https://github.com/zhaohongxuan/shangma_auto_sign/actions/workflows/auto-sign.yaml/badge.svg)](https://github.com/zhaohongxuan/shangma_auto_sign/actions/workflows/auto-sign.yaml)

### 基于 Node.js + GitHub Action 实现上海马拉松官网每日签到

### Use 使用

1. Fork本项目（顺手点Star以示鼓励～🥳）
2. 在Repo的Setting页面，添加名为上马官网的用户名：`SM_USERNAME`和密码：`SM_PASSWORD`的Secret 
3. 手动测试运行
<img width="1444" alt="image" src="https://github.com/zhaohongxuan/shangma_auto_sign/assets/8613196/695683c9-fbc2-4cab-9ef8-41e2ddf59b78">
在控制台应该能看到 `签到成功/请勿重复签到` 的提示
<img width="990" alt="image" src="https://github.com/zhaohongxuan/shangma_auto_sign/assets/8613196/399e89f7-2ad6-486e-9e67-8953564ec528">


### 关于Job执行时间
签到Job执行时间是**UTC时间0点**，也就是**北京时间8点**执行，**不过由于GitHub的负载比较重**，真正签到时间可能延后一段时间，一般是几十分钟，这个延迟时间取决于GitHub Action的负载。

### 申明
- 本项目仅做学习交流, 禁止用于各种非法途径
- Auto Sign-in run successful on Fri Sep 13 06:46:04 UTC 2024
- Auto Sign-in run successful on Sat Sep 14 00:42:53 UTC 2024
- Auto Sign-in run successful on Sun Sep 15 00:49:58 UTC 2024
- Auto Sign-in run successful on Mon Sep 16 00:46:55 UTC 2024
- Auto Sign-in run successful on Tue Sep 17 00:36:34 UTC 2024
- Auto Sign-in run successful on Wed Sep 18 00:43:25 UTC 2024
- Auto Sign-in run successful on Thu Sep 19 00:44:07 UTC 2024
- Auto Sign-in run successful on Fri Sep 20 00:44:01 UTC 2024
- Auto Sign-in run successful on Sat Sep 21 00:43:29 UTC 2024
- Auto Sign-in run successful on Sun Sep 22 00:50:09 UTC 2024
- Auto Sign-in run successful on Mon Sep 23 00:46:06 UTC 2024
- Auto Sign-in run successful on Tue Sep 24 00:45:36 UTC 2024
- Auto Sign-in run successful on Wed Sep 25 00:46:27 UTC 2024
- Auto Sign-in run successful on Thu Sep 26 00:45:11 UTC 2024
- Auto Sign-in run successful on Fri Sep 27 00:45:37 UTC 2024
- Auto Sign-in run successful on Sat Sep 28 00:45:00 UTC 2024
- Auto Sign-in run successful on Sun Sep 29 00:51:09 UTC 2024
- Auto Sign-in run successful on Mon Sep 30 00:48:00 UTC 2024
- Auto Sign-in run successful on Tue Oct  1 00:51:42 UTC 2024
- Auto Sign-in run successful on Wed Oct  2 00:45:32 UTC 2024
- Auto Sign-in run successful on Thu Oct  3 00:45:38 UTC 2024
- Auto Sign-in run successful on Fri Oct  4 00:45:47 UTC 2024
- Auto Sign-in run successful on Sat Oct  5 00:44:59 UTC 2024
- Auto Sign-in run successful on Sun Oct  6 00:50:47 UTC 2024
- Auto Sign-in run successful on Mon Oct  7 00:48:17 UTC 2024
- Auto Sign-in run successful on Tue Oct  8 00:45:24 UTC 2024
- Auto Sign-in run successful on Wed Oct  9 00:45:16 UTC 2024
- Auto Sign-in run successful on Thu Oct 10 00:45:23 UTC 2024
- Auto Sign-in run successful on Fri Oct 11 00:45:27 UTC 2024
- Auto Sign-in run successful on Sat Oct 12 00:44:23 UTC 2024
- Auto Sign-in run successful on Sun Oct 13 00:50:23 UTC 2024
- Auto Sign-in run successful on Mon Oct 14 00:48:08 UTC 2024
- Auto Sign-in run successful on Tue Oct 15 00:46:30 UTC 2024
- Auto Sign-in run successful on Wed Oct 16 00:46:16 UTC 2024
- Auto Sign-in run successful on Thu Oct 17 00:45:51 UTC 2024
- Auto Sign-in run successful on Fri Oct 18 00:45:50 UTC 2024
- Auto Sign-in run successful on Sat Oct 19 00:45:12 UTC 2024
- Auto Sign-in run successful on Sun Oct 20 00:51:33 UTC 2024
- Auto Sign-in run successful on Mon Oct 21 00:48:29 UTC 2024
- Auto Sign-in run successful on Tue Oct 22 00:46:41 UTC 2024
- Auto Sign-in run successful on Wed Oct 23 00:50:42 UTC 2024
- Auto Sign-in run successful on Thu Oct 24 00:46:21 UTC 2024
- Auto Sign-in run successful on Fri Oct 25 00:46:49 UTC 2024
- Auto Sign-in run successful on Sat Oct 26 00:44:59 UTC 2024
- Auto Sign-in run successful on Sun Oct 27 00:51:07 UTC 2024
- Auto Sign-in run successful on Mon Oct 28 00:49:39 UTC 2024
- Auto Sign-in run successful on Tue Oct 29 00:48:00 UTC 2024
- Auto Sign-in run successful on Wed Oct 30 00:46:47 UTC 2024
- Auto Sign-in run successful on Thu Oct 31 00:47:10 UTC 2024
- Auto Sign-in run successful on Fri Nov  1 00:51:57 UTC 2024
- Auto Sign-in run successful on Sat Nov  2 00:45:22 UTC 2024
- Auto Sign-in run successful on Sun Nov  3 00:51:16 UTC 2024
- Auto Sign-in run successful on Mon Nov  4 00:49:00 UTC 2024
- Auto Sign-in run successful on Tue Nov  5 00:45:05 UTC 2024
- Auto Sign-in run successful on Wed Nov  6 00:45:18 UTC 2024
- Auto Sign-in run successful on Thu Nov  7 00:45:18 UTC 2024
- Auto Sign-in run successful on Fri Nov  8 00:45:05 UTC 2024
- Auto Sign-in run successful on Sat Nov  9 00:44:12 UTC 2024
- Auto Sign-in run successful on Sun Nov 10 00:49:41 UTC 2024
- Auto Sign-in run successful on Mon Nov 11 00:47:06 UTC 2024
- Auto Sign-in run successful on Tue Nov 12 00:44:48 UTC 2024
- Auto Sign-in run successful on Wed Nov 13 00:45:48 UTC 2024
- Auto Sign-in run successful on Thu Nov 14 00:45:57 UTC 2024
- Auto Sign-in run successful on Fri Nov 15 00:49:53 UTC 2024
- Auto Sign-in run successful on Sat Nov 16 00:48:22 UTC 2024
- Auto Sign-in run successful on Sun Nov 17 00:53:01 UTC 2024
- Auto Sign-in run successful on Mon Nov 18 00:51:31 UTC 2024
- Auto Sign-in run successful on Tue Nov 19 00:49:53 UTC 2024
- Auto Sign-in run successful on Wed Nov 20 00:48:52 UTC 2024
- Auto Sign-in run successful on Wed Nov 20 06:38:34 UTC 2024
- Auto Sign-in run successful on Thu Nov 21 01:17:37 UTC 2024
- Auto Sign-in run successful on Fri Nov 22 01:18:39 UTC 2024
- Auto Sign-in run successful on Sat Nov 23 01:16:21 UTC 2024
- Auto Sign-in run successful on Sun Nov 24 01:23:33 UTC 2024
- Auto Sign-in run successful on Mon Nov 25 01:19:41 UTC 2024
- Auto Sign-in run successful on Tue Nov 26 01:18:43 UTC 2024
- Auto Sign-in run successful on Wed Nov 27 01:20:20 UTC 2024
- Auto Sign-in run successful on Thu Nov 28 01:19:47 UTC 2024
- Auto Sign-in run successful on Fri Nov 29 01:19:41 UTC 2024
- Auto Sign-in run successful on Sat Nov 30 01:17:51 UTC 2024
- Auto Sign-in run successful on Sun Dec  1 01:39:23 UTC 2024
- Auto Sign-in run successful on Mon Dec  2 01:22:18 UTC 2024
- Auto Sign-in run successful on Tue Dec  3 01:21:10 UTC 2024
- Auto Sign-in run successful on Wed Dec  4 01:21:17 UTC 2024
- Auto Sign-in run successful on Thu Dec  5 01:21:17 UTC 2024
- Auto Sign-in run successful on Fri Dec  6 01:20:30 UTC 2024
- Auto Sign-in run successful on Sat Dec  7 01:19:59 UTC 2024
- Auto Sign-in run successful on Sun Dec  8 01:26:35 UTC 2024
- Auto Sign-in run successful on Mon Dec  9 01:23:15 UTC 2024
- Auto Sign-in run successful on Tue Dec 10 01:22:19 UTC 2024
- Auto Sign-in run successful on Wed Dec 11 01:21:12 UTC 2024
- Auto Sign-in run successful on Thu Dec 12 01:20:43 UTC 2024
- Auto Sign-in run successful on Fri Dec 13 01:22:06 UTC 2024
- Auto Sign-in run successful on Sat Dec 14 01:18:41 UTC 2024
- Auto Sign-in run successful on Sun Dec 15 01:26:37 UTC 2024
- Auto Sign-in run successful on Mon Dec 16 01:23:44 UTC 2024
- Auto Sign-in run successful on Tue Dec 17 01:20:55 UTC 2024
- Auto Sign-in run successful on Wed Dec 18 01:17:59 UTC 2024
- Auto Sign-in run successful on Thu Dec 19 01:18:50 UTC 2024
- Auto Sign-in run successful on Fri Dec 20 01:15:04 UTC 2024
- Auto Sign-in run successful on Sat Dec 21 01:13:33 UTC 2024
- Auto Sign-in run successful on Sun Dec 22 01:20:20 UTC 2024
- Auto Sign-in run successful on Mon Dec 23 01:16:06 UTC 2024
- Auto Sign-in run successful on Tue Dec 24 01:14:35 UTC 2024
- Auto Sign-in run successful on Wed Dec 25 01:13:45 UTC 2024
- Auto Sign-in run successful on Thu Dec 26 01:14:03 UTC 2024
- Auto Sign-in run successful on Fri Dec 27 01:14:31 UTC 2024
- Auto Sign-in run successful on Sat Dec 28 01:13:00 UTC 2024
- Auto Sign-in run successful on Sun Dec 29 01:21:11 UTC 2024
- Auto Sign-in run successful on Mon Dec 30 01:16:45 UTC 2024
- Auto Sign-in run successful on Tue Dec 31 01:14:12 UTC 2024
- Auto Sign-in run successful on Wed Jan  1 01:20:40 UTC 2025
- Auto Sign-in run successful on Thu Jan  2 01:13:47 UTC 2025
- Auto Sign-in run successful on Fri Jan  3 01:14:50 UTC 2025
- Auto Sign-in run successful on Sat Jan  4 01:13:15 UTC 2025
- Auto Sign-in run successful on Sun Jan  5 01:20:23 UTC 2025
- Auto Sign-in run successful on Mon Jan  6 01:17:56 UTC 2025
- Auto Sign-in run successful on Tue Jan  7 01:15:06 UTC 2025
- Auto Sign-in run successful on Wed Jan  8 01:15:07 UTC 2025
- Auto Sign-in run successful on Thu Jan  9 01:14:29 UTC 2025
- Auto Sign-in run successful on Fri Jan 10 01:16:43 UTC 2025
