# ANet UI screenshots

Produced by the repository's own browser drives (`tests/node-source-palette`, `tests/chat-fork-entry`)
against a fresh `expo export -p web` of `main` on 2026-11-10.

All data inside the screenshots is **synthetic fixture data** (示例-A / 示例-B / demo-a …). No real
account, node, session or path appears in them.

| file | what it shows |
|---|---|
| `0.2.499/desktop-list.png` | 新建节点「节点来源」：按项目分组的已有会话 + 同项目下的「新建空会话 / 接入已有会话」 |
| `0.2.499/desktop-selected.png` | 选好之后：确认行、名字输入、提交可用 |
| `0.2.499/desktop-clone.png` | 复制节点：源行、预填名字、工作目录（新的空目录 / 共用源目录）、复制会话开关 |
| `0.2.499/desktop-open.png` | Fork 当前节点：只列可 fork 的受管会话，当前项唯一 ✓ |
| `0.2.499/phone-list.png` | 手机 390×844：同一浮层，列表在卡内滚动，确认区不被键盘挡住 |
| `0.2.499/phone-selected.png` | 手机：选好之后确认区仍在视口内 |
| `0.2.499/desktop-search.png` | 搜索过滤（项目名 / 会话名 / 路径） |
| `0.2.499/desktop-error.png` | Hub 真实错误码可见，不静默 fallback |

Why this repo exists: the drives assert the shape, and a screenshot is the fastest way to show a
person what the shape is without asking them to click through a desktop build first.
