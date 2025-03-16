<p align="center">
  <img src="excourtFront\images\logo.png" width="200" alt="ExCourt Logo">
</p>

# 易场地 - 同济大学羽毛球场地交换系统 / ExCourt - Tongji University Badminton Court Exchange System

## 项目简介 / Project Overview

**易场地** 是一款专为 **同济大学师生** 设计的场地管理与预约系统。系统旨在优化校内羽毛球场地资源的利用率，提供便捷的场地预约、交换、拼场功能，并实现实时数据更新与高效管理。本仓库中的代码为2024年秋季软件工程项目的成果，仅为一个初始版本，功能并不完善，后续将在未来进行继续的更新迭代。  
**ExCourt** is a venue management and booking system designed specifically for **Tongji University students and faculty**. The system aims to optimize the utilization of on-campus badminton court resources, providing convenient venue booking, exchange, and team-building functionalities, while ensuring real-time data updates and efficient management. The code in this repository represents the result of a software engineering project for Fall 2024, and it is an initial version. The functionality is not complete, and further updates and iterations are planned for the future.

---

## 项目背景 / Project Background

- **预约场地现状**：现有系统中羽毛球预约需求激烈，但存在抢场难、资源浪费、信息不透明等问题。  
- **Current Venue Booking Issues**: The existing system faces high demand for badminton courts, but problems such as difficulty in securing venues, resource wastage, and lack of transparency persist.

- **用户需求**：  
  - 96% 的用户希望拥有一个能实现 **场地交换** 和 **组队** 的平台。  
  - 75% 的用户经常需要更换场地或组队。  

- **User Needs**:  
  - 96% of users want a platform that enables **venue exchange** and **team formation**.  
  - 75% of users frequently need to change venues or form teams.

系统通过解决这些痛点，为校内用户提供灵活、高效的场地管理方案。  
This system addresses these pain points by offering a flexible and efficient venue management solution for campus users.

---

## 功能介绍 / Features

1. **场地信息可视化 / Venue Information Visualization**  
   - 以图形化方式展示场地状态，支持筛选和加入空缺场地。  
   - Displays venue status in a graphical format, supporting filtering and joining available venues.

2. **场地资源再分配（换场）/ Venue Resource Redistribution (Venue Exchange)**  
   - 用户可发布换场需求，系统自动匹配并确认。  
   - Users can post venue exchange requests, and the system automatically matches and confirms them.

3. **组队功能 / Team Formation**  
   - 用户可发布拼场需求，自动更新场地状态并接受加入申请。  
   - Users can post team formation requests, and the venue status updates automatically to accept joining requests.

4. **场地资源转让 / Venue Resource Transfer**  
   - 用户可放弃场地并将其转让给其他用户。  
   - Users can relinquish their venue reservations and transfer them to other users.

5. **失物招领 / Lost and Found**  
   - 发布、查看失物信息，实现物品核销和申诉。  
   - Users can post and view lost items, manage item verification, and initiate claims.

6. **即时通讯 / Instant Messaging**  
   - 用户间实时交流，便于协调场地与拼场事宜。  
   - Real-time communication between users to coordinate venue usage and team formation.

7. **账户管理 / Account Management**  
   - 支持用户的个人信息与信誉分管理。  
   - Supports personal information and reputation management.

---

## 目标用户 / Target Users

- **普通用户 / Regular Users**：同济大学在读学生和老师。  
- **System Administrators**: Responsible for resource management and system maintenance.
- **系统管理员 / System Administrators**：负责资源管理和系统维护。  
- **客服人员 / Customer Support**：处理申诉与投诉。  
- **Customer Support**: Handles appeals, complaints, and disputes.

---

## 使用技术 / Technologies Used

- **前端 / Frontend**: 微信小程序 / WeChat Mini Program
- **后端 / Backend**: Flask框架 / Flask Framework
- **其他依赖 / Other Dependencies**: 同济大学现有的体育场馆预约系统与统一登录接口（开发中） / Tongji University's existing sports venue booking system and unified login interface. (Under development)

---

## 系统特点 / System Features

- **实时更新 / Real-time Updates**: 场地状态随时刷新，数据准确可靠。 / Venue status is updated constantly to ensure accurate and reliable data.
- **用户友好 / User-friendly**: 简洁美观的 UI 设计，便于操作。 / Simple and aesthetically pleasing UI design that is easy to use.
- **灵活性 / Flexibility**: 满足用户换场、拼场及组队的多样需求。 / Supports various user needs, such as venue exchanges, team formation, and flexible venue management.

---

## 文件结构 / File Structure

- `/excourtFront`: 前端代码（微信小程序）/ Frontend code (WeChat Mini Program)
- `/school`: 后端代码与API接口（模拟学校数据库）/ Backend code and API interfaces simulating the school database
- `/system`: 系统后端及数据库相关代码与API接口 / Backend and database-related code and API interfaces
- `/docs`: 文档及相关资源 / Documentation and related resources

---

## 安装与运行 / Installation and Running

1. 克隆代码仓库 / Clone the repository:
   ```bash
   git clone https://github.com/ShanghaineseImpact/ExCourt.git
   cd ExCourt
