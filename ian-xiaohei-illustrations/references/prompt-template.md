# 生图提示词模板

每张图单独生成。根据正文内容替换变量，不要把多张图拼在一起。

```text
Generate one standalone 16:9 horizontal Chinese article illustration.

Visual DNA:
Pure white background. Minimalist hand-drawn line art for the explanatory structure. Slightly wobbly pen lines. Lots of empty white space. Sparse handwritten Chinese annotations using brand blue #012fe3, orange, and brand green #01c193. Clean absurd product-sketch feeling. The recurring character Bemo follows the provided reference image identity. No gradients, no shadows, no paper texture, no complex background, no commercial vector style, no PPT infographic look, no cute mascot poster, no children's illustration, no realistic UI.

Recurring IP character required:
Use the provided Bemo reference image. If no image is provided by the user, use the bundled reference images in assets/brand/. Bemo is a blue-haired chibi developer in a green hoodie with white drawstrings, blue/teal eye identity, casual pants and blue-white shoes, often using a laptop or code-symbol object. Bemo must perform the core conceptual action, not decorate the scene. Preserve the blue hair, green hoodie, developer mood, and cheerful but focused personality.

Theme:
{正文配图主题}

Structure type:
{结构类型：Workflow / 系统局部 / 前后对比 / 角色状态 / 概念隐喻 / 方法分层 / 地图路线 / 小漫画分镜}

Core idea:
{这张图要表达的核心意思}

Composition:
{具体画面：Bemo 在哪里、正在做什么、主要物件是什么、信息如何流动}

Suggested elements:
{元素1} / {元素2} / {元素3} / {元素4}

Chinese handwritten labels:
{标注词1} / {标注词2} / {标注词3} / {标注词4} / {可选标注词5}

Color use:
Black for most explanatory line art and main handwritten text. Preserve the brand character colors from the reference image: saturated blue hair, green hoodie, skin tone, blue-white shoes, and blue code/laptop accents. Orange for main flow/path/arrows. Brand blue #012fe3 only for key warnings/problems/results. Brand green #01c193 only for secondary notes or feedback/system state. Do not use red for warnings, and do not use ordinary blue for secondary notes.

Constraints:
One image explains only one core structure. Keep the main subject around 40%-60% of the canvas. Preserve at least 35% blank white space. Use at most 5-8 short handwritten Chinese labels. Do not write a title in the top-left corner. Do not write the structure type on the image. Do not make it a formal diagram, course slide, or dense explainer. Do not copy prior examples or reuse known case compositions unless explicitly requested; invent a fresh visual metaphor for this specific article. It should be clear but not instructional, interesting but not childish, strange but clean.
```

## 图像编辑提示

去掉左上角标题：

```text
Edit the provided image. Remove only the handwritten title "{要删除的文字}" and its underline from the top-left corner. Fill that area with the same clean white background, matching the surrounding blank paper. Preserve everything else exactly: characters, labels, paths, line style, composition, aspect ratio, and image quality. Do not add any new text or objects.
```

增强怪诞感：

```text
Regenerate this illustration with the same core meaning and simple layout, but make Bemo more central to the conceptual action. Bemo should be doing the strange work that explains the idea, not standing beside the diagram. Preserve the provided character identity: blue hair, green hoodie, developer mood. Keep it clean, sparse, hand-drawn, and not mascot-like.
```
