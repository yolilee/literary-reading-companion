# Literary Reading Companion 📖

**An open-source, book-agnostic AI reading skill for B2–C1 English learners.**  
**Upload photos of English book pages → understand the passage → discuss one meaningful question → study challenging vocabulary in its original reading order, with pronunciation, Chinese explanations, examples, and visual references.**

**Not limited to *Circe*.** Use it with novels, classics, short stories, memoirs, essays, narrative nonfiction, and other English books. *Circe* by Madeline Miller is **only one example** of how this workflow can be used.

![Illustrative English output preview](assets/preview-english.png)

> Preview is an **illustrative mockup of the response structure**, not a screenshot of an actual ChatGPT session or a transcription of a copyrighted book.

## English

### What does this skill do?

| Step | Output |
| --- | --- |
| 1 · Read | Interpret a photograph of one or two facing pages; identify only readable text. |
| 2 · Summarize | A concise **Chinese story summary**, including relevant subtext, with no spoilers beyond the supplied pages. |
| 3 · Discuss | **One thoughtful question** in English, with Chinese translation; a real literary conversation, not a rote quiz. |
| 4 · Learn | Thorough **B2–C1 vocabulary** in exact page order: left page top-to-bottom, then right page top-to-bottom. |
| 5 · Visualize | Real-world reference images **beside useful visual words**, when supported by the assistant. |
| 6 · Continue | Maintain reading continuity across new page photos, and avoid needless repetition. |

Each vocabulary entry includes **American IPA**, approximate **CEFR level**, **contextual Chinese meaning**, a **newly written English example**, and its **Chinese translation**. Include meaningful phrases and uncommon literary words, but do not fill the list with trivial beginner vocabulary. Common words that challenge B2 readers (such as *glimpse, flare, scoff, reprieve*) should not be skipped.

### Supported books and genres

The workflow is **book-agnostic**: contemporary fiction, fantasy, historical fiction, mythology retellings, literary classics, crime fiction, science fiction, memoir, biographies, essays, and narrative nonfiction. Difficulty labels are approximate and should reflect usage and context, not claim official CEFR certification.

### Example output (original, fictional demonstration)

**Input:** A clear photograph of two facing pages from *any* English novel.

**1. Story summary / 内容总结**  
A traveler returns to a familiar coast but realizes that the place—and their sense of belonging—has changed.  
一位旅人重返熟悉的海岸，却发现故地与自己的归属感都已悄然改变。

**2. Discussion / 讨论问题**  
*Can returning to a familiar place make us feel less at home than leaving it?*  
重返熟悉的地方，是否反而可能让我们比离开时更没有归属感？

**3. Vocabulary / 生词** (demonstration only; actual output follows the photographed text's exact order)

**LEFT PAGE**

**01 · glimpse** /ɡlɪmps/ · **B2** — 瞥见；短暂看到  
*Example:* She caught a glimpse of the distant shore.  
*中文：* 她瞥见了远处的海岸。

**RIGHT PAGE**

**02 · relent** /rɪˈlent/ · **C1** — （恶劣情况、态度）缓和；变得不再严厉  
*Example:* The storm finally relented before dawn.  
*中文：* 暴风雨终于在黎明前减弱。

When a relevant term is concrete, the assistant may insert a reference image **between adjacent vocabulary entries without changing their order**.

### Installation and usage

**Option A · ChatGPT / other assistants that support custom skills:**
1. Download this repository (green **Code → Download ZIP**) or clone it.
2. Locate [`SKILL.md`](SKILL.md). Import the skill folder using the skill installation method supported by your assistant. **Installing a GitHub repository does not automatically activate a skill in ChatGPT.** Availability and invocation syntax vary by product.
3. Upload a clear photograph of a book page and ask the assistant to use *Literary Reading Companion*. If your environment supports explicit skill invocation, use its own invocation method.

**Option B · Without skill installation:** Open [`SKILL.md`](SKILL.md), copy its instructions into your assistant's custom instructions or the current conversation, and upload book-page photos. This works as a reusable prompt, though image lookup and continuity depend on the platform.

**Example prompts:**
- “Analyze these two pages using Literary Reading Companion.”
- “Continue with the next pages. Keep vocabulary in the book's reading order.”
- “Explain *reprieve* with American IPA, Chinese meaning, and an example.”
- “Only discuss the character's choice this time; skip vocabulary.”

### Photo tips and limitations

- Keep both pages sharp, well-lit, and as flat as possible; avoid covering words with fingers.
- For difficult words or blurred text, upload a close-up rather than asking the assistant to guess.
- Images are optional: they require an assistant capable of retrieving or displaying visual references. A Markdown file cannot force the chat interface to render pictures.
- This is an **instruction-based skill**, not a standalone app or a guaranteed one-click ChatGPT integration. Results depend on the model and its enabled capabilities.
- Examples are original and do not reproduce copyrighted book passages.

### Files

- [`SKILL.md`](SKILL.md) — skill behavior and formatting instructions
- [`examples/sample-output.md`](examples/sample-output.md) — sample reading response
- [`assets/preview-english.png`](assets/preview-english.png) — illustrative response preview
- [`assets/preview-chinese.png`](assets/preview-chinese.png) — bilingual illustrative preview
- [`LICENSE`](LICENSE) — license

---

## 中文说明

**Literary Reading Companion（英文文学精读助手）** 是一个开源、可复用的 AI 阅读 Skill，面向 **B2→C1 英语学习者**。它**不绑定任何一本书**：小说、文学经典、散文、回忆录、传记、叙事类非虚构作品等，都可以使用。之前阅读的《Circe》（《喀耳刻》）只是演示案例之一。

![双语示例展示（示意图）](assets/preview-chinese.png)

> 图片是为了说明输出形式而制作的**示意图**，并非真实聊天截图，也不是某本书的逐字摘录。

### 你会得到什么？

1. **剧情概括**：先用中文概括照片中的情节、人物关系和潜台词，不剧透后续章节。
2. **一个深度讨论问题**：英文问题配中文翻译；你回答后，可以继续自然讨论人物、选择、情感或主题。
3. **完整的 B2–C1 生词整理**：按**左页从上到下，再右页从上到下**的原文顺序，不按字母排序。重点覆盖真正影响阅读的中高级词汇、文学表达和固定搭配，不遗漏 *flare / scoff / reprieve* 等常见但有难度的词。
4. **每个词都提供**：美式音标、约略 CEFR 等级、结合上下文的中文释义、原创英文例句和中文翻译。
5. **图片辅助记忆**：植物、动物、器物、动作等适合视觉记忆的词汇，在平台支持时于词条附近插入参考图片；不打乱单词顺序。
6. **连续阅读**：后续上传新页面时继续当前进度，尽量避免无意义的重复解释。

### 安装与使用

**方式 A：支持自定义 Skill 的 AI 平台**  
点击 GitHub 绿色 **Code → Download ZIP** 下载，解压后找到 [`SKILL.md`](SKILL.md)，按照所使用平台的 Skill 导入方式添加。**仅仅下载或收藏 GitHub 仓库，并不会自动安装到 ChatGPT。** 不同平台的调用方式可能不同。

**方式 B：直接当作提示词使用**  
打开 [`SKILL.md`](SKILL.md)，将指令复制到 AI 的自定义指令或聊天中，然后上传英文书页照片。图片显示、连续记忆等能力取决于所用平台。

**使用示例：**
- “请按照 Literary Reading Companion 的格式分析这两页。”
- “继续下一页，所有生词按原文出现顺序排列。”
- “解释 *flesh* 和 *flash* 的区别，给出美式音标和例句。”
- “这次先不整理单词，我们只讨论人物为什么做出这个决定。”

### 拍照建议

尽量保证文字清晰、光线均匀、书页平整，不要用手遮挡重要段落。遇到模糊词汇可单独补拍。Skill 不应凭空猜测看不清的内容，也不会自动提供平台不支持的联网图片能力。

### 开源说明

这是一个**阅读工作流 / 指令型 Skill**，不是需要付费 API 才能运行的独立应用。使用效果取决于你所选的 AI 模型、是否支持图片理解及图片检索，以及 Skill 安装机制。
