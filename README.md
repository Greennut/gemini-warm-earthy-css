

# Gemini - Warm Earthy & Slate Rose Edition

[![Install directly with Stylus](https://img.shields.io/badge/Install%20with-Stylus-1185fe?style=for-the-badge&logo=stylus)](https://raw.githubusercontent.com/Greennut/gemini-warm-earthy-theme/main/gemini-warm-earthy.user.css)

A warm, eye-pleasing theme for `gemini.google.com` featuring an earthy canvas (`#fbf9f5`), 32px rounded white cards, and a refined slate rose code syntax palette.

针对 `gemini.google.com` 的暖大地色与玫瑰灰配色用户样式。采用米褐底色（`#fbf9f5`）、32px 大圆角白底卡片容器与灰粉语法高亮。

---

## Features / 设计特性

* **Warm Canvas**: Replaces harsh white/blue-gray with a calming parchment fill (`#fbf9f5`).
* **Card Containers**: 32px rounded borders with subtle line dividers (`#e2ded8` / `#ede8e1`).
* **Slate Rose Palette**: Brick red keywords (`#a33d2c`), slate rose declarations (`#d05a6e`), moss green strings (`#6c8b35`), and gold constants (`#b8860b`).
* **Monospace Typography**: Scaled to 16px with anti-aliased monospace stack.

---

## Color Palette & Design Tokens / 色盘与设计变量

This theme uses semantic CSS variables in `:root`. You can customize them directly to adjust tones.
本主题在 `:root` 中定义了语义化 CSS 变量，可根据个人偏好直接调整各色阶。

### 1. Canvas & Containers / 画布与容器

| Token (CSS Variable) | Hex Value |  Role / 作用域说明 |
| :--- | :--- | :--- |
| `--gem-warm-canvas` | `#FBF9F5` |  全局羊皮纸暖白底色（替换原生冷白/灰） |
| `--gem-warm-card-bg` | `#FFFFFF` | 代码块内底、纯白卡片背景 |
| `--gem-warm-border` | `#E2DED8` | 代码块外框 1px 细线（暖灰） |
| `--gem-warm-divider` | `#EDE8E1` | 代码块顶栏分割线（低饱和分割） |

---

### 2. Typography & Controls / 文本与控制项

| Token (CSS Variable) | Hex Value | Role / 作用域说明 |
| :--- | :--- |  :--- |
| `--gem-warm-text-main` | `#3A3A3A` | 代码正文字体主色（炭黑，非死黑） |
| `--gem-warm-text-muted` | `#6E685E` |  代码块语言标签、复制按钮图标与文字 |
| `--gem-warm-comment` | `#9E9A92` | 代码注释文本（斜体、低对比暖灰） |

---

### 3. Syntax Highlighting / 语法高亮色阶 (Slate Rose & Earthy)

| Token (CSS Variable) | Hex Value  | Highlight Scope / 高亮元素类型 |
| :--- | :--- | :--- |
| `--gem-warm-keyword` | `#A33D2C` |  核心关键字、标签名 (`keyword`, `tag`, `selector-tag`) |
| `--gem-warm-rose-accent` | `#D05A6E` |   函数名、类名、类型声明、元数据 (`title`, `function`, `type`, `meta`) |
| `--gem-warm-attribute` | `#4B789B` |  属性名、选择器属性 (`attr`, `attribute`, `property`) |
| `--gem-warm-string` | `#6C8B35` | 字符串字面量 (`string`) |
| `--gem-warm-number` | `#B8860B` | 数值、布尔常量 (`number`, `literal`) |
| `--gem-warm-brown-dark` | `#8C5338` | 伪类、ID 选择器 (`selector-pseudo`, `selector-id`) |
| `--gem-warm-brown-light` | `#A1662F` | 内置对象、原生 API (`built_in`) |
| `--gem-warm-variable` | `#4A4644` | 局部变量、参数名 (`variable`, `params`) |

---
## Installation / 安装使用

### Option 1: One-Click Install (Recommended / 推荐)
Click the badge above if you have the **Stylus** browser extension installed.

若已安装 **Stylus** 扩展，直接点击页面顶部蓝色的 **Install with Stylus** 徽标即可自动触发安装。

### Option 2: Manual / 手动安装
1. Install **Stylus** on your browser.
2. Create a new style and paste the content of `gemini-warm-earthy.user.css`.
3. Set domain to `gemini.google.com`.


## Preview

<!-- Replace the placeholder paths with your actual screenshots -->

| Overview | Code Block & Input Interaction |
| :---: | :---: |
| <img src="https://github.com/user-attachments/assets/f1122a5d-b13f-45bd-9269-2a8dc2af4540" width="400" /> | <img src="https://github.com/user-attachments/assets/c3b4cb70-9b05-410f-8ca4-c0e12e92181c" width="400" /> | |

---
