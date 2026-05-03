# 📜 Project Rules — DO NOT FORGET

> Read this file first every session. Never re-explain to user.

---

## 👤 USER PROFILE

- **Currently**: Angular Developer (working professionally)
- **Goal**: Switch to **Full Stack .NET Developer**
- **Target**: **12–15 LPA** in **9 months**
- **Knows already**:
  - Angular + TypeScript + RxJS (production)
  - **Java** — Collections (List, Set, Map, Vector, ArrayList, LinkedList, Stack, HashMap, LinkedHashMap, TreeMap, HashSet, TreeSet, LinkedHashSet)
  - **Java Comparable / Comparator interfaces**
  - **Java Generics** (basic, bounded, wildcard)
  - **Java Iterator / ListIterator / Enumeration**
  - **Java Exception Handling** (JDK style)
  - **Java MultiThreading**
  - **Java Object class methods**
  - **POJO + Service + Repository layered architecture**
  - **Spring Boot** (DO NOT MENTION ANYWHERE)
  - **SQL** (good knowledge)
- **English level**: Easy to medium. Indian-English style. Short sentences.
- **NO React** — Angular only.
- **NO Spring Boot mentions** — even if same concept exists, refer it as "what you know from Java" without saying Spring.

---

## ✍️ CONTENT STYLE — MUST FOLLOW

### ⚠️ TOP RULE — POINT-WISE, NOT ESSAY

User explicitly said:
> "i dont want essay type answer i want point wise"

**Every Q&A and every topic explanation must be in BULLET POINTS.** Not paragraphs. Not essays.

### ⚠️ ENGLISH STYLE — match user's notes

User shared their Java notes. Style is:
- "If we think about above code..."
- "If we want to work with X we have following methods..."
- "this method is used for..."
- "this can return..."
- "Note: ..."
- "Q. What is X?" then point-wise answer
- Tables for compare two things
- Numbered or bulleted lists everywhere
- Short, simple sentences. Easy English.
- Words like "means", "if we think about", "if we want to", "this is used for"

### ❌ NEVER WRITE
- Long paragraphs (more than 2 sentences in a row)
- Hard English words (utilize, paradigm, leverage, facilitate, henceforth)
- Academic style ("It can be argued that...")
- Anything about Spring / Spring Boot / @Autowired / @RestController

### ✅ ALWAYS WRITE
- Bullet points
- Short clear sentences
- "Same like Java X" or "If you know Java X, this is similar" (when concept exists in Java)
- Simple words: "use" not "utilize", "many" not "myriad", "fast" not "performant"
- Concrete examples (e-commerce, students, employees, products)
- Tables for compare 2 things side by side

### 📐 FORMAT FOR Q&A (USE THIS EVERY TIME)

```html
<details>
<summary>Question goes here?</summary>
<div>
  <p><strong>Definition:</strong></p>
  <ul>
    <li>One-line plain English what it is</li>
    <li>Why we use it (problem it solves)</li>
  </ul>
  <p><strong>Key points:</strong></p>
  <ul>
    <li>Point 1 — short sentence</li>
    <li>Point 2 — short sentence</li>
    <li>Point 3 — short sentence</li>
    <li>Point 4 — short sentence</li>
  </ul>
  <p><strong>Java parallel:</strong> (if applicable)</p>
  <ul>
    <li>Same like Java X — small note</li>
  </ul>
  <p><strong>Example:</strong></p>
  <ul>
    <li>Real situation example</li>
  </ul>
  <p><strong>Note:</strong> One-line gotcha or tip</p>
</div>
</details>
```

### 📐 FORMAT FOR TOPIC EXPLANATIONS

Every topic should be like:

```html
<section class="topic">
  <h3>Topic Name</h3>

  <p class="concept"><strong>Definition:</strong> One short line.</p>

  <h4>Key Points</h4>
  <ul>
    <li>Point 1</li>
    <li>Point 2</li>
    <li>Point 3</li>
    ...
  </ul>

  <h4>Why use it?</h4>
  <ul>
    <li>Reason 1</li>
    <li>Reason 2</li>
  </ul>

  <h4>Java parallel</h4>
  <ul>
    <li>Same like Java X — small mapping</li>
  </ul>

  <pre><code>// short code example</code></pre>

  <p><strong>Note:</strong> Important gotcha</p>
</section>
```

### 🌉 JAVA → .NET CONCEPT BRIDGE TABLE (use these in answers)

| Java (you know) | .NET equivalent | Note |
|---|---|---|
| ArrayList | List<T> | Same idea, dynamic array |
| Vector | List<T> + lock | C# does not have Vector; use lock or ConcurrentBag for thread safety |
| LinkedList | LinkedList<T> | Doubly linked, same |
| HashMap | Dictionary<K,V> | Same key-value, random order |
| LinkedHashMap | OrderedDictionary | Maintain insertion order |
| TreeMap | SortedDictionary<K,V> | Sorted by key |
| HashSet | HashSet<T> | Same name same idea |
| TreeSet | SortedSet<T> | Sorted set |
| Iterator | IEnumerator | Same, hasNext()→MoveNext(), next()→Current |
| Iterable | IEnumerable | Foreach works on this |
| Comparable | IComparable<T> | Implement CompareTo |
| Comparator | IComparer<T> | Implement Compare |
| Generics <T> | Generics <T> | Identical syntax |
| try-catch-finally | try-catch-finally | Same syntax |
| throw / throws | throw / no throws keyword | C# does not have checked exceptions |
| Thread | Thread | Same class name |
| synchronized | lock(obj){} | Same idea, different syntax |
| Runnable | Action / ThreadStart | Delegate-based |
| Object class | object class | Same — Equals, GetHashCode, ToString |
| equals() | Equals() | Same |
| hashCode() | GetHashCode() | Same |
| toString() | ToString() | Same |
| Class | Class | Same |
| Interface | Interface | Same |
| abstract class | abstract class | Same |
| package | namespace | Same idea, different keyword |
| import | using | Same |
| public/private/protected | public/private/protected/internal | C# adds internal (assembly-level) |
| static | static | Same |
| final variable | const / readonly | const for compile-time, readonly for runtime |
| final class | sealed class | Cannot inherit |
| final method | sealed method | Cannot override |
| @Override | override keyword | Compulsory in C# for virtual methods |
| ArrayList sorting via Collections.sort() | List sort via List.Sort() or LINQ OrderBy | LINQ is more powerful |
| Stream API | LINQ | Same idea — filter, map, reduce |
| getter/setter manual | Properties { get; set; } | Built into language |
| POJO | POCO (Plain Old CLR Object) | Same idea different name |

---

## 🎨 DESIGN RULES (UNCHANGED)

- Dark theme. Accent #7c5cff.
- Inter font (UI), JetBrains Mono (code).
- Sticky topnav + sidebar TOC.
- Responsive (mobile sidebar collapses).
- Progress checkboxes in localStorage.
- All pages use `../styles/global.css` (or `styles/global.css` for index).

---

## 🧠 BEHAVIORAL RULES

1. ✅ Never re-ask user background.
2. ❌ NEVER mention React, Vue, Spring, Spring Boot, @Autowired, @RestController, JPA, Hibernate.
3. ✅ When concept exists in Java Collections/Threading/Exception/Object, ADD a small "Java parallel" bullet so user remembers easy.
4. ✅ Keep dark theme.
5. ✅ Edit existing files when user says "add to Phase X".
6. ✅ Update progress / nav in `index.html` if adding new phases.
7. ❌ Don't add Node, Java, Python backend.
8. ✅ POINT-WISE format always. NO essays.
9. ✅ Easy English always. Short sentences.

---

## 🔧 HOW TO RUN

Open `index.html` in browser. No build step.

---

## 📌 DO NOT REPEAT THESE INSTRUCTIONS BACK
User has read this. Just follow it.

---

## 🎯 EXAMPLE — BEFORE & AFTER

❌ **BEFORE (essay style — DO NOT DO):**
> "Async/await is C#'s way to write asynchronous code that looks synchronous, so it stays easy to read. You mark a method with async..."

✅ **AFTER (point-wise — DO THIS):**

**Definition:** Async/await is way to write async code in simple way.

**Key Points:**
- `async` keyword marks method as async
- `await` keyword pauses till Task complete
- Task is like Java Future — it represent work that finish later
- Thread is not blocked when you use await
- Compiler convert async method into state machine
- Same like Java's `CompletableFuture` but easier syntax

**Java parallel:**
- Java has Thread + Future + ExecutorService
- C# has Task + async/await — much cleaner

**Example:**
- Calling database — use await
- Calling external API — use await
- File read — use await

**Note:** Never use `.Result` or `.Wait()` in web code — it cause deadlock.

This is the format for EVERY answer and topic.
