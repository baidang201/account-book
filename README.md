# 记账应用 (Account Book)

Next.js + Prisma 实战教学项目

## 课前准备

### 1. 配置数据库连接

1. 注册 [Neon](https://neon.tech) 免费账号
2. 创建项目，获取 Connection string
3. "cp env.example .env", 编辑 `.env` 文件，替换 `DATABASE_URL` 为你的连接串

### 2. 安装依赖

```bash
npm install
```

### 3. 生成 Prisma 客户端

```bash
npx prisma generate
```

## 常用命令

| 命令 | 说明 |
|------|------|
| `npx prisma studio` | 打开可视化数据库管理界面 |
| `npx prisma migrate dev` | 创建数据库迁移 |
| `npx prisma db push` | 将 Schema 同步到数据库 |
| `npx prisma generate` | 生成 Prisma 客户端 |

## 课程学习路径

1. **选型分析**：使用「5问选型法」确定数据库类型
2. **模型设计**：用自然语言描述需求，AI 生成 Prisma Schema
3. **数据同步**：执行迁移，将模型同步到 Neon 数据库
4. **增删改查**：通过 Prisma Studio 或 API 操作数据
5. **报错排查**：掌握常见错误的解决方法
