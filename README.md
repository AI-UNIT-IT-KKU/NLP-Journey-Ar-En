# 🧠  دورة معالجة اللغة الطبيعية (NLP Course)

## 🧭 جدول المحتويات | Table of Contents
- [المقدمة](#-المقدمة-بالعربية)
- [Introduction (English)](#-introduction-in-english)
- [📘 محتوى الدورة | Course Contents](#-محتوى-الدورة--course-contents)

---

# 🇸🇦 المقدّمة (بالعربية)

## 🌍 ما هي المعالجة اللغوية الطبيعية (Natural Language Processing - NLP)؟

> **NLP** هو فرع من **الذكاء الاصطناعي (AI)** و **اللغويات الحاسوبية (Computational Linguistics)**، يهتم بتطوير الأنظمة التي تمكّن الحاسوب من **فهم اللغة البشرية وتحليلها والتفاعل بها**.  
>
> أي أنه مجال يبحث في **كيف يمكن للكمبيوتر أن يقرأ، ويكتب، ويتحدث، ويفهم اللغة مثل الإنسان.**

🔹 بالعربية:  
هو علم يجمع بين **علوم اللغة، الحوسبة، والذكاء الاصطناعي**، ويهدف إلى بناء نماذج قادرة على التعامل مع النصوص البشرية — مثل الترجمة، التلخيص، أو فهم الأسئلة.  
ولا علاقة له بعلم **NLP (Neuro-Linguistic Programming)** المتعلق بالتنمية البشرية.

---

## 🚀 أهمية المعالجة اللغوية الطبيعية

مع ازدياد المحتوى اللغوي الهائل على الإنترنت (مليارات الجمل يوميًا من تغريدات، مقالات، منشورات، محادثات...)، أصبح من الضروري وجود تقنيات **تفهم اللغة** لتساعدنا في:

- 🔍 **تحليل النصوص** وفهم المشاعر العامة.  
- 💬 **التفاعل الذكي** بين الإنسان والآلة.  
- 🌐 **ترجمة النصوص** بين اللغات بدقة متزايدة.  
- 📈 **تنظيم المعرفة** من كميات ضخمة من البيانات النصية.  

> 💡 بحلول عام **2025**، أصبحت تقنيات الـ NLP جزءًا أساسياً من حياتنا اليومية:  
> من ChatGPT وClaude وGemini إلى المساعدين الصوتيين الذكيين في كل هاتف وجهاز منزلي.  
> تطوّر المجال خلال آخر أربع سنوات بسرعة هائلة، جعلت فهم اللغة البشرية من أعقد تحديات الذكاء الاصطناعي وأكثرها تأثيرًا اقتصاديًا.

---

## 🕰️ تاريخ المعالجة اللغوية الطبيعية (1940 → 2025)

| الحقبة          | الحدث الأبرز                                                                          | الأثر                                            |
| ---------------- | ------------------------------------------------------------------------------------- | ------------------------------------------------ |
| **1600s–1800s** | فلاسفة مثل لايبنتز وديكارت حاولوا تصميم رموز تربط بين اللغات                          | بدايات التفكير في اللغة الرمزية                  |
| **1930s**       | أفكار أولية حول الترجمة الآلية                                                        | نظريات فقط، دون تطبيقات عملية                    |
| **1950**        | آلان تورنغ ينشر مقال *"Computing Machinery and Intelligence"* ويقترح **اختبار تورنغ** | أول معيار لقياس ذكاء الآلة لغويًا                |
| **1954**        | تجربة *Georgetown-IBM*: ترجمة 60 جملة روسية إلى إنجليزية                              | أول تجربة ترجمة آلية ناجحة جزئيًا                |
| **1968**        | مشروع **SHRDLU** في MIT (Terry Winograd)                                              | حوار تفاعلي ذكي مع الحاسوب داخل "عالم الكتل"     |
| **1991**        | إطلاق برنامج **DOCTOR SBAITSO**                                                       | أول نموذج مبكر لفكرة “Chatbot”                   |
| **2006**        | إطلاق **IBM Watson**                                                                  | فوز النظام على البشر في برنامج Jeopardy          |
| **2011–2016**   | ظهور المساعدات الذكية: **Siri, Alexa, Cortana, Google Assistant**                     | دخول NLP في الحياة اليومية                       |
| **2018**        | ظهور **BERT** من Google و**GPT** من OpenAI                                            | بداية عصر "نماذج اللغة العميقة"                  |
| **2020–2023**   | إطلاق **ChatGPT**، **Claude**، **Llama**                                              | ثورة في التفاعل اللغوي الإنساني – الآلي          |
| **2024–2025**   | اعتماد نماذج اللغة في التعليم، الصحة، والبحث العلمي                                   | NLP يصبح ركيزة أساسية في الاقتصاد الرقمي العالمي |

> 🧩 خلاصة:  
> خلال 70 سنة، انتقلت المعالجة اللغوية الطبيعية من "ترجمة جمل بسيطة" إلى **أنظمة تفكر وتكتب وتحاور بذكاء مذهل**.

---

## ⚙️ تحدّيات المعالجة اللغوية الطبيعية

رغم التقدّم الهائل، لا يزال التعامل مع اللغة **أحد أصعب التحديات** في الذكاء الاصطناعي، لأن اللغة:

- 🌀 **غامضة ومعقّدة** بطبيعتها.  
  > “All the money he had had had had no effect on him.”  
  > جملة صحيحة نحويًا، لكنها مربكة دلاليًا.

- 🔁 **غنية بالاحتمالات والتفسيرات المتعددة.**  
  > “A woman, without her man, is nothing.”  
  > مقابل  
  > “A woman: without her, man is nothing.”  
  > نفس الكلمات، لكن المعنى يتغيّر تمامًا حسب الترقيم.

- 🌍 **تختلف اللهجات والمعاني حسب الثقافة.**  
  كلمة “شيخة” مثلاً تختلف معناها بين مصر والخليج والمغرب.

- 🎭 **تحتوي على مجازات وسخرية وصيغ عامية**  
  مثل: “طير من هنا”، “فِرمِت الجهاز”، “رن له”.

- 📜 **النصوص غير مهيكلة (Unstructured Data)**  
  يصعب على الحاسوب تحليلها مثل الأرقام.

> ❗️لذلك يقال:  
> "اللغة سهلة للبشر، صعبة للحواسيب."

---

## 🤖 تطبيقات المعالجة اللغوية الطبيعية (حتى عام 2025)

| المجال                                  | التطبيقات                       | التطوّر حتى 2025                       |
| --------------------------------------- | ------------------------------- | -------------------------------------- |
| **الترجمة الآلية**                      | Google Translate, DeepL         | أصبحت شبه بشرية في الفهم والسياق       |
| **نماذج اللغة (LLMs)**                  | ChatGPT, Claude, Gemini, LLaMA  | أصبحت تولّد نصوصًا دقيقة ومبدعة        |
| **تحليل المشاعر والرأي العام**          | أدوات مراقبة السوشيال ميديا     | تُستخدم سياسيًا وتجاريًا لفهم الجمهور  |
| **التلخيص الذكي للنصوص**                | Summarizers وGPT-based tools    | تلخيص فوري وذكي لمقالات وتقارير        |
| **استخراج المعلومات**                   | في الصحافة، والبحوث، والتحقيقات | نماذج تفهم النصوص القانونية والعلمية   |
| **التعرّف على الكلام (Speech-to-Text)** | Whisper, Alexa, Google Speech   | دقّة تفوق 98% في بيئات متعددة اللغات   |
| **التحليل اللغوي في التعليم**           | Grammarly, ChatGPT Tutors       | تصحيح ذكي وتقييم لغوي في الوقت الحقيقي |
| **التفاعل الصوتي والمحادثة**            | روبوتات خدمة العملاء الذكية     | أصبح المحادث أقرب ما يكون للإنسان      |

> 🌟 باختصار:  
> المعالجة اللغوية الطبيعية اليوم هي "لغة الآلات" التي تتحدث بها مع البشر.

---

## 🪄 الخلاصة

> علم الـ NLP هو الجسر بين **اللغة البشرية والفكر الآلي**.  
> كل تطبيق ذكي حولك — من الترجمة إلى ChatGPT — يعتمد على مبادئ هذا العلم.  
> والسنوات القادمة ستجعل هذا المجال أكثر تداخلاً مع كل جانب من حياتنا.

---

# 🇬🇧 Introduction (in English)

## 🌍 What is Natural Language Processing (NLP)?

> **NLP** is a subfield of **Artificial Intelligence (AI)** and **Computational Linguistics**, concerned with building systems that can **understand, analyze, and interact** using human language.  
>
> In simple terms, it explores **how computers can read, write, speak, and comprehend language like humans do.**

It combines **linguistics, computer science, and AI** to create models capable of handling human text — such as translation, summarization, and question answering.  
And it has **no relation** to *Neuro-Linguistic Programming (NLP)* used in personal development.

---

## 🚀 Why NLP Matters

The internet today is filled with massive amounts of textual data — billions of words daily from tweets, posts, articles, and conversations.  
We need NLP to help machines make sense of this chaos.

- 🔍 **Text analysis** and sentiment detection.  
- 💬 **Human–machine interaction** (chatbots, assistants).  
- 🌐 **Automatic translation** between languages.  
- 📈 **Knowledge extraction** from unstructured data.

> 💡 By **2025**, NLP technologies have become essential to daily life:  
> from ChatGPT and Claude to Gemini and voice assistants.  
> The last few years have seen explosive growth that reshaped how machines understand human language.

---

## 🕰️ A Brief History of NLP (1940 → 2025)

| Era            | Key Milestone                                                            | Impact                                           |
| --------------- | ------------------------------------------------------------------------ | ------------------------------------------------ |
| **1600s–1800s** | Philosophers like Leibniz & Descartes proposed symbolic language systems | Early ideas of symbolic language                 |
| **1930s**       | Initial concepts of machine translation                                  | Theoretical only                                 |
| **1950**        | Alan Turing published *Computing Machinery and Intelligence*             | Proposed the **Turing Test**                     |
| **1954**        | *Georgetown–IBM* experiment: 60 sentences translated                     | Early success in machine translation             |
| **1968**        | **SHRDLU** at MIT by Terry Winograd                                      | Early conversational AI in a simulated world     |
| **1991**        | **Doctor Sbaitso** chatbot                                               | Early AI therapist simulation                    |
| **2006**        | **IBM Watson**                                                           | Defeated humans in *Jeopardy!*                   |
| **2011–2016**   | Siri, Alexa, Cortana, Google Assistant                                   | NLP enters everyday life                         |
| **2018**        | **BERT** (Google) & **GPT** (OpenAI)                                     | Birth of deep language models                    |
| **2020–2023**   | ChatGPT, Claude, LLaMA                                                   | Revolution in human–AI conversation              |
| **2024–2025**   | Language models used in education, health, and science                   | NLP becomes a global digital backbone            |

> 🧩 In 70 years, NLP evolved from simple translation to systems that **think, write, and converse intelligently.**

---

## ⚙️ NLP Challenges

Language is **inherently complex** — full of ambiguity, culture, and emotion.

- 🌀 **Ambiguity**  
  “All the money he had had had had no effect on him.”

- 🔁 **Syntax and punctuation change meaning**  
  “A woman, without her man, is nothing.”  
  vs.  
  “A woman: without her, man is nothing.”

- 🌍 **Dialects & cultural context**  
  One Arabic word like “شيخة” has different meanings across countries.

- 🎭 **Slang, sarcasm, and metaphors**  
  Machines struggle to interpret figurative language.

- 📜 **Unstructured text data**  
  Unlike numbers, text has no fixed format.

> ❗️For humans, language is natural.  
> For machines, it’s chaos.

---

## 🤖 NLP Applications (as of 2025)

| Field | Applications | Evolution |
|-------|---------------|------------|
| **Machine Translation** | Google Translate, DeepL | Nearly human-level fluency |
| **Language Models (LLMs)** | ChatGPT, Claude, Gemini, LLaMA | Produce coherent, creative text |
| **Sentiment Analysis** | Social Media Analytics | Drives political & business insights |
| **Summarization** | GPT-based tools | Real-time intelligent text summarization |
| **Information Extraction** | Legal, journalism, research | Deep text comprehension |
| **Speech Recognition** | Whisper, Alexa, Google Speech | Accuracy over 98% |
| **Education & Writing Tools** | Grammarly, ChatGPT Tutors | Real-time corrections & learning |
| **Conversational AI** | Customer support chatbots | Human-like conversations |

> 🌟 In short: NLP is the **language of machines that speak to humans.**

---

## 🪄 Conclusion

> NLP bridges **human language and artificial intelligence.**  
> Every smart app — from translators to ChatGPT — is built upon it.  
> The future will only deepen this connection between humans and machines.

---

# 📘 محتوى الدورة | Course Contents

> 🇸🇦  
> في هذا القسم ستجد جميع دفاتر الدورة (**Notebooks**) بالترتيب،  
> من الأساسيات إلى الأدوات المتقدمة، لتتعلم كيف تفهم الحواسيب اللغة البشرية خطوة بخطوة.

> 🇬🇧  
> Below are all the course notebooks,  
> organized from basic foundations to advanced NLP tools — guiding you through how machines understand human language.



| 🔢 القسم | 📖 المحتوى                | 📘 Notebook             | 📝 الوصف                                                             |                                                                                                                                                                                                                                                                                                                                                 |
| -------- | ------------------------- | ----------------------- | -------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1️⃣      | الأساسيات               | NLP Basics            | [`01_NLP_Basics.ipynb`](./01_NLP_Basics.ipynb)                       | 🇸🇦 التعامل مع النصوص، ملفات PDF، والتعبيرات النمطية (Regex).<br>🇬🇧 Handling text files, PDFs, and regular expressions (Regex).                                                                                                                                                                                                              |
| 2️⃣      | أدوات المعالجة اللغوية  | NLP Tools             | [`02_NLP_Tools.ipynb`](./02_NLP_Tools.ipynb)                         | 🇸🇦 تحليل النصوص باستخدام مكتبات NLTK وspaCy: **تقسيم الجمل والكلمات، الوسوم النحوية، الجذور، الكيانات، الكلمات الشائعة، العلاقات النحوية، والتصوّر البصري للنصوص.**<br>🇬🇧 Text analysis using NLTK & spaCy: **Tokenization, Sentence Segmentation, POS Tagging, Stemming, NER, Stopwords, Matchers, Syntax Trees, and Text Visualization.** |
| 3️⃣      | المعالجة البسيطة للنصوص | Basic Text Processing | [`03_Basic_Text_Processing.ipynb`](./03_Basic_Text_Processing.ipynb) | 🇸🇦 من التمثيل بالكلمات إلى المعنى: **BoW، TF-IDF، Word2Vec، وقياس التشابه النصي والمعنوي.**<br>🇬🇧 From word counts to meaning: **BoW, TF-IDF, Word2Vec, and Textual & Semantic Similarity techniques.**                                                                                                                                     |

---

> 💡 **ملاحظة | Note:**  
> 🇸🇦 هذا المشروع مفتوح المصدر لغرض التعليم، مستوحى من دورة الأستاذ **هشام عاصم**،  
> مع تحديثات حديثة حتى عام **2025** وتنسيق باللغتين العربية والإنجليزية.  
>
> 🇬🇧 This is an open-source educational project inspired by **Hesham Assem’s Arabic NLP course**,  
> updated for **2025 standards** with bilingual Arabic–English explanations.

---

> 🧾 *Summarized and written by me, inspired by the Arabic NLP Course by Hesham Assem.*
