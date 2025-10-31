# Why React? 
## 🚀 ১. ইন্ডাস্ট্রিতে React-এর ব্যাপক চাহিদা

Facebook (Meta), Instagram, Netflix, Airbnb, Uber, Discord — এইসব বড় বড় কোম্পানি **React** ব্যবহার করে।
👉 তাই React শিখলে **ভালো চাকরি পাওয়ার সম্ভাবনা অনেক বেশি**।

---

## ⚛️ ২. Component-Based সিস্টেম (পুনঃব্যবহারযোগ্য কোড)

React-এ আপনি UI তৈরি করেন **কম্পোনেন্ট** দিয়ে — যেমন আলাদা **Navbar, Button, Card** ইত্যাদি।
👉 একবার লিখে বারবার ব্যবহার করা যায় — এতে কোড হয় পরিষ্কার, সংগঠিত এবং সময় বাঁচে।

---

## ⚡ ৩. দ্রুত পারফরম্যান্স (Virtual DOM)

React **Virtual DOM** ব্যবহার করে, যা শুধু প্রয়োজনীয় অংশ আপডেট করে।
✔ তাই ওয়েবসাইট হয় **দ্রুত, স্মুথ এবং লাইটওয়েট** — পুরনো পদ্ধতির চেয়ে অনেক বেশি উন্নত।

---

## 📚 ৪. বড় কমিউনিটি এবং অনেক লাইব্রেরি সাপোর্ট

React-এর জন্য আছে **React Router, Redux, Axios, Tailwind CSS, Next.js** এর মতো শক্তিশালী টুলস।
👉 আপনি চাইলে খুব সহজে **Advanced Web App** বানাতে পারবেন।

---

## 🎯 ৫. চাকরির বাজারে React ডেভেলপারের বেতন বেশি

চাকরির সাইটগুলোতে আপনি দেখবেন:

* **React JS Developer**
* **Frontend Developer (React)**
* **Full Stack Developer (MERN Stack)**
  👉 React জানা ডেভেলপারদের **বেতন এবং সুযোগ — দুটোই বেশি।**

---

## 🌍 ৬. আধুনিক টেক স্ট্যাকের মূল অংশ

React হচ্ছে **MERN Stack**, **Next.js Stack** এবং আধুনিক ওয়েব ডেভেলপমেন্টের মূল ভিত্তি।
👉 **Single Page Application, Dashboard, E-commerce, Portfolio** — সব তৈরি করা যায় React দিয়ে।

---

## 🎮 ৭. শিখতে মজার এবং সহজ (যদি JS বেসিক জানা থাকে)

যদি আপনার **HTML, CSS, JavaScript বেসিক জানা থাকে**, তবে React শেখা হবে **সহজ ও মজার**।

---

## 🎁 অতিরিক্ত সুবিধা — রিয়েল প্রজেক্ট বানানো যায়

React শিখে আপনি এসব প্রজেক্ট করতে পারবেন:

* YouTube/UI Clone 🎥
* E-commerce ওয়েবসাইট 🛒
* অ্যাডমিন ড্যাশবোর্ড 📊
* সোশ্যাল মিডিয়া UI 💬
  👉 এগুলো করলে **পোর্টফোলিও শক্তিশালী হবে এবং ইন্টারভিউতে ভালো প্রভাব ফেলবে।**

---

## ✅ ছোট করে সারাংশ

> **React = দ্রুত ডেভেলপমেন্ট + বেশি চাকরি সুযোগ + ভালো বেতন + ফিউচার-প্রুফ স্কিল**

যদি লক্ষ্য থাকে **Frontend / Full Stack Developer হওয়া**, তাহলে React শেখা **অবশ্যই প্রয়োজনীয়**।

--
| লেভেল           | কী শিখবেন                                                 | আউটপুট                       |
| --------------- | --------------------------------------------------------- | ---------------------------- |
| 🔹 লেভেল 1      | React Environment Setup (VS Code, Node, Create React App) | প্রথম React প্রজেক্ট রান করা |
| 🔹 লেভেল 2      | JSX, Components, Props                                    | নিজের কম্পোনেন্ট বানানো      |
| 🔹 লেভেল 3      | useState, useEffect (Hooks)                               | ডাইনামিক UI                  |
| 🔹 লেভেল 4      | API Fetching (Axios / Fetch)                              | রিয়েল ডেটা নিয়ে কাজ          |
| 🔹 লেভেল 5      | Routing (React Router)                                    | মাল্টি-পেজ ওয়েবঅ্যাপ         |
| 🔹 লেভেল 6      | Context API / Redux                                       | স্টেট ম্যানেজমেন্ট           |
| 🔹 লেভেল 7      | Tailwind / Material UI                                    | প্রফেশনাল ডিজাইন             |
| 🎁 প্রজেক্ট ফেজ | ৪-৫টি রিয়েল প্রজেক্ট বানাবেন                              | পোর্টফোলিও তৈরি হবে          |
# React Initialize

## 🛠️ Step 0: Node.js আছে কি না (দ্রুত চেক)

টার্মিনালে চালান:

```bash
node -v
npm -v
```

ভার্সন দেখালে ঠিক আছে। না হলে Node LTS ইন্সটল করুন (nodejs.org থেকে)।

---

## 🚀 Step 1: Vite দিয়ে নতুন React প্রজেক্ট বানানো

টার্মিনালে লিখুন (আপনি যে ফোল্ডারে প্রজেক্ট রাখতে চান সেখানে):

```bash
npm create vite@latest my-react-app -- --template react
cd my-react-app
npm install
npm run dev
```

টার্মিনালে যে লোকাল ইউআরএল দেখাবে (যেমন: `http://localhost:5173`), সেটা ব্রাউজারে খুলুন। 🎉

> চাইলে TypeScript ব্যবহার করতে পারেন: `--template react-ts`

---

## 🧭 Step 2: প্রজেক্ট স্ট্রাকচার (সংক্ষেপে)

```
my-react-app/
├─ index.html
├─ package.json
├─ vite.config.js
└─ src/
   ├─ App.jsx
   ├─ main.jsx
   └─ assets/
```

* **main.jsx**: এখানে React অ্যাপ DOM-এ মাউন্ট হয়।
* **App.jsx**: আপনার অ্যাপের মূল কম্পোনেন্ট।

---

## ✍️ Step 3: প্রথম কম্পোনেন্ট লেখা (App.jsx আপডেট)

`src/App.jsx` ফাইলের কনটেন্ট বদলে দিন:

```jsx
import { useState } from "react";

export default function App() {
  const [count, setCount] = useState(0);

  return (
    <main style={{ fontFamily: "sans-serif", padding: 24 }}>
      <h1>হ্যালো React + Vite 👋</h1>
      <p>এটা আপনার প্রথম React অ্যাপ।</p>

      <button onClick={() => setCount(count + 1)}>
        ক্লিক করেছেন: {count} বার
      </button>
    </main>
  );
}
```

এখন পেজ রিফ্রেশ না করেই বাটনে ক্লিক করলে কাউন্টার বাড়তে দেখবেন—এটাই React-এর **re-render** ম্যাজিক।

---

## 🧩 Step 4: নিজের কম্পোনেন্ট বানানো (Props সহ)

`src/components/Button.jsx` নামে নতুন ফাইল বানান:

```jsx
export default function Button({ onClick, children }) {
  return (
    <button onClick={onClick} style={{ padding: "8px 14px", cursor: "pointer" }}>
      {children}
    </button>
  );
}
```

এবার `App.jsx` এ ব্যবহার করুন:

```jsx
import { useState } from "react";
import Button from "./components/Button";

export default function App() {
  const [count, setCount] = useState(0);

  return (
    <main style={{ fontFamily: "sans-serif", padding: 24 }}>
      <h1>কম্পোনেন্ট + Props ডেমো</h1>
      <p>ক্লিক: {count}</p>
      <Button onClick={() => setCount(count + 1)}>একটি কাস্টম বাটন</Button>
    </main>
  );
}
```

**বোঝা গেল?** `children` হল বাটনের ভিতরের টেক্সট, আর `onClick` হল ইভেন্ট হ্যান্ডলার।

---

## 🔀 Step 5: Routing যোগ করা (মাল্টি-পেজ ফিল)

ইন্সটল করুন:

```bash
npm install react-router-dom
```

`src/main.jsx` আপডেট:

```jsx
import React from "react";
import ReactDOM from "react-dom/client";
import { createBrowserRouter, RouterProvider } from "react-router-dom";
import App from "./App.jsx";

function About() {
  return <h2>About পেজ</h2>;
}

const router = createBrowserRouter([
  { path: "/", element: <App /> },
  { path: "/about", element: <About /> },
]);

ReactDOM.createRoot(document.getElementById("root")).render(
  <React.StrictMode>
    <RouterProvider router={router} />
  </React.StrictMode>
);
```

এখন ব্রাউজারে `/about` ভিজিট করলে নতুন পেজ দেখবেন।

---

## 🧪 Step 6: API থেকে ডেটা আনা (ছোট ডেমো)

`src/App.jsx`-এ একটি ফেচ উদাহরণ (ডেমো API):

```jsx
import { useEffect, useState } from "react";

export default function App() {
  const [posts, setPosts] = useState([]);

  useEffect(() => {
    // ডেমো: JSONPlaceholder
    fetch("https://jsonplaceholder.typicode.com/posts?_limit=5")
      .then(res => res.json())
      .then(data => setPosts(data));
  }, []);

  return (
    <main style={{ fontFamily: "sans-serif", padding: 24 }}>
      <h1>ফেচ করা ডেটা</h1>
      <ul>
        {posts.map(p => (
          <li key={p.id}><strong>{p.title}</strong></li>
        ))}
      </ul>
    </main>
  );
}
```

---
# JSX & Props

### 🔹 JSX কী?

JSX (JavaScript XML) হলো **React এ UI লেখার একটা syntax**। এটা দেখতে অনেকটা HTML এর মতো, কিন্তু আসলে JavaScript এর মধ্যে HTML-এর মতো কোড লেখার একটা উপায়।

👉 উদাহরণ:

```jsx
const element = <h1>Hello, World!</h1>;
```

এখানে `<h1>Hello, World!</h1>` দেখতে HTML মনে হলেও আসলে এটা JSX, যেটা React এর মাধ্যমে JavaScript এ কনভার্ট হয়।

**কেন JSX ব্যবহার করা হয়?**

* UI লেখা সহজ হয়।
* JavaScript এর লজিক HTML এর মতো স্ট্রাকচারের ভেতরে লিখতে সুবিধা হয়।
* কোড আরও readable হয়।

---

### 🔹 Props কী?

**Props (Properties)** হলো React এ **ডাটা পাস করার সিস্টেম**।
ধরা যাক তুমি এক জায়গায় একটা কম্পোনেন্ট বানালে, আর অন্য জায়গায় সেটা ব্যবহার করার সময় ভিন্ন ভিন্ন ডাটা পাঠাতে চাও—তখন props ব্যবহার করা হয়।

👉 উদাহরণ:

```jsx
function Welcome(props) {
  return <h1>Hello, {props.name}</h1>;
}

export default function App() {
  return (
    <div>
      <Welcome name="Rahim" />
      <Welcome name="Karim" />
    </div>
  );
}
```

**এখানে কী হচ্ছে?**

* `Welcome` নামের একটা component বানানো হয়েছে।
* `props.name` ব্যবহার করে dynamic টেক্সট দেখানো হচ্ছে।
* `App` component থেকে আমরা দুইবার `Welcome` ব্যবহার করেছি—একবার `name="Rahim"` আরেকবার `name="Karim"` দিয়েছি।
* ফলে UI তে দেখাবে:

  ```
  Hello, Rahim
  Hello, Karim
  ```

---

### 📌 JSX আর Props এর মূল পয়েন্ট

* **JSX** = JavaScript + HTML syntax।
* **Props** = Parent থেকে Child component এ ডাটা পাঠানোর সিস্টেম।
* Props **immutable** (মানে child component এর ভেতর থেকে props পরিবর্তন করা যায় না)।


একদম ঠিক 👍 এখন Props নিয়ে আরও ডিটেইলসে যাই, বিশেষ করে **Prop Types** আর কিভাবে **props পাস ও পড়া হয়** সেটা বাংলায় বোঝাই।

---

## 🔹 Props কীভাবে Pass করা হয়

Props হলো **Parent Component থেকে Child Component এ data পাঠানোর উপায়**।
Props সবসময় **attribute আকারে** পাঠানো হয়।

👉 উদাহরণ:

```jsx
function Welcome(props) {
  return <h1>Hello, {props.name}</h1>;
}

export default function App() {
  return (
    <div>
      <Welcome name="Rahim" />
      <Welcome name="Karim" />
    </div>
  );
}
```

এখানে `name="Rahim"` আর `name="Karim"` হলো Props।
Child component (`Welcome`) সেটা `props.name` দিয়ে access করছে।

---

## 🔹 Props পড়ার দুটি সাধারণ উপায়

1. **props অবজেক্ট ব্যবহার করে**

```jsx
function Welcome(props) {
  return <h1>Hello, {props.name}</h1>;
}
```

2. **Destructuring করে**

```jsx
function Welcome({ name }) {
  return <h1>Hello, {name}</h1>;
}
```

---

## 🔹 Prop Types (Type Checking এর জন্য)

React এ `prop-types` লাইব্রেরি ব্যবহার করে আমরা props এর ধরন (type) ঠিক করে দিতে পারি।
এতে component কে কোন ডাটা কী ধরনের হতে হবে সেটা বোঝানো যায়, আর ভুল হলে warning পাওয়া যায়।

👉 প্রথমে ইনস্টল করতে হবে:

```
npm install prop-types
```

👉 উদাহরণ:

```jsx
import PropTypes from "prop-types";

function UserCard({ name, age }) {
  return (
    <div>
      <h2>{name}</h2>
      <p>Age: {age}</p>
    </div>
  );
}

// PropTypes দিয়ে type define করা
UserCard.propTypes = {
  name: PropTypes.string.isRequired,
  age: PropTypes.number.isRequired,
};

export default UserCard;
```

---

### 🔹 এখানে কী হচ্ছে?

* `UserCard` component এ আমরা `name` (string) আর `age` (number) props চাই।
* `.isRequired` মানে এগুলো অবশ্যই দিতে হবে, না দিলে warning আসবে।
* যদি `age` এর জায়গায় string পাঠাই (যেমন `"twenty"`), React console এ warning দেবে।

---

## 📌 সারসংক্ষেপ

* Props → Parent থেকে Child এ data পাঠানোর সিস্টেম।
* Props পড়া যায় `props.object` দিয়ে অথবা destructuring করে।
* `prop-types` ব্যবহার করে props এর ধরন ঠিক করে দেওয়া যায় (যেমন `string`, `number`, `bool`, `array`, `object` ইত্যাদি)।

---
খুব ভালো প্রশ্ন! 🚀
চল এবার **Read-only Props** আর **Conditional Rendering** দুইভাবে কিভাবে করা যায় সেটা বাংলায় দেখে নেই।

---

## 🔹 Props হলো Read-only

React এ **Props immutable (পরিবর্তন করা যায় না)**।
মানে child component এর ভেতর থেকে props এর মান (value) বদলানো যাবে না।
👉 Props শুধু **পড়তে** পারবে, কিন্তু **লিখতে (change)** পারবে না।

👉 ভুল উদাহরণ (এভাবে করা যাবে না ❌):

```jsx
function User({ name }) {
  name = "Changed Name"; // ❌ props পরিবর্তন করা যাবে না
  return <h1>{name}</h1>;
}
```

👉 সঠিক উদাহরণ ✅:

```jsx
function User({ name }) {
  return <h1>{name}</h1>;
}
```

---

# 🔹 Conditional Rendering (শর্ত অনুযায়ী UI দেখানো)

React এ **দুইভাবে conditional rendering** করা যায়:

---

### 1. **if / else ব্যবহার করে**

```jsx
function Greeting({ isLoggedIn }) {
  if (isLoggedIn) {
    return <h1>Welcome Back!</h1>;
  } else {
    return <h1>Please Login</h1>;
  }
}
```

👉 এখানে যদি `isLoggedIn = true` হয় তবে "Welcome Back!" দেখাবে, না হলে "Please Login" দেখাবে।

---

### 2. **Ternary Operator ব্যবহার করে**

```jsx
function Greeting({ isLoggedIn }) {
  return (
    <h1>{isLoggedIn ? "Welcome Back!" : "Please Login"}</h1>
  );
}
```

👉 এখানে এক লাইনে condition চেক করা হয়েছে।

---

## 📌 সারসংক্ষেপ

* Props সবসময় **read-only** → শুধু ব্যবহার করা যায়, modify করা যায় না।
* Conditional rendering করা যায়:

  1. **if/else statement**
  2. **ternary operator (?:)**

---


# 🔹 কেন export / import দরকার?

React প্রজেক্টে কোড সাধারণত ছোট ছোট **component ফাইলে ভাগ করে রাখা হয়**।
যাতে প্রজেক্ট বড় হলেও মেইনটেইন করা সহজ হয়।
এক ফাইল থেকে অন্য ফাইলে component ব্যবহার করতে হলে **export** আর **import** করতে হয়।

---

## 🔹 Export এর ধরন

### 1. **Default Export**

একটা ফাইল থেকে শুধু **একটা জিনিস** default হিসেবে export করা যায়।
👉 উদাহরণ:

```jsx
// MyComponent.js
function MyComponent() {
  return <h1>Hello from MyComponent</h1>;
}

export default MyComponent;
```

👉 Import করার সময়:

```jsx
// App.js
import MyComponent from "./MyComponent";

function App() {
  return <MyComponent />;
}

export default App;
```

⚡ এখানে লক্ষ্য করো: import করার সময় **{} লাগছে না**, আর নাম যেকোনো দিতে পারো (যেমন `MyComponent` এর জায়গায় `HelloComp` লিখলেও চলবে)।

---

### 2. **Named Export**

একটা ফাইল থেকে **একাধিক জিনিস** export করা যায় named export দিয়ে।
👉 উদাহরণ:

```jsx
// utils.js
export function add(a, b) {
  return a + b;
}

export function multiply(a, b) {
  return a * b;
}
```

👉 Import করার সময়:

```jsx
import { add, multiply } from "./utils";

console.log(add(2, 3));       // 5
console.log(multiply(2, 3)); // 6
```

⚡ এখানে লক্ষ্য করো: import করার সময় **{} ব্যবহার করতে হবে**।
আর নাম অবশ্যই একই হতে হবে (`add` মানে `add`, `multiply` মানে `multiply`)।

---

### 3. **Default + Named একসাথে**

এক ফাইলে একটা default export + একাধিক named export থাকতে পারে।

👉 উদাহরণ:

```jsx
// helpers.js
export default function sayHello(name) {
  return `Hello, ${name}`;
}

export const PI = 3.1416;
export const VERSION = "1.0";
```

👉 Import করার সময়:

```jsx
import sayHello, { PI, VERSION } from "./helpers";

console.log(sayHello("Rahim")); // Hello, Rahim
console.log(PI);                // 3.1416
console.log(VERSION);           // 1.0
```

---

## 📌 সারসংক্ষেপ

* **Default Export** → একটাই export → import এ `{}` লাগে না।
* **Named Export** → অনেকগুলো export → import এ `{}` ব্যবহার করতে হয়।
* এক ফাইলে default + named দুটোই থাকতে পারে।

---


# React-এ **events handle করার জন্য বিভিন্ন উপায়** আছে। 

---

### ১. **Inline Event Handling**

এখানে সরাসরি JSX element-এর ভেতরেই event handler লিখে দেওয়া হয়।

```jsx
function App() {
  return (
    <button onClick={() => alert("Button Clicked!")}>
      Click Me
    </button>
  );
}
```

👉 সুবিধা: ছোটখাট কাজের জন্য দ্রুত ব্যবহার করা যায়।
👉 অসুবিধা: কোড বড় হলে পড়তে অসুবিধা হয়।

---

### ২. **Event Handler Function আলাদা করে লেখা**

Event handle করার জন্য function আলাদা করে লেখা হয়, তারপর JSX-এ reference দেওয়া হয়।

```jsx
function App() {
  const handleClick = () => {
    alert("Button Clicked!");
  };

  return (
    <button onClick={handleClick}>
      Click Me
    </button>
  );
}
```

👉 সুবিধা: কোড পরিষ্কার ও re-usable হয়।

---

### ৩. **Passing Arguments সহ Event Handler**

Event handler-এ argument পাঠানোর দরকার হলে arrow function ব্যবহার করা হয়।

```jsx
function App() {
  const handleClick = (name) => {
    alert(`Hello, ${name}`);
  };

  return (
    <button onClick={() => handleClick("Mamun")}>
      Click Me
    </button>
  );
}
```

👉 সুবিধা: ডাইনামিক ডেটা পাঠানো যায়।

---

### ৪. **Event Object ব্যবহার করা**

React event handler-এ default event object পাওয়া যায়, যেটা দিয়ে event সম্পর্কিত তথ্য বের করা যায়।

```jsx
function App() {
  const handleInput = (event) => {
    console.log("Input Value:", event.target.value);
  };

  return (
    <input type="text" onChange={handleInput} />
  );
}
```

👉 সুবিধা: user interaction সম্পর্কিত তথ্য (যেমন value, key, mouse position ইত্যাদি) পাওয়া যায়।

---

### ৫. **Class Component-এ Event Handling(Advanced)**

Class component-এ `this` binding দরকার হয়।

```jsx
class App extends React.Component {
  constructor() {
    super();
    this.handleClick = this.handleClick.bind(this);
  }

  handleClick() {
    alert("Button Clicked!");
  }

  render() {
    return <button onClick={this.handleClick}>Click Me</button>;
  }
}
```

👉 আধুনিক React-এ functional component বেশি ব্যবহার হয়, তবে class component-এ binding গুরুত্বপূর্ণ।

---

### ৬. **Event Handler as Props পাঠানো(Important)**

Parent থেকে child component-এ event handler পাঠানো যায়।

```jsx
function Child({ onButtonClick }) {
  return <button onClick={onButtonClick}>Click Me</button>;
}

function App() {
  const handleClick = () => {
    alert("Clicked from Child!");
  };

  return <Child onButtonClick={handleClick} />;
}
```

👉 সুবিধা: parent-child কমিউনিকেশন সহজ হয়।

---

### ৭. **Synthetic Events (React-এর own event system)**

React event গুলো **SyntheticEvent** দিয়ে manage করে, যেটা সব browser-এর জন্য একইভাবে কাজ করে।
(উদাহরণ: `onClick`, `onChange`, `onMouseOver` সব Synthetic Event)।

---

🔑 **সংক্ষেপে:**
React-এ event handling করা যায়

1. Inline
2. Function reference দিয়ে
3. Argument পাঠিয়ে
4. Event object ব্যবহার করে
5. Class component-এ binding করে
6. Props হিসেবে child এ পাঠিয়ে
7. React Synthetic Event system এর মাধ্যমে

---




# 🔹 State কী?

React-এ **state** হলো একটি বিশেষ ধরনের data storage, যেটা component-এর ভেতরে থাকে।
এটা **component-এর আচরণ ও UI (User Interface)** পরিবর্তন করতে ব্যবহার হয়।

👉 সহজভাবে বললে:
**State = Component-এর বর্তমান অবস্থা (data) যেটা সময়ের সাথে পরিবর্তন হতে পারে।**

---

## 🔹 State কেন দরকার?

* কোন ডেটা বারবার পরিবর্তিত হবে (যেমন: counter-এর সংখ্যা, input-এর মান, toggle on/off) সেটা state-এ রাখা হয়।
* যখন state পরিবর্তন হয়, তখন React আবার UI re-render করে যাতে নতুন state দেখা যায়।

---

## 🔹 State ব্যবহার করার নিয়ম (Functional Component)

React-এ সাধারণত `useState` hook দিয়ে state তৈরি ও পরিবর্তন করা হয়।

### Example 1: Counter

```jsx
import React, { useState } from "react";

function Counter() {
  const [count, setCount] = useState(0); // state initialize

  const increase = () => {
    setCount(count + 1); // state change
  };

  return (
    <div>
      <p>Count: {count}</p>
      <button onClick={increase}>Increase</button>
    </div>
  );
}

export default Counter;
```

### এখানে কী হচ্ছে?

1. `useState(0)` → শুরুতে state-এর মান 0
2. `count` → বর্তমান state value
3. `setCount` → state পরিবর্তন করার function
4. যখন `setCount` দিয়ে মান বদলাই, React UI আবার render করে নতুন মান দেখায়।

---

## 🔹 State-এর গুরুত্বপূর্ণ বিষয়

1. **Direct state change করা যাবে না**
   ❌ `count = count + 1` ভুল
   ✅ `setCount(count + 1)` ঠিক

2. **State asynchronous হতে পারে**
   মানে সাথে সাথে change দেখা না-ও যেতে পারে, React পেছনে manage করে।

3. **একই component-এ একাধিক state রাখা যায়**

```jsx
const [name, setName] = useState("Mamun");
const [age, setAge] = useState(22);
```

---

## 🔹 ছোট Example (Toggle Button)

```jsx
function ToggleButton() {
  const [isOn, setIsOn] = useState(false);

  return (
    <button onClick={() => setIsOn(!isOn)}>
      {isOn ? "ON" : "OFF"}
    </button>
  );
}
```

👉 এখানে button চাপলে state change হয় (`true/false`) আর UI তৎক্ষণাৎ update হয়।

---

🔑 **সংক্ষেপে:**

* State হলো component-এর dynamic data।
* `useState` দিয়ে declare ও change করা হয়।
* State change করলে React UI আবার update করে।

---


# 🔹 React Hooks কী?

React প্রথমে Class Component-এ state ও lifecycle method দিয়ে কাজ করতো।
কিন্তু এগুলো একটু জটিল ছিলো।

👉 তাই React v16.8 থেকে **Hooks** এসেছে।
Hooks হলো **বিশেষ ধরনের function** যেগুলো React-এর ভিতরে built-in আছে এবং functional component-এ state, lifecycle, context ইত্যাদি ব্যবহার করতে দেয়।

**Hooks-এর উদাহরণ:**

* `useState` → state ম্যানেজ করার জন্য
* `useEffect` → side effect (API call, data fetch, timer ইত্যাদি) করার জন্য
* `useContext` → context ব্যবহার করার জন্য
* `useReducer`, `useRef`, `useMemo` ইত্যাদি

👉 সহজভাবে: **Hooks মানে shortcut function, যেগুলো দিয়ে functional component-এ আগের class component-এর সব ফিচার ব্যবহার করা যায়।**

---

# 🔹 useState কী?

**useState হলো সবচেয়ে বেশি ব্যবহৃত React Hook।**
এটা দিয়ে আমরা component-এর ভিতরে **state তৈরি ও update** করতে পারি।

---

## 📌 useState ব্যবহার করার syntax

```jsx
const [stateVariable, setStateFunction] = useState(initialValue);
```

* `stateVariable` → বর্তমান state এর মান রাখে।
* `setStateFunction` → state আপডেট করার জন্য function।
* `initialValue` → state-এর প্রথম মান (যেমন: সংখ্যা হলে 0, string হলে "" ইত্যাদি)।

---

## 📌 Example 1: Counter App

```jsx
import React, { useState } from "react";

function Counter() {
  const [count, setCount] = useState(0); // state declare

  const increase = () => {
    setCount(count + 1); // state update
  };

  return (
    <div>
      <p>Count: {count}</p>
      <button onClick={increase}>Increase</button>
    </div>
  );
}

export default Counter;
```

👉 এখানে:

* শুরুতে `count = 0`
* যখন button চাপি, `setCount(count + 1)` কল হয়
* React UI আবার re-render করে নতুন `count` দেখায়

---

## 📌 Example 2: Toggle Button

```jsx
function ToggleButton() {
  const [isOn, setIsOn] = useState(false);

  return (
    <button onClick={() => setIsOn(!isOn)}>
      {isOn ? "ON" : "OFF"}
    </button>
  );
}
```

👉 এখানে:

* শুরুতে state = `false` (মানে OFF)
* button চাপলে state উল্টে যায় (`true`/`false`)
* UI তে সাথে সাথে পরিবর্তন দেখা যায়।

---

# 🔹 useState সম্পর্কিত গুরুত্বপূর্ণ বিষয়

1. **State সরাসরি পরিবর্তন করা যাবে না**
   ❌ `count = count + 1`
   ✅ `setCount(count + 1)`

2. **State change করলে React component আবার render হয়**
   মানে UI update হয়।

3. **একটা component-এ একাধিক state থাকতে পারে**

```jsx
const [name, setName] = useState("Mamun");
const [age, setAge] = useState(22);
```

---

## 🔑 সংক্ষেপে:

* **Hooks** হলো React-এর special function, functional component-এ extra feature দেয়।
* **useState** হলো hook, যেটা দিয়ে state create ও update করা হয়।
* State পরিবর্তন করলে UI আবার update হয়।

---

“`use()` hook” React-এর একটি নতুন API যা React 19 থেকে পাওয়া যাচ্ছে। এটি Promise বা context থেকে সরলভাবে value পড়তে দেয়, এবং Suspense ও error boundary-এর সঙ্গে কাজ করে। ([React][1])

নিচে “use()” hook-এর কার্যকর ধাপ, সুবিধা ও উদাহরণ বাংলায় ব্যাখ্যা দিলাম:

---

# 🔹 use() hook কী?

* `use(resource)` — এখানে `resource` হতে পারে **Promise** বা **context** ([React][1])
* যদি resource একটি Promise হয়, তাহলে component সেই Promise resolve না হওয়া পর্যন্ত “suspend” (অপেক্ষা) করবে, এবং Suspense fallback দেখাবে। ([React][1])
* যদি resource context হয়, তাহলে `use(context)` `useContext` মতোই কাজ করে, কিন্তু এটা loop / conditional এর ভিতরেও ব্যবহার করা যেতে পারে (যেখানে `useContext` ব্যবহার করা যায় না)। ([React][1])

---

## 🔹 use() কীভাবে কাজ করে?

| Resource ধরণ       | আচরণ (Behavior)                                             | ফলাফল                     |
| ------------------ | ----------------------------------------------------------- | ------------------------- |
| Promise            | যদি Promise এখনও resolve না হয় → component suspend হবে     | Suspense fallback দেখাবে  |
| Promise (rejected) | Promise reject হলে → nearest Error Boundary fallback দেখাবে | error UI                  |
| Context            | `use(context)` → সে context-এর current value return করবে    | যেমন `useContext` কাজ করে |

---

## 🔹 উদাহরণ

```jsx
import { use, Suspense } from 'react';

function Message({ messagePromise }) {
  const message = use(messagePromise);  // Promise resolve না হলে অপেক্ষা করবে
  return <p>Message: {message}</p>;
}

function App() {
  const messagePromise = fetch("/api/message").then(res => res.text());

  return (
    <Suspense fallback={<div>Loading message...</div>}>
      <Message messagePromise={messagePromise} />
    </Suspense>
  );
}
```

উপরের কোডে:

* `messagePromise` একটি Promise
* `Message` component-এ `use(messagePromise)` করি
* Promise resolve না হলে `Suspense` fallback দেখানো হবে
* Promise resolve হলে `message` পাঠিয়ে UI রেন্ডার করবে

---

## 🔹 use() ব্যবহার করার নিয়ম ও সতর্কতা

* `use()` **শুধুমাত্র** React Component বা Hook-এর ভিতর ব্যবহার করতে হবে ([React][1])
* `use()` কে loop, 조건 বা nested statements-এ ব্যবহার করা যাবে — এটি `useContext` এর ক্ষেত্রে সম্ভব নয় ([React][1])
* `use()` কে `try-catch` ব্লকে সরাসরি ব্যবহার করা যাবে না — error handling করতে হবে Error Boundary-র মাধ্যমে ([React][1])

---

**সারাংশ:**
“use()” একটি নতুন Hook যা Promise বা context থেকে সরাসরি value পড়তে দেয় এবং Suspense ও Error Boundary-এর সাথে natural ভাবে কাজ করে। এটি React-এর asynchronous data handling কে আরও সরল ও expressive করে তোলে।


# `useCallback` — সহজ ও পরিষ্কারভাবে বোঝানো যাক

`useCallback` হল React-এর একটি **Hook**, যেটা মূলত **function memoization** করার জন্য ব্যবহার করা হয়।

---

## 🎯 কেন `useCallback` লাগে?

React কম্পোনেন্ট **বারবার re-render** হলে প্রতিবার **নতুন function তৈরি** হয়।
এই ফাংশন যদি **child component-এ prop হিসেবে পাঠানো হয়**, তাহলে child-ও **অযথা re-render হবে**।

👉 `useCallback` এই সমস্যার সমাধান করে —
**একই dependency থাকলে আগের function-টাই রিটার্ন করে**, নতুন করে তৈরি করে না।

---

## 💡 সিনট্যাক্স

```jsx
const memoizedFunction = useCallback(() => {
  // logic here
}, [dependency]);
```

* ✅ যদি `dependency` **পরিবর্তন না হয়**, তাহলে React **নতুন ফাংশন তৈরি করবে না**।
* ⚡ Performance বৃদ্ধি পায়, especially বড় প্রোজেক্টে।

---

## 🔍 সহজ উদাহরণ

ধরে নেই আপনার একটা বাটন আছে, ও তার ক্লিক ফাংশন আপনি **child component-এ পাঠাচ্ছেন**।

### ❌ Without `useCallback`

```jsx
function Parent() {
  const handleClick = () => {
    console.log("Clicked");
  };

  return <Child onClick={handleClick} />;
}
```

👉 Parent রি-রেন্ডার হলেই **handleClick নতুন করে তৈরি হবে**, আর Child-ও রেন্ডার হবে।

---

### ✅ With `useCallback`

```jsx
import { useCallback } from "react";

function Parent() {
  const handleClick = useCallback(() => {
    console.log("Clicked");
  }, []); // dependency empty — মানে একবারই ফাংশন তৈরি হবে

  return <Child onClick={handleClick} />;
}
```

👉 Parent যতবার render হোক, **handleClick একই থাকবে** → **Child re-render হবে না**।

---

## 🎭 Child component যদি `React.memo` দিয়ে wrap করা থাকে

```jsx
const Child = React.memo(({ onClick }) => {
  console.log("Child render");
  return <button onClick={onClick}>Click</button>;
});
```

🌟 এখন Parent রি-রেন্ডার হলেও Child re-render হবে না কারণ `onClick` ফাংশন **মেমোইজড**।

---

## ⚠️ কখন `useCallback` ব্যবহার করবেন না?

* **মাইক্রো ফাংশন হলে** (যেমন ছোট map/filter ভিতরে লেখা) ❌ লাগবে না।
* অকারণে useCallback ব্যবহার করলে Performance **খারাপ** হতে পারে কারণ React-কে **function memoize রাখতে আলাদা হিসাব রাখতে হয়**।

---

## 🎯 Golden Rule

> **"Function prop নিচে পাঠাচ্ছেন + React.memo child ব্যবহার করছেন → তখন `useCallback` ব্যবহার করুন"**

---



# 🔹 Suspense কী?

React-এ **Suspense** হলো একটি **built-in component** যা asynchronous কাজ (যেমন: data load হওয়া, lazy component load হওয়া ইত্যাদি) চলাকালীন সময়ে একটি fallback UI (যেমন: “Loading…”) দেখানোর জন্য ব্যবহার করা হয়।

👉 সহজভাবে বললে:
**Suspense = লোডিং বা অপেক্ষার সময় alternative UI দেখানোর উপায়।**

---

## 🔹 Syntax

```jsx
<Suspense fallback={<div>Loading...</div>}>
  <MyComponent />
</Suspense>
```

* `fallback` → এখানে যা দেওয়া হবে সেটা দেখাবে যতক্ষণ data/component লোড হচ্ছে।
* `MyComponent` → আসল component, যেটা asynchronous ভাবে data লোড করবে।

---

## 🔹 কোথায় Suspense ব্যবহার হয়?

1. **Lazy loading (React.lazy)** → Component on-demand লোড করতে।
2. **Data fetching (React 18+ with use & concurrent features)** → Promise resolve হওয়া পর্যন্ত অপেক্ষা করাতে।
3. **Server Components (React 18+)** → সার্ভার থেকে ডেটা আসার আগ পর্যন্ত UI ফাঁকা না রেখে কিছু দেখাতে।

---

## 🔹 Example 1: Lazy Loading

```jsx
import React, { Suspense, lazy } from "react";

const Profile = lazy(() => import("./Profile"));

function App() {
  return (
    <div>
      <h1>My App</h1>
      <Suspense fallback={<h2>Loading Profile...</h2>}>
        <Profile />
      </Suspense>
    </div>
  );
}

export default App;
```

👉 এখানে:

* `Profile` component lazy load হচ্ছে।
* যতক্ষণ না component লোড হয়, `Loading Profile...` দেখা যাবে।

---

## 🔹 Example 2: Suspense with Data Fetch (React 19 style)

```jsx
import { use, Suspense } from "react";

function Message({ messagePromise }) {
  const message = use(messagePromise); // Promise resolve না হওয়া পর্যন্ত suspend হবে
  return <p>{message}</p>;
}

function App() {
  const messagePromise = fetch("/api/message").then(res => res.text());

  return (
    <Suspense fallback={<div>Loading message...</div>}>
      <Message messagePromise={messagePromise} />
    </Suspense>
  );
}
```

👉 এখানে:

* `messagePromise` resolve না হওয়া পর্যন্ত **Suspense fallback** (Loading message...) দেখাবে।
* resolve হয়ে গেলে `Message` render হবে।

---

## 🔹 সংক্ষেপে:

* Suspense হলো React-এর **loading state manager**।
* Data বা Component লোড না হওয়া পর্যন্ত fallback UI দেখায়।
* React.lazy, data fetching, concurrent rendering—সব জায়গায় ব্যবহার হয়।

---




# 🧩 React-এ Style কীভাবে কাজ করে

React-এ আপনি HTML এর মতো `class` বা `id` ব্যবহার করতে পারেন, আবার সরাসরি **inline style** (অর্থাৎ `style` prop) দিয়েও CSS লিখতে পারেন।
তবে React-এর `style` prop একটু আলাদা — এটি একটি **JavaScript object** নেয়, সাধারণ CSS স্ট্রিং নয়।

---

## 🖊️ ১. Inline Style ব্যবহার

HTML এ যেমন লিখি:

```html
<h1 style="color: red; font-size: 20px;">Hello</h1>
```

React-এ একই কাজটি করতে হয় JavaScript object হিসেবে:

```jsx
<h1 style={{ color: "red", fontSize: "20px" }}>Hello</h1>
```

🔹 লক্ষ্য করুন —

* CSS property-গুলো **camelCase** ফরম্যাটে লেখা হয় (`font-size` → `fontSize`)
* মানগুলো **স্ট্রিং হিসেবে** দেওয়া হয় (যেমন `"20px"`)

---

## 🧱 ২. আলাদা Style Object ব্যবহার

বারবার style না লিখে আগে থেকেই একটি অবজেক্ট বানানো যায়:

```jsx
const headingStyle = {
  color: "blue",
  textAlign: "center",
  marginTop: "20px"
};

function App() {
  return <h1 style={headingStyle}>Welcome!</h1>;
}
```

এতে কোড আরও পরিষ্কার থাকে এবং একই style অনেক জায়গায় পুনরায় ব্যবহার করা যায়।

---

## 🎨 ৩. Conditional Style (শর্ত অনুযায়ী স্টাইল)

React-এ আপনি **শর্ত অনুযায়ী style পরিবর্তন** করতে পারেন:

```jsx
function Product({ available }) {
  return (
    <div
      style={{
        color: available ? "green" : "gray",
        fontWeight: available ? "bold" : "normal",
      }}
    >
      {available ? "In Stock" : "Sold Out"}
    </div>
  );
}
```

➡️ এখানে যদি `available` true হয়, তাহলে সবুজ bold টেক্সট দেখাবে, না হলে ধূসর সাধারণ টেক্সট।

---

## 🧩 ৪. Multiple Styles Merge করা

একাধিক style object একত্রেও ব্যবহার করা যায়:

```jsx
const baseStyle = { color: "white", padding: "10px" };
const dangerStyle = { backgroundColor: "red" };

<div style={{ ...baseStyle, ...dangerStyle }}>Warning</div>;
```

এখানে `...` স্প্রেড অপারেটর ব্যবহার করে দুইটি স্টাইল একত্র করা হয়েছে।

---

## 🧠 ৫. বিকল্প: CSS File বা CSS Modules

Inline style ছাড়াও আপনি চাইলে:

* আলাদা `.css` ফাইল লিখে `import './App.css'` করতে পারেন
* অথবা `CSS Modules` ব্যবহার করতে পারেন (যেমন `App.module.css`)

এগুলো বড় প্রজেক্টে maintain করা সহজ হয়।

---

## ✅ সংক্ষিপ্ত সারাংশ

| বিষয়                  | বর্ণনা                                           |
| --------------------- | ------------------------------------------------ |
| **Style prop**        | JavaScript object হিসেবে CSS লেখা হয়             |
| **Property নাম**      | camelCase (যেমন `backgroundColor`)               |
| **Value টাইপ**        | সাধারণত স্ট্রিং (`"10px"`, `"red"`)              |
| **Conditional style** | টার্নারি অপারেটর (`condition ? style1 : style2`) |
| **Reusable style**    | আলাদা ভ্যারিয়েবলে সংরক্ষণ করা যায়                |

দারুণ! প্রতিশ্রুত তুলনামূলক সারাংশটা দিলাম—সংক্ষেপে, বাংলায় 👇

# React-এ স্টাইল করার জনপ্রিয় পদ্ধতি (তুলনা)

| পদ্ধতি                             | কবে ব্যবহার ভাল                        | সুবিধা                            | সীমাবদ্ধতা                           | হালকা উদাহরণ                                                     |
| ---------------------------------- | -------------------------------------- | --------------------------------- | ------------------------------------ | ---------------------------------------------------------------- |
| **Inline style (`style={{...}}`)** | ছোট, ডাইনামিক, এক-দুই জায়গায়           | JS দিয়ে conditional/merge সহজ     | পসুডো-সিলেক্টর/মিডিয়া-কুয়েরি নেই     | `<div style={{color:'red',padding:'8px'}} />`                    |
| **সাধারণ CSS ফাইল**                | গ্লোবাল স্টাইল, ছোট-মিড প্রজেক্ট       | শেখা সহজ, ব্রাউজার-নেটিভ          | ক্লাসনেম কনফ্লিক্ট হতে পারে          | `import './App.css'` + `<div className="card" />`                |
| **CSS Modules**                    | কম্পোনেন্ট-স্কোপড স্টাইল               | নাম সংঘাত নেই, টাইপ-ফ্রেন্ডলি     | ক্লাস যোগ/শেয়ার কিছুটা ভার্বোজ       | `import s from './Box.module.css'; <div className={s.box} />`    |
| **Styled-components**              | ডাইনামিক থিমিং, বড় অ্যাপ              | props-ভিত্তিক স্টাইল, থিম সাপোর্ট | রানটাইম কস্ট, লার্জ বান্ডেলে ওভারহেড | `const Btn=styled.button\`color:${p=>p.primary?'#fff':'#222'};`` |
| **Emotion**                        | Styled-components-এর মতো কিন্তু হাল্কা | CSS prop/Styled API দুটোই         | কনফিগ লাগতে পারে                     | `<div css={{color:'hotpink'}} />`                                |
| **Tailwind CSS**                   | দ্রুত UI প্রোটোটাইপ/প্রড               | Utility-first, ছোট CSS আউটপুট     | ক্লাস লম্বা হতে পারে                 | `<div className="p-4 bg-slate-100 rounded-xl" />`                |

## Conditional স্টাইল/ক্লাস—দুটি দ্রুত প্যাটার্ন

**Inline (জাভাস্ক্রিপ্ট অবজেক্ট):**

```jsx
<div style={{ color: inStock ? 'green' : 'gray', fontWeight: inStock ? 700 : 400 }}>
  {inStock ? 'In Stock' : 'Sold Out'}
</div>
```

**className টগল (`clsx` বা `classnames`):**

```bash
npm i clsx
```

```jsx
import clsx from "clsx";

<div className={clsx("btn", isPrimary && "btn--primary", disabled && "opacity-50")}>
  Buy
</div>
```

## মিডিয়া কুয়েরি দরকার?

* **Inline** এ সরাসরি নেই; সাধারণত CSS/CSS Modules/Styled-components/Tailwind ব্যবহার করুন।
* **Styled-components**:

```jsx
const Card = styled.div`
  padding: 16px;
  @media (min-width: 1024px) { padding: 24px; }
`;
```

* **Tailwind**: `p-4 lg:p-6`



# 🧠 Lift Up State (স্টেট উপরে তোলা)

React-এ **state** সাধারণত কোনো এক কম্পোনেন্টের মধ্যে থাকে। কিন্তু যদি একাধিক কম্পোনেন্ট সেই state ব্যবহার করতে চায়, তখন সেটাকে নিচে না রেখে **একটা common parent কম্পোনেন্টে তুলে দেওয়া হয়** — একে বলে **lifting up the state**।

#### 🧩 উদাহরণ:

ধরা যাক, তোমার দুটি কম্পোনেন্ট আছে — `InputBox` এবং `DisplayBox`। দুটোই একই ডেটা নিয়ে কাজ করবে।

যদি `InputBox`-এর ভেতরে state রাখা হয়, তাহলে `DisplayBox` সেটা পাবে না।
তাই আমরা state-টাকে তাদের parent কম্পোনেন্টে তুলে দিই।

```jsx
function Parent() {
  const [text, setText] = useState('');

  return (
    <>
      <InputBox text={text} setText={setText} />
      <DisplayBox text={text} />
    </>
  );
}

function InputBox({ text, setText }) {
  return <input value={text} onChange={(e) => setText(e.target.value)} />;
}

function DisplayBox({ text }) {
  return <p>{text}</p>;
}
```

➡️ এখানে `text` state `Parent`-এ তোলা হয়েছে — অর্থাৎ **state lifted up** হয়েছে।

---

### ⚙️ Pass Handler as Props (হ্যান্ডলার প্রপ হিসেবে পাঠানো)

যখন নিচের কোনো কম্পোনেন্টে কোনো ইভেন্ট (যেমন ক্লিক, ইনপুট) হ্যান্ডেল করতে হয়, তখন parent কম্পোনেন্ট থেকে একটা **handler function** নিচে **props হিসেবে পাঠানো** হয়।
এভাবে নিচের কম্পোনেন্ট parent-এর state পরিবর্তন করতে পারে।

#### 🧩 উদাহরণ:

```jsx
function Parent() {
  const [count, setCount] = useState(0);

  const handleIncrement = () => setCount(count + 1);

  return (
    <>
      <CounterDisplay count={count} />
      <CounterButton onIncrement={handleIncrement} />
    </>
  );
}

function CounterDisplay({ count }) {
  return <h2>{count}</h2>;
}

function CounterButton({ onIncrement }) {
  return <button onClick={onIncrement}>+</button>;
}
```

➡️ এখানে `handleIncrement` ফাংশনটা **Parent** থেকে **props** হিসেবে **CounterButton**-এ পাঠানো হয়েছে — মানে **handler passed as prop**।

---

### 💡 সারসংক্ষেপ

| ধারণা                     | কাজ                                                                                       |
| ------------------------- | ----------------------------------------------------------------------------------------- |
| **Lift up state**         | একাধিক কম্পোনেন্টে শেয়ার করার জন্য state কে parent-এ তোলা                                 |
| **Pass handler as props** | নিচের কম্পোনেন্টে parent-এর ফাংশন পাঠানো, যাতে নিচের কম্পোনেন্ট event হ্যান্ডেল করতে পারে |


ঠিক আছে 😊 — আমি সহজভাবে বুঝিয়ে দিচ্ছি।

---

### 🎈 ১. React কীভাবে state চিনে?

React **state** বদলেছে কিনা বুঝতে “reference” দেখে।
মানে — আগের ডেটার জায়গা (মেমোরিতে) বদলেছে কি না।

যদি আপনি পুরনো জায়গায়ই ডেটা বদলান, React বুঝতে পারে না যে কিছু পরিবর্তন হয়েছে।

---

### 🚫 ভুল পদ্ধতি:

```jsx
const [numbers, setNumbers] = useState([1, 2, 3]);

numbers.push(4);
setNumbers(numbers); // ❌ React বুঝবে না state বদলেছে
```

এখানে `numbers` একই জায়গায় রয়ে গেছে (পুরনো reference)।
তাই React কিছুই আপডেট করবে না।

---

### ✅ সঠিক পদ্ধতি:

```jsx
setNumbers([...numbers, 4]); // ✅ নতুন অ্যারে তৈরি হচ্ছে
```

এখানে আমরা নতুন অ্যারে বানিয়েছি (`[...]`)।
তাই React দেখে — “আচ্ছা, state বদলেছে!”
এবং UI আপডেট করে।

---

### 💡 "Lift up state" মানে কী?

ধরুন, দুইটা child component আছে — দুজনেই একই ডেটা ব্যবহার করবে।

তখন সেই ডেটা (state) **parent component**-এ রাখা হয়।
এটাই বলে **lift up state**।

---

### 🧩 উদাহরণ:

```jsx
function Parent() {
  const [count, setCount] = useState(0);

  return (
    <>
      <ChildA count={count} setCount={setCount} />
      <ChildB count={count} />
    </>
  );
}

function ChildA({ count, setCount }) {
  return <button onClick={() => setCount(count + 1)}>Add</button>;
}

function ChildB({ count }) {
  return <p>Count: {count}</p>;
}
```

👉 এখানে `count` state **Parent** এ আছে,
কিন্তু দুইটা Child — A আর B — উভয়েই সেটা ব্যবহার করছে।

এটাই “lifting up state”।

---

### 🪄 এক কথায়:

| বিষয়                 | মানে                                                                       |
| -------------------- | -------------------------------------------------------------------------- |
| React state আপডেট হয় | যখন নতুন reference (নতুন অবজেক্ট বা অ্যারে) তৈরি হয়                        |
| সরাসরি পরিবর্তন করলে | React বুঝতে পারে না                                                        |
| Lift up state        | একাধিক component যেন একই state শেয়ার করতে পারে, তাই state parent এ তোলা হয় |

---


## 🧩 সম্পূর্ণ কোড একবার দেখি

```jsx
import { useState } from "react";

function Parent() {
  const [items, setItems] = useState(["Apple", "Banana"]);

  return (
    <div>
      <h2>Parent Component 🍎</h2>
      <AddItem items={items} setItems={setItems} />
      <ShowItems items={items} />
    </div>
  );
}

function AddItem({ items, setItems }) {
  const addItemWrong = () => {
    // ❌ ভুল উপায় — একই reference ব্যবহার হচ্ছে
    items.push("Mango");
    setItems(items);
  };

  const addItemRight = () => {
    // ✅ সঠিক উপায় — নতুন reference তৈরি হচ্ছে
    setItems([...items, "Mango"]);
  };

  return (
    <div>
      <button onClick={addItemWrong}>Add (Wrong Way)</button>
      <button onClick={addItemRight}>Add (Right Way)</button>
    </div>
  );
}

function ShowItems({ items }) {
  return (
    <ul>
      {items.map((item, i) => (
        <li key={i}>{item}</li>
      ))}
    </ul>
  );
}

export default Parent;
```

---

## 🧠 ধাপে ধাপে ব্যাখ্যা

### ১️⃣ `Parent` কম্পোনেন্ট

এটা মূল (parent) কম্পোনেন্ট যেখানে state রাখা আছে।

```jsx
const [items, setItems] = useState(["Apple", "Banana"]);
```

👉 এখানে `items` হচ্ছে state আর `setItems` হচ্ছে সেই state আপডেট করার ফাংশন।
শুরুতে state-এর মান হলো `["Apple", "Banana"]`।

তারপর এই state-টা **দুইটি child component**-এ পাঠানো হচ্ছে props দিয়ে:

```jsx
<AddItem items={items} setItems={setItems} />
<ShowItems items={items} />
```

---

### ২️⃣ `AddItem` কম্পোনেন্ট

এটা এমন একটা কম্পোনেন্ট যেটা state পরিবর্তন করে — মানে নতুন ফল যোগ করে।

এখানে দুটি ফাংশন আছে:

#### 🔴 ভুল উপায়:

```jsx
items.push("Mango");
setItems(items);
```

এখানে `push()` দিয়ে আগের অ্যারে-তেই “Mango” যোগ করা হচ্ছে।
কিন্তু নতুন অ্যারে তৈরি করা হয়নি।
👉 তাই React ভাবে “state তো একই reference-এ আছে”, ফলে UI আপডেট হয় না।

---

#### 🟢 সঠিক উপায়:

```jsx
setItems([...items, "Mango"]);
```

এখানে `...items` মানে হচ্ছে আগের সব উপাদান নিয়ে একটা **নতুন অ্যারে** তৈরি করা।
নতুন অ্যারে মানে নতুন **reference**।
👉 React বুঝে যায় state বদলেছে, তাই রি-রেন্ডার করে।

---

### ৩️⃣ `ShowItems` কম্পোনেন্ট

এই কম্পোনেন্ট শুধু state দেখায়।

```jsx
<ul>
  {items.map((item, i) => (
    <li key={i}>{item}</li>
  ))}
</ul>
```

প্রতিবার যখন state আপডেট হয়, React এই component আবার রেন্ডার করে
এবং নতুন লিস্ট দেখায়।

---

### ৪️⃣ সব মিলিয়ে কী শিখলাম

| বিষয়                        | ব্যাখ্যা                                                              |
| --------------------------- | --------------------------------------------------------------------- |
| **State reference**         | React state পরিবর্তন হয়েছে কিনা বুঝতে reference দেখে।                 |
| **Mutable update (ভুল)**    | পুরনো অ্যারে বা অবজেক্ট সরাসরি বদলালে React বুঝবে না।                 |
| **Immutable update (সঠিক)** | নতুন reference তৈরি করলে React state পরিবর্তন বুঝে যায়।               |
| **Lift up state**           | একাধিক কম্পোনেন্টে একই state ব্যবহার করতে হলে, সেটা parent-এ তোলা হয়। |

---

### 🧩 বাস্তবে কিভাবে বুঝবে এটা হচ্ছে?

👉 “Add (Wrong Way)” ক্লিক করলে কিছু হবে না (React বুঝবে না)।
👉 “Add (Right Way)” ক্লিক করলে নতুন আইটেম দেখা যাবে (React রি-রেন্ডার করবে)।



# ব্রাউজারে Local Storage কী? (বাংলায় সহজভাবে ব্যাখ্যা)

**Local Storage** হলো ব্রাউজারের একটি বিশেষ জায়গা যেখানে ওয়েবসাইটগুলো আপনার কম্পিউটারে ডেটা সংরক্ষণ করতে পারে।
এই ডেটা আপনি ব্রাউজার বন্ধ করলেও রয়ে যায় — মানে, **স্থায়ীভাবে সেভ থাকে** যতক্ষণ না আপনি ম্যানুয়ালি মুছে দেন বা কোড থেকে ডিলিট করা হয়।

---

### কেন Local Storage ব্যবহার করা হয়?

* **User Settings সংরক্ষণ করার জন্য** (যেমন: ডার্ক মোড চালু আছে কি না)
* **Form data সাময়িকভাবে সেভ করার জন্য**
* **ছোটখাটো ডেটা রাখার জন্য**, যাতে সার্ভারে বারবার রিকোয়েস্ট পাঠাতে না হয়
* **Login token (JWT)** রাখতে, যাতে ইউজার বারবার লগইন করতে না হয়

---

### Local Storage এর বৈশিষ্ট্য

| বৈশিষ্ট্য      | ব্যাখ্যা                             |
| -------------- | ------------------------------------ |
| Data Limit     | সাধারণত 5MB পর্যন্ত ডেটা রাখা যায়    |
| Persistence    | ব্রাউজার বন্ধ করলেও ডেটা থাকে        |
| Key-Value Pair | ডেটা রাখা হয় **key: value** ফরম্যাটে |
| Only String    | শুধু **string ডেটা** সেভ করা যায়     |

---

### সহজ উদাহরণ (JavaScript দিয়ে)

```js
// ডেটা সেভ করা
localStorage.setItem("name", "Mamun");

// ডেটা পড়া
let userName = localStorage.getItem("name");

// ডেটা রিমুভ করা
localStorage.removeItem("name");

// সব ডেটা মুছে ফেলা
localStorage.clear();
```

---

### সংক্ষিপ্তভাবে বোঝার টিপস

👉 Local Storage = ব্রাউজারের **ছোটো ডেটাবেজ**
👉 ডেটা **browser-এ সেভ থাকে**, সার্ভারে না
👉 **Auto-delete হয় না**, নিজে মুছতে হবে

দারুন! তাহলে চলুন দুইটা বিষয় একে একে সহজভাবে বুঝি:

---

## ✅ 1. Local Storage vs Session Storage — পার্থক্য (বাংলায় সহজ তুলনা)

| বিষয়              | **Local Storage**                       | **Session Storage**                                 |
| ----------------- | --------------------------------------- | --------------------------------------------------- |
| ডেটা কত সময় থাকে | ব্রাউজার বন্ধ করলেও ডেটা থাকে (স্থায়ী) | ট্যাব বা ব্রাউজার বন্ধ করলে ডেটা মুছে যায়          |
| ব্যবহার ক্ষেত্র   | থিম, ইউজার সেটিংস, টোকেন ইত্যাদি        | ফর্ম ডেটা, এক পেজ থেকে আরেক পেজে সাময়িক তথ্য পাঠানো |
| ডেটা সাইজ লিমিট   | প্রায় **5MB**                          | তার কাছাকাছি, তবে Local Storage থেকে একটু কম        |
| শেয়ারিং           | একই ব্রাউজারে সব ট্যাবে ডেটা শেয়ার হয়   | শুধু **একই ট্যাবের মধ্যে সীমাবদ্ধ**                 |
| উদাহরণ            | `localStorage.setItem()`                | `sessionStorage.setItem()`                          |

👉 **মনে রাখার ট্রিক:**

* **Local = Long time**
* **Session = Short time (only current tab)**

---

## 🔍 5. ব্রাউজারে Data Storage — সবগুলো ধরনের ও ব্যাখ্যা

| Storage Type        | কোথায় ব্যবহার হয়                           | স্থায়িত্ব                       | সাইজ                             | নিরাপত্তা                                         |
| ------------------- | -------------------------------------------- | -------------------------------- | -------------------------------- | ------------------------------------------------- |
| **Cookies**         | পুরনো পদ্ধতি, সার্ভারে ডেটা পাঠায় সাথে সাথে | সাধারণত 7 দিন বা মেয়াদ অনুযায়ী | খুব ছোট (4KB)                    | কম নিরাপদ (XSS আক্রমণে leak হতে পারে)             |
| **Local Storage**   | ইউজার সেটিংস, টোকেন, থিম ইত্যাদি             | স্থায়ী                          | ~5MB                             | XSS-এ এক্সেস করা যায়                             |
| **Session Storage** | ফর্ম ডেটা, সাময়িক UI স্টেট                   | ট্যাব বন্ধ হলে মুছে যায়         | ~5MB এর কাছাকাছি                 | XSS-এ এক্সেস করা যায়                             |
| **IndexedDB**       | বড় অ্যাপ (যেমন: WhatsApp Web, PWA apps)     | স্থায়ী                          | **অনেক বেশি (শত MB+ও হতে পারে)** | Local Storage এর চেয়ে নিরাপদ এবং আরও স্ট্রাকচারড |

---

### সহজ উদাহরণ দিয়ে বোঝাই:

| বাস্তব উদাহরণ                                                                                      | কোন Storage ব্যবহার হবে              |
| -------------------------------------------------------------------------------------------------- | ------------------------------------ |
| আপনি একটি ওয়েবসাইটে **ডার্ক মোড অন করেন**, ব্রাউজার রিস্টার্ট করার পরও যেন থাকে                    | **Local Storage**                    |
| আপনি **checkout form fill করছেন**, পেজ reload হলেও যেন ডেটা থাকে কিন্তু ব্রাউজার বন্ধ করলে না থাকে | **Session Storage**                  |
| আপনি আবার সাইটে এসে লগইন না করেই ঢুকতে চান (remember me)                                           | **Cookies বা Local Storage-এ token** |
| আপনি ব্রাউজারে **WhatsApp বা Notion Offline mode** ব্যবহার করছেন                                   | **IndexedDB**                        |

---

### 🎯 Summary সহজ ভাষায়

| Fake Dialog                                                                       | বোঝার কৌশল      |
| --------------------------------------------------------------------------------- | --------------- |
| **"ভাই, আমি বারবার reload দিলে ডেটা যেন থাকে কিন্তু browser close করলে না থাকে"** | Session Storage |
| **"Browser বন্ধ করলেও ডেটা যেন না হারায়"**                                        | Local Storage   |
| **"Server-এ অটো পাঠাবে ডেটা, খুব ছোটখাটো তথ্য"**                                  | Cookies         |
| **"অনেক বড় ডেটা রাখতে চাই, offline app বানানোর মতো"**                             | IndexedDB       |

---
# React-এ চার্ট তৈরি করা (বাংলায় সহজ গাইড)

## 🧩 ১. Recharts ইনস্টল করা

Recharts হলো React-এর জন্য একটি জনপ্রিয় চার্ট লাইব্রেরি।

টার্মিনালে লিখো:

```bash
npm install recharts
```

---

## 🧠 ২. সাধারণ উদাহরণ (Simple Line Chart)

`App.js` বা অন্য কোনো কম্পোনেন্টে নিচের কোড দাও 👇

```jsx
import React from "react";
import {
  LineChart,
  Line,
  XAxis,
  YAxis,
  CartesianGrid,
  Tooltip,
  Legend
} from "recharts";

const data = [
  { name: "জানুয়ারি", sales: 4000 },
  { name: "ফেব্রুয়ারি", sales: 3000 },
  { name: "মার্চ", sales: 5000 },
  { name: "এপ্রিল", sales: 2500 },
];

const App = () => {
  return (
    <div style={{ textAlign: "center" }}>
      <h2>মাসভিত্তিক বিক্রির চার্ট</h2>
      <LineChart width={500} height={300} data={data}>
        <CartesianGrid strokeDasharray="3 3" />
        <XAxis dataKey="name" />
        <YAxis />
        <Tooltip />
        <Legend />
        <Line type="monotone" dataKey="sales" stroke="#82ca9d" />
      </LineChart>
    </div>
  );
};

export default App;
```

👉 এই কোডে:

* `data` হলো চার্টের তথ্য।
* `LineChart` হলো মূল চার্ট কন্টেইনার।
* `Line` হলো লাইনের ডেটা প্রদর্শনের জন্য।
* `Tooltip`, `Legend` চার্টে অতিরিক্ত তথ্য দেখায়।

---

## 📊 ৩. Bar Chart উদাহরণ

```jsx
import { BarChart, Bar, XAxis, YAxis, Tooltip, Legend, CartesianGrid } from "recharts";

const data = [
  { name: "জানুয়ারি", profit: 2400 },
  { name: "ফেব্রুয়ারি", profit: 1398 },
  { name: "মার্চ", profit: 9800 },
  { name: "এপ্রিল", profit: 3908 },
];

export default function ProfitChart() {
  return (
    <BarChart width={500} height={300} data={data}>
      <CartesianGrid strokeDasharray="3 3" />
      <XAxis dataKey="name" />
      <YAxis />
      <Tooltip />
      <Legend />
      <Bar dataKey="profit" fill="#8884d8" />
    </BarChart>
  );
}
```

---

## 🌈 ৪. চার্টের ধরনসমূহ

Recharts-এ আরও অনেক ধরণের চার্ট রয়েছে:

* LineChart
* BarChart
* PieChart
* AreaChart
* RadarChart
* ComposedChart

---

## 🚀 ৫. Chart.js ব্যবহার করতে চাইলে

তুমি চাইলে **Chart.js** এবং **react-chartjs-2** ব্যবহার করতে পারো:

```bash
npm install chart.js react-chartjs-2
```

তারপর উদাহরণ:

```jsx
import { Line } from "react-chartjs-2";

const data = {
  labels: ["জানুয়ারি", "ফেব্রুয়ারি", "মার্চ", "এপ্রিল"],
  datasets: [
    {
      label: "বিক্রি",
      data: [4000, 3000, 5000, 2500],
      borderColor: "blue",
      fill: false,
    },
  ],
};

export default function MyChart() {
  return <Line data={data} />;
}
```

# **SPA (Single Page Application) এর পরিচয় – বাংলায় ব্যাখ্যা**

---

### 🧩 **SPA কী?**

SPA বা **Single Page Application** হলো এমন একটি ওয়েব অ্যাপ্লিকেশন বা ওয়েবসাইট, যেখানে ব্যবহারকারী যখন নতুন কোনো পৃষ্ঠা বা কনটেন্টে যায়, তখন পুরো ওয়েবপেজটি রিলোড হয় না। বরং একই পৃষ্ঠার মধ্যে **JavaScript** (বিশেষ করে frameworks যেমন React, Vue, Angular) ব্যবহার করে কনটেন্টটি ডাইনামিকভাবে পরিবর্তন করা হয়।

📘 সহজভাবে বললে:
SPA একবার সার্ভার থেকে পুরো অ্যাপ্লিকেশন লোড করে নেয়, এরপর ব্যবহারকারী যখন কিছু ক্লিক করে, তখন শুধু প্রয়োজনীয় অংশটুকু পরিবর্তিত হয় — পুরো পেজ নতুন করে লোড হয় না।

---

### ⚙️ **SPA কীভাবে কাজ করে**

1. **Initial Load:**
   প্রথমবার SPA লোড হওয়ার সময় সার্ভার থেকে HTML, CSS, এবং JavaScript ফাইলগুলো ডাউনলোড হয়।

2. **Client-Side Routing:**
   ব্যবহারকারী যখন অ্যাপের ভিতরে বিভিন্ন পৃষ্ঠায় যায় (যেমন /home, /about, /contact), তখন JavaScript URL পরিবর্তন করে কিন্তু সার্ভারে নতুন অনুরোধ পাঠায় না।

3. **Data Fetching:**
   প্রয়োজন হলে কেবল **API call** করে সার্ভার থেকে নতুন ডেটা আনে, এবং সেটি পেজে দেখায়।

---

### 💡 **SPA এর সুবিধা**

* ⚡ **দ্রুত লোড হয়:** একবার লোড হওয়ার পর পেজ পরিবর্তনে রিলোড লাগে না।
* 💻 **Better User Experience:** নেভিগেশন মসৃণ ও ফ্লুইড লাগে।
* 🧠 **Less Server Load:** সার্ভারকে বারবার HTML পাঠাতে হয় না।
* 📱 **Mobile App-এর মতো অভিজ্ঞতা:** ওয়েব অ্যাপটিও অ্যাপের মতো লাগে।

---

### ⚠️ **SPA এর অসুবিধা**

* 🚫 **SEO সমস্যা:** যেহেতু পেজগুলো ডাইনামিকভাবে লোড হয়, সার্চ ইঞ্জিন ক্রলার সবসময় সঠিকভাবে ইনডেক্স করতে পারে না।
* 🕒 **Initial Load সময় বেশি:** প্রথমবার পুরো অ্যাপ লোড হতে সময় লাগে।
* 🔐 **Security ঝুঁকি:** Client-side logic বেশি থাকায় নিরাপত্তা সচেতনভাবে হ্যান্ডেল করতে হয়।
* ↩️ **Browser Back/Forward Navigation জটিল:** Routing ভালোভাবে হ্যান্ডেল না করলে ব্যাক বাটনে সমস্যা হয়।

---

### 🧰 **SPA তৈরি করার জন্য জনপ্রিয় Frameworks**

* **React.js**
* **Angular**
* **Vue.js**
* **Svelte**

---

### 🧠 **উদাহরণ**

যেমন, তুমি যখন **Gmail** বা **Facebook** ব্যবহার করো, তখন নতুন মেইল বা পোস্ট দেখতে পেজ রিফ্রেশ করতে হয় না — এগুলো SPA প্রযুক্তি ব্যবহার করে।



---

## 🧭 **প্রথমে ছোট তুলনা: SPA vs MPA**

| বিষয়                             | **SPA (Single Page Application)**                  | **MPA (Multi Page Application)**                  |
| -------------------------------- | -------------------------------------------------- | ------------------------------------------------- |
| পেজ লোড                          | একবার লোড হয়, পরে কনটেন্ট ডাইনামিকভাবে পরিবর্তন হয় | প্রতিবার নতুন পেজ সার্ভার থেকে লোড হয়             |
| স্পিড                            | দ্রুত (after first load)                           | তুলনামূলকভাবে ধীর                                 |
| SEO (Search Engine Optimization) | দুর্বল (বিশেষ কনফিগারেশন লাগবে)                    | ভালোভাবে কাজ করে                                  |
| ডেভেলপমেন্ট জটিলতা               | কম (একবারে ফ্রন্টএন্ড তৈরি করা যায়)                | বেশি (প্রতি পেজে আলাদা HTML ও সার্ভার রিকোয়েস্ট)  |
| Framework                        | React, Angular, Vue.js                             | Django, Laravel, Express.js, PHP, ASP.NET ইত্যাদি |
| ইউজার এক্সপেরিয়েন্স              | App-এর মতো মসৃণ                                    | ওয়েবসাইটের মতো সাধারণ                             |

---

## 🧩 **কখন SPA ব্যবহার করা উচিত**

SPA বেছে নেওয়া ভালো, যখন তোমার অ্যাপ্লিকেশনটা “ইন্টারঅ্যাকটিভ” বা “ওয়েব অ্যাপ” ধাঁচের হয় — যেমন ব্যবহারকারী ঘনঘন অ্যাপের ভিতরে কাজ করছে।

### ✅ **SPA ব্যবহারের উপযুক্ত ক্ষেত্র**

1. **ডাইনামিক অ্যাপ্লিকেশন:**
   যেমন Gmail, Facebook, Twitter — যেখানে একবার লোডের পর সব কাজ ক্লায়েন্ট সাইডে হয়।

2. **Dashboard বা Admin Panel:**
   যেমন Shopify Admin, Google Analytics Dashboard।

3. **Progressive Web App (PWA):**
   অফলাইনে কাজ করে এমন ওয়েব অ্যাপ।

4. **Real-time Data প্রয়োজন হয় এমন অ্যাপ:**
   যেমন চ্যাট অ্যাপ, ট্রেডিং প্যানেল, গেমিং ইন্টারফেস।

---

## 🏗️ **কখন MPA ব্যবহার করা উচিত**

MPA ভালো হয় এমন অ্যাপের জন্য যেখানে **SEO গুরুত্বপূর্ণ**, এবং প্রতিটি পেজের আলাদা কনটেন্ট থাকে।

### ✅ **MPA ব্যবহারের উপযুক্ত ক্ষেত্র**

1. **ই-কমার্স ওয়েবসাইট:**
   যেমন Amazon, Daraz — প্রতিটি প্রোডাক্টের আলাদা পেজ লাগে।

2. **ব্লগ বা নিউজ সাইট:**
   যেমন Prothom Alo, Medium — যেখানে প্রতিটি আর্টিকেল আলাদা URL-এ থাকে এবং সার্চ ইঞ্জিনে ইনডেক্স হওয়া দরকার।

3. **কর্পোরেট বা ইনফরমেশনাল ওয়েবসাইট:**
   যেমন কোম্পানির হোমপেজ, “About Us”, “Contact” ইত্যাদি।

4. **SEO-ফোকাসড ওয়েবসাইট:**
   যখন সার্চ ইঞ্জিন থেকে ট্রাফিক দরকার।

---

## ⚖️ **সারাংশে: সিদ্ধান্ত নেওয়ার গাইড**

| প্রশ্ন                                        | যদি উত্তর হয় "হ্যাঁ" → তাহলে       |
| --------------------------------------------- | ---------------------------------- |
| তুমি কি মোবাইল-অ্যাপের মতো ওয়েব অভিজ্ঞতা চাও? | **SPA ব্যবহার করো**                |
| তোমার কি সার্চ ইঞ্জিন থেকে ট্রাফিক দরকার?     | **MPA ব্যবহার করো**                |
| অ্যাপ কি রিয়েলটাইম ডেটা ব্যবহার করে?          | **SPA ব্যবহার করো**                |
| অ্যাপ কি অনেক আলাদা কনটেন্ট পেজ নিয়ে গঠিত?    | **MPA ব্যবহার করো**                |
| দ্রুত রেসপন্স দরকার?                          | **SPA ব্যবহার করো (with caching)** |

---

🔍 **সহজ উদাহরণ:**

* **SPA উদাহরণ:** Gmail, Facebook, Trello, Spotify Web
* **MPA উদাহরণ:** Wikipedia, Amazon, BBC News

চলো সহজ বাংলায় **React Router** এর ধারণাটা বুঝে নেওয়া যাক 👇

---
# React Router এর সহজ গাইড (বাংলায়)
### 🧭 React Router কী?

**React Router** হলো React-এর জন্য তৈরি একটি **routing লাইব্রেরি**, যা আমাদের **Single Page Application (SPA)**-এর মধ্যে বিভিন্ন পেজে যাতায়াত করতে সাহায্য করে **reload ছাড়াই**।
অর্থাৎ, তুমি যখন কোনো লিঙ্কে ক্লিক করো, তখন ব্রাউজার পুরো পেজটা নতুন করে লোড করে না — শুধু নির্দিষ্ট অংশ পরিবর্তন হয়।

---

### 🧩 কেন React Router দরকার?

React দিয়ে বানানো অ্যাপ সাধারণত একটাই HTML ফাইল ব্যবহার করে (index.html)।
তাই যদি আমরা "Home", "About", "Contact" ইত্যাদি আলাদা পেজ তৈরি করতে চাই, তাহলে আমাদের একটি **routing system** দরকার যা:

* URL অনুযায়ী নির্দিষ্ট component দেখাবে।
* ব্রাউজারে **Back/Forward button** সাপোর্ট করবে।
* পুরো অ্যাপ reload না করে **smooth navigation** দেবে।

এখানেই React Router কাজে আসে।

---

### ⚙️ কিভাবে কাজ করে?

React Router মূলত তিনটি গুরুত্বপূর্ণ জিনিস ব্যবহার করে 👇

1. **BrowserRouter** – এটি পুরো অ্যাপের জন্য routing সক্রিয় করে।
2. **Routes** – এটি একাধিক route (path) ধারণ করে।
3. **Route** – এটি নির্দিষ্ট করে দেয়, কোন path এ কোন component দেখানো হবে।

উদাহরণস্বরূপ 👇

```jsx
import { BrowserRouter, Routes, Route } from "react-router-dom";
import Home from "./Home";
import About from "./About";
import Contact from "./Contact";

function App() {
  return (
    <BrowserRouter>
      <Routes>
        <Route path="/" element={<Home />} />
        <Route path="/about" element={<About />} />
        <Route path="/contact" element={<Contact />} />
      </Routes>
    </BrowserRouter>
  );
}

export default App;
```

এখানে:

* `/` → Home component দেখাবে
* `/about` → About component দেখাবে
* `/contact` → Contact component দেখাবে

---

### 🔗 Navigation (Link ব্যবহার)

React Router-এ **`<a>` ট্যাগের বদলে `<Link>`** ব্যবহার করা হয়, যাতে পেজ reload না হয়।

```jsx
import { Link } from "react-router-dom";

function Navbar() {
  return (
    <nav>
      <Link to="/">Home</Link>
      <Link to="/about">About</Link>
      <Link to="/contact">Contact</Link>
    </nav>
  );
}
```

---

### 🧠 গুরুত্বপূর্ণ কনসেপ্টসমূহ

* **useNavigate()** → প্রোগ্রাম্যাটিকভাবে অন্য route-এ যেতে ব্যবহৃত হয়।
* **useParams()** → URL থেকে ডাইনামিক প্যারামিটার নিতে ব্যবহৃত হয়।
  যেমন `/user/:id` রুটে গেলে `useParams()` দিয়ে `id` পাওয়া যায়।
* **Nested Routes** → এক রুটের ভিতরে আরেকটি রুট বসানো যায়।

---

### 💡 সারসংক্ষেপ

| বিষয়                  | ব্যাখ্যা                             |
| --------------------- | ------------------------------------ |
| React Router          | SPA-তে navigation এর জন্য ব্যবহৃত হয় |
| BrowserRouter         | Routing system চালু করে              |
| Route                 | Path অনুযায়ী component দেখায়         |
| Link                  | Reload ছাড়া পেজ পরিবর্তন করে         |
| useNavigate/useParams | Navigation ও URL data নিয়ন্ত্রণ করে  |




---
# React-এ Form Data নেওয়ার সহজ গাইড (বাংলায়)
## 🧠 ধাপ ১: `onSubmit` কী করে?

`onSubmit` হলো **form-এর submit event** হ্যান্ডলার।
যখন একজন ব্যবহারকারী form-এর **Submit** বাটনে ক্লিক করে বা Enter চাপ দেয়, তখন `onSubmit` ফাংশনটি চলে।

উদাহরণ:

```jsx
<form onSubmit={handleSubmit}>
  <input type="text" name="username" />
  <input type="email" name="email" />
  <button type="submit">Submit</button>
</form>
```

এখানে `handleSubmit` একটি ফাংশন, যা `onSubmit` ট্রিগার হলে চালু হবে।

---

## ⚙️ ধাপ ২: `e` বা `event` কী?

`e` হলো **event object**, যা ব্রাউজার স্বয়ংক্রিয়ভাবে দেয় যখন কোনো ইভেন্ট ঘটে (যেমন form submit হয়)।
এতে form-এর সমস্ত তথ্য, event type, target element ইত্যাদি থাকে।

---

## 🧩 ধাপ ৩: `e.target` কীভাবে কাজ করে?

`e.target` মূলত সেই **HTML element** নির্দেশ করে যেটিতে ইভেন্টটি ঘটেছে — এই ক্ষেত্রে পুরো form element।

তাই আপনি `e.target.elements` বা সরাসরি `e.target.<input-name>.value` ব্যবহার করে ইনপুট ভ্যালু নিতে পারেন।

উদাহরণ:

```jsx
function handleSubmit(e) {
  e.preventDefault(); // form রিলোড বন্ধ করে

  const name = e.target.username.value;
  const email = e.target.email.value;

  console.log("Name:", name);
  console.log("Email:", email);
}
```

---

## 🧾 ধাপ ৪: সহজ বাংলা ব্যাখ্যা

1. `onSubmit` — form সাবমিট হলে যেই ফাংশন চলে।
2. `e.preventDefault()` — পেজ রিলোড হওয়া বন্ধ করে।
3. `e.target` — পুরো form element বোঝায়।
4. `e.target.name.value` — form-এর নির্দিষ্ট input এর মান নেয়।

---

## ✅ সম্পূর্ণ উদাহরণ (বাংলায় মন্তব্যসহ)

```jsx
import React from "react";

function MyForm() {
  const handleSubmit = (e) => {
    e.preventDefault(); // ডিফল্ট রিফ্রেশ বন্ধ করা হলো

    const username = e.target.username.value;
    const email = e.target.email.value;

    alert(`নাম: ${username}\nইমেইল: ${email}`);
  };

  return (
    <form onSubmit={handleSubmit}>
      <input type="text" name="username" placeholder="নাম লিখুন" />
      <input type="email" name="email" placeholder="ইমেইল লিখুন" />
      <button type="submit">সাবমিট</button>
    </form>
  );
}

export default MyForm;
```

# React-এ FormData এবং Controlled Component এর সহজ গাইড (বাংলায়)

## 🧩 ধাপ ১: Form action কী?

React 18 থেকে আপনি `<form>` ট্যাগে সরাসরি একটি **action function** দিতে পারেন।
যখন ফর্মটি সাবমিট হয়, React সেই action ফাংশনটি চালায় এবং `FormData` হিসেবে ডেটা পাঠায়।

এটি React-এর নতুন **Server Actions (Next.js 13+ / React 18+)** বা client-side submit দুইভাবেই কাজ করতে পারে।

---

### উদাহরণ – `form action` এবং `FormData` ব্যবহার

```jsx
function MyForm() {
  const handleAction = (formData) => {
    const name = formData.get("name");
    const email = formData.get("email");
    console.log("নাম:", name);
    console.log("ইমেইল:", email);
  };

  return (
    <form action={handleAction}>
      <input name="name" type="text" placeholder="নাম লিখুন" />
      <input name="email" type="email" placeholder="ইমেইল লিখুন" />
      <button type="submit">সাবমিট</button>
    </form>
  );
}
```

### 🔍 ব্যাখ্যা:

* `action={handleAction}` → ফর্ম সাবমিট হলে React এই ফাংশনে form data পাঠায়।
* `formData.get("name")` → form থেকে ইনপুটের মান পাওয়া যায়।
* এটা **uncontrolled form**, কারণ ইনপুটগুলোর মান React state দ্বারা নিয়ন্ত্রিত নয়।

---

## 🧠 ধাপ ২: Controlled Component কী?

**Controlled component** মানে, ইনপুটের মান (`value`) React-এর state দ্বারা নিয়ন্ত্রিত হয়।
এর ফলে React পুরো form data-এর উপর নিয়ন্ত্রণ রাখতে পারে।

---

### উদাহরণ – Controlled Component ব্যবহার করে

```jsx
import { useState } from "react";

function ControlledForm() {
  const [formData, setFormData] = useState({
    name: "",
    email: "",
  });

  const handleChange = (e) => {
    setFormData({
      ...formData,
      [e.target.name]: e.target.value,
    });
  };

  const handleSubmit = (e) => {
    e.preventDefault();
    console.log("নাম:", formData.name);
    console.log("ইমেইল:", formData.email);
  };

  return (
    <form onSubmit={handleSubmit}>
      <input
        name="name"
        type="text"
        value={formData.name}
        onChange={handleChange}
        placeholder="নাম লিখুন"
      />
      <input
        name="email"
        type="email"
        value={formData.email}
        onChange={handleChange}
        placeholder="ইমেইল লিখুন"
      />
      <button type="submit">সাবমিট</button>
    </form>
  );
}
```

### 🔍 ব্যাখ্যা:

* প্রতিটি ইনপুটের মান React state (`formData`) দ্বারা নিয়ন্ত্রিত।
* `onChange` ইভেন্টের মাধ্যমে state আপডেট হয়।
* `onSubmit`-এ state থেকে মান নেওয়া হয়, DOM থেকে নয়।

---

## ⚖️ তুলনা (Difference Summary)

| দিক             | `FormData` সহ `action`             | Controlled Component            |
| --------------- | ---------------------------------- | ------------------------------- |
| ডেটা হ্যান্ডলিং | ব্রাউজার FormData অবজেক্ট থেকে নেয় | React state থেকে নেয়            |
| কোডের সরলতা     | সহজ ও কম কোড লাগে                  | কিছুটা বেশি কোড লাগে            |
| নিয়ন্ত্রণ       | ব্রাউজার নিয়ন্ত্রিত                | React নিয়ন্ত্রিত                |
| ব্যবহার ক্ষেত্র | সাধারণ বা static form              | Dynamic বা validation দরকার হলে |

---

## ✅ একত্রিত উদাহরণ — Controlled + FormData

আপনি চাইলে দুই পদ্ধতিই মিশিয়ে ব্যবহার করতে পারেন:

```jsx
import { useState } from "react";

function HybridForm() {
  const [formData, setFormData] = useState({ name: "", email: "" });

  const handleAction = (data) => {
    const name = data.get("name");
    const email = data.get("email");
    alert(`নাম: ${name}\nইমেইল: ${email}`);
  };

  const handleChange = (e) => {
    setFormData({ ...formData, [e.target.name]: e.target.value });
  };

  return (
    <form action={handleAction}>
      <input
        name="name"
        value={formData.name}
        onChange={handleChange}
        placeholder="নাম লিখুন"
      />
      <input
        name="email"
        value={formData.email}
        onChange={handleChange}
        placeholder="ইমেইল লিখুন"
      />
      <button type="submit">সাবমিট</button>
    </form>
  );
}
```

# React-এ Form Data নেওয়ার দুইটি প্রধান উপায় (বাংলায় সহজ গাইড)
React (বা সাধারণভাবে JavaScript) এ **form data সংগ্রহের দুটি প্রধান উপায়** আছে —

> 1️⃣ **Uncontrolled Components (DOM থেকে ডেটা নেওয়া)**
> 2️⃣ **Controlled Components (React state দিয়ে ডেটা নিয়ন্ত্রণ করা)**

---

## 🧩 ১️⃣ Uncontrolled Components

👉 এখানে React form element-এর মান নিজে “control” করে না।
Input field-গুলোর মান সরাসরি DOM থেকে নেওয়া হয় — যেমন `e.target` বা `FormData` অবজেক্ট দিয়ে।

---

### ✅ উদাহরণ (Uncontrolled form)

```jsx
import React from "react";

function UncontrolledForm() {
  const handleSubmit = (e) => {
    e.preventDefault();
    const formData = new FormData(e.target);

    const name = formData.get("name");
    const email = formData.get("email");

    console.log("Name:", name);
    console.log("Email:", email);
  };

  return (
    <form onSubmit={handleSubmit}>
      <input type="text" name="name" placeholder="Enter your name" required />
      <input type="email" name="email" placeholder="Enter your email" required />
      <button type="submit">Submit</button>
    </form>
  );
}

export default UncontrolledForm;
```

---

### 🔍 ব্যাখ্যা

* এখানে form data React state-এ সংরক্ষিত নয়।
* Submit ইভেন্ট হলে DOM থেকে মান নেওয়া হয় (`FormData` বা `e.target.elements`)।
* এটি সহজ, কিন্তু validation বা live update করা কঠিন।

---

## 🧠 ২️⃣ Controlled Components

👉 এখানে প্রতিটি ইনপুটের মান React-এর **state** দ্বারা নিয়ন্ত্রিত হয়।
অর্থাৎ, ইনপুট ফিল্ডের `value` এবং `onChange` উভয়ই state-এর সঙ্গে যুক্ত থাকে।

---

### ✅ উদাহরণ (Controlled form)

```jsx
import React, { useState } from "react";

function ControlledForm() {
  const [formData, setFormData] = useState({
    name: "",
    email: "",
  });

  const handleChange = (e) => {
    setFormData({
      ...formData,
      [e.target.name]: e.target.value,
    });
  };

  const handleSubmit = (e) => {
    e.preventDefault();
    console.log("Name:", formData.name);
    console.log("Email:", formData.email);
  };

  return (
    <form onSubmit={handleSubmit}>
      <input
        type="text"
        name="name"
        value={formData.name}
        onChange={handleChange}
        placeholder="Enter your name"
        required
      />
      <input
        type="email"
        name="email"
        value={formData.email}
        onChange={handleChange}
        placeholder="Enter your email"
        required
      />
      <button type="submit">Submit</button>
    </form>
  );
}

export default ControlledForm;
```

---

### 🔍 ব্যাখ্যা

* ইনপুটের মান (`value`) React state থেকে আসে।
* `onChange` ইভেন্টে state আপডেট হয়।
* ফলে React সম্পূর্ণভাবে form data নিয়ন্ত্রণ করতে পারে।
* এতে রিয়েলটাইম ভ্যালিডেশন, API হ্যান্ডলিং, বা conditional UI সহজ হয়।

---

## ⚖️ তুলনা: Controlled বনাম Uncontrolled

| দিক               | Controlled Component                | Uncontrolled Component   |
| ----------------- | ----------------------------------- | ------------------------ |
| ডেটা উৎস          | React state                         | DOM (FormData, e.target) |
| কোডের সরলতা       | কিছুটা বেশি কোড                     | কম কোড                   |
| ভ্যালিডেশন        | সহজ                                 | কিছুটা জটিল              |
| পারফরম্যান্স      | বেশি control, কিন্তু বেশি re-render | কম re-render             |
| ব্যবহারের ক্ষেত্র | বড় form, validation, API call       | ছোট, সাধারণ form         |

---



