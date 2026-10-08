# 🎓 سنة Gemini ببلاش للطلبة + 10 Prompts للمذاكرة

لو انت طالب جامعة، Google بتديك اشتراك Gemini المدفوع سنة كاملة ببلاش.
بس الاشتراك لوحده مش هيفرق، اللي هيفرق إنك تعرف تطلب منه إيه وانت بتذاكر.

هنا هتلاقي **الـ 10 Prompts اللي بستخدمها بالظبط** للتلخيص وحل المسائل وتحضير الامتحانات، وكل واحد معاه شرح بيعمل إيه وامتى تستخدمه.

> 💡 انسخ الـ Prompt زي ما هو، وغيّر بس الحاجات اللي بين `[ ]`.

---

## 🔌 الأول: فعّل العرض

1. ادخل على صفحة العرض الرسمية: **[gemini.google/students](https://gemini.google/students)** واختار العرض المتاح في بلدك.
2. أكّد إنك طالب (التحقق بيتم عن طريق SheerID). استخدم **حساب Google شخصي**، مش حساب الجامعة نفسه.
3. هيطلب منك وسيلة دفع. مش هيسحب حاجة طول السنة، بس ده عشان التجديد بعدها.

📅 **آخر ميعاد تفعّل فيه العرض: 31 ديسمبر 2026.**

🇺🇸 في أمريكا الخطة اسمها Google AI Pro، وبرّه أمريكا اسمها **Google AI Plus**، فيها حدود استخدام أعلى في Gemini ومساحة تخزين أكبر.

> ⏰ **أهم خطوة:** اعمل Reminder على الموبايل بعد **11 شهر** من التفعيل، وادخل على إعدادات الاشتراك في Google One وألغي التجديد التلقائي. لو نسيت، هيبدأ يسحب فلوس.

لو واجهتك مشكلة، شوف الشروط الكاملة على صفحة العرض أو [مساعدة Google One](https://support.google.com/googleone).

---

## 📄 1. لخّصلي المحاضرة

استخدمه أول ما تخلص أي محاضرة. ارفع الـ PDF أو صور السلايدز مع الـ Prompt.

```
I uploaded my lecture on [اسم المادة / الموضوع].
Summarize it for a university student revising for an exam:
1. A 5-line overview of what the lecture is about.
2. The key concepts, each with a one-sentence definition.
3. Any formulas, laws or dates, listed separately.
4. The 5 points most likely to come in the exam, and why.
Use only what is in the file. If something is unclear in the file, say so instead of guessing.
```

**بيعمل إيه؟** بيحوّل محاضرة طويلة لصفحة واحدة مترتبة: الفكرة، التعريفات، القوانين، والنقط المهمة للامتحان.
**نصيحة:** جملة "Use only what is in the file" بتخليه ميألّفش حاجات مش في المنهج بتاعك.

---

## 🧠 2. اشرحلي كأني أول مرة أسمع عنه

لما تقف عند مفهوم مش فاهمه.

```
Explain [اسم المفهوم] from [اسم المادة] as if I am hearing it for the first time.
Start with a simple everyday example, then give the proper academic definition,
then show one worked example from the subject itself.
End with 3 quick questions to check I understood. Don't give me the answers until I reply.
```

**بيعمل إيه؟** بيبدأ بمثال من الحياة، وبعدين التعريف الأكاديمي، وبعدين مثال من المادة، وفي الآخر يختبرك.

---

## ✏️ 3. حل المسألة خطوة بخطوة

للمسائل والتمارين اللي مش عارف تبدأها.

```
Here is a problem from [اسم المادة]:
[اكتب المسألة أو ارفع صورتها]

Solve it step by step. For each step, explain why you are doing it, not only what you are doing.
After the solution, list the rule or formula used in each step,
and point out the most common mistake students make in this type of problem.
```

**بيعمل إيه؟** مش بيديك الناتج وخلاص، بيشرحلك ليه كل خطوة، وفين الطلبة بيغلطوا عادة.

---

## 🧩 4. ساعدني أحلها بنفسي

لما تكون عايز تتعلم بجد مش تنقل الحل.

```
I want to solve this problem myself:
[اكتب المسألة]

Don't give me the solution. Give me one hint at a time.
Wait for my answer after each hint. If I'm wrong, tell me where my thinking went off, then give the next hint.
```

**بيعمل إيه؟** بيقلب Gemini لمدرس خصوصي: تلميح واحد كل مرة، وانت اللي توصل للحل.
**نصيحة:** ده أحسن Prompt لو المادة فيها مسائل كتير، لأنك في الامتحان هتحلها لوحدك.

---

## ✅ 5. صحّحلي حلي

بعد ما تحل مسألة أو تكتب إجابة، قبل ما تسلّم أو تكمّل.

```
Here is the question and my answer:
Question: [السؤال]
My answer: [إجابتك]

Grade my answer like a strict university examiner out of [الدرجة الكاملة].
Show what is correct, what is wrong or missing, and how many marks I would lose for each mistake.
Then show a model answer.
```

**بيعمل إيه؟** بيصحح زي الدكتور بالظبط: فين صح، فين غلط، وهتخسر كام درجة، وبعدين الإجابة النموذجية.

---

## 📝 6. اعملي امتحان تجريبي

قبل الامتحان بكام يوم.

```
Based on the material I uploaded for [اسم المادة], create a practice exam:
- 10 multiple choice questions
- 5 short answer questions
- 2 long questions like a real final exam
Mix easy, medium and hard. Don't show the answers.
After I send my answers, grade them and tell me which topics I need to revise.
```

**بيعمل إيه؟** امتحان كامل من المنهج بتاعك، وبعد ما تحل بيقولك إنت ضعيف في أنهي جزء.

---

## 🃏 7. Flashcards للمراجعة

للحاجات اللي محتاجة حفظ: تعريفات، مصطلحات، تواريخ، قوانين.

```
From the material on [الموضوع], make 20 flashcards.
Format each one as:
Front: a short question
Back: the answer in one or two lines
Focus on definitions, formulas and anything I need to memorize. Put them in a table.
```

**بيعمل إيه؟** بيطلعلك 20 كارت في جدول، تراجع منهم في المواصلات أو قبل الامتحان بساعة.

---

## 🗓️ 8. خطة مذاكرة لحد الامتحان

أول ما جدول الامتحانات ينزل.

```
My exams are:
[المادة 1] on [التاريخ]
[المادة 2] on [التاريخ]
[المادة 3] on [التاريخ]

I can study about [عدد الساعات] hours a day, and today is [تاريخ النهارده].
My weakest subject is [المادة] and my strongest is [المادة].
Make a day-by-day study plan in a table, with revision days before each exam and one light day per week.
```

**بيعمل إيه؟** بيقسم المنهج على الأيام اللي فاضلة، ويدي المادة الصعبة وقت أكتر، ويسيبلك أيام مراجعة.

---

## 🗺️ 9. اربطلي الشابتر ببعضه

لما الشابتر يكون طويل والأفكار متلخبطة في دماغك.

```
Make a structured outline of [اسم الشابتر] showing how the ideas connect:
main topic, then sub-topics, then the key points under each.
Use indented bullets like a mind map.
At the end, write 3 sentences explaining how this chapter connects to [شابتر تاني أو موضوع تاني].
```

**بيعمل إيه؟** بيعملك خريطة ذهنية بالنقط، فتشوف الشابتر كله مرة واحدة وتفهم إزاي الأجزاء مرتبطة ببعض.

---

## 🎯 10. أنا أشرح وانت تكشف الثغرات

آخر خطوة قبل الامتحان: لو عرفت تشرحها، يبقى فاهمها.

```
I will explain [اسم المفهوم] to you in my own words.
Act as my professor. After I explain, tell me:
1. What I got right.
2. What I got wrong or left out.
3. One follow-up question a professor would ask to test if I really understand.
Here is my explanation: [اكتب شرحك]
```

**بيعمل إيه؟** بيخليك انت اللي تشرح، وهو يطلعلك الحاجات اللي فاكر إنك فاهمها وانت مش فاهمها.

---

## 🇪🇬 تقدر تكتبله بالمصري كمان

Gemini فاهم المصري كويس جدًا. جرّب ده مع أي PDF:

```
أنا رافعلك محاضرة [اسم المادة]. لخصهالي في صفحة واحدة،
وقولي أهم 5 حاجات ممكن ييجوا في الامتحان،
وبعدين اسألني 5 أسئلة عليها واحدة واحدة، ومتقوليش الإجابة غير لما أرد.
```

---

## ⚠️ نصايح مهمة

- **راجع أي إجابة مهمة:** Gemini ممكن يغلط، خصوصًا في الحسابات. قارن بالكتاب أو السلايدز.
- **ارفع الملف دايمًا:** لما ترفع المحاضرة نفسها، الإجابات بتبقى من منهجك انت مش من النت.
- **استخدمه عشان تفهم، مش عشان تنقل:** اتأكد من قواعد جامعتك في استخدام الـ AI في الأسايمنتس والمشاريع.
- **متنساش الـ Reminder:** بعد 11 شهر ألغي التجديد، وإلا هيبدأ يسحب من الكارت.
- **خلي بياناتك لنفسك:** متكتبش أرقام سرية أو بيانات شخصية في الشات.

---

## 🚀 الخلاصة

| قبل | بعد |
|---|---|
| تقرا المحاضرة 3 مرات ومش فاكر حاجة | ملخص صفحة واحدة بأهم النقط |
| تقف عند المسألة ومتعرفش تبدأ | تلميحات خطوة بخطوة لحد ما تحلها |
| تدخل الامتحان ومتعرفش مستواك | امتحان تجريبي بيقولك ضعيف في إيه |
| تذاكر كل حاجة في آخر أسبوع | خطة يوم بيوم لحد آخر امتحان |

---

لو استفدت، تابعني عشان فيه Prompts وأتمتة أكتر جاية 🔥
وابعت الصفحة دي لصاحبك اللي في الجامعة 🎓

**Steven Ayman — Vida AI**
