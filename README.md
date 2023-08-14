# React Interview Question / Answer

<h3>1. What is React and Feature of React?</h3>

<details>

<summary>Answer:</summary>

<p>React is a JavaScript library that helps you build user interfaces for your websites or web applications. Think of it as a set of tools that make it easier for you to create interactive and dynamic elements on your web pages. </p>

**features of React:**

1. **Component-Based**: React divides your web page into smaller building blocks called components. These components are like puzzle pieces that you can put together to create a complete picture. Each component can have its own logic and behavior, making it easier to manage and reuse code.

2. **Virtual DOM**: React uses something called a Virtual DOM (Document Object Model) to keep track of changes in your components. When something in your component changes, React doesn't immediately update the actual webpage. Instead, it updates the Virtual DOM first, and then figures out the most efficient way to update the real DOM. This makes your web app faster and more efficient.

3. **Declarative Syntax**: In React, you describe what you want your user interface to look like in a simple and declarative way. You tell React how you want things to be, and it takes care of updating the actual interface for you. This is different from the traditional way of web development where you might have had to worry about each small change.

4. **Reusability**: Since React encourages you to break your interface into components, you can reuse these components across different parts of your website. This saves you time and helps maintain consistency in your design and functionality.

5. **One-Way Data Flow**: React follows a one-way data flow, which means that the data flows in a single direction: from parent components to child components. This makes it easier to understand how data changes and where those changes are coming from.

6. **JSX**: JSX is a syntax extension for JavaScript that React uses. It allows you to write HTML-like code within your JavaScript, making it easier to visualize how your components will look in the browser.

Overall, React simplifies the process of building dynamic and interactive web interfaces by breaking down your webpage into smaller reusable parts and efficiently managing updates to the user interface. 
</details>

<h3>2. What is Virtual DOM?</h3>

<details>
   <summary>Answer:</summary>

Imagine you have a real-world painting and a copy of that painting. You want to make changes to the copy without affecting the original. The Virtual DOM in React is like that copy of the painting.

In web development, the browser's "DOM" (Document Object Model) represents the structure of a webpage. When you use React, instead of directly changing the real DOM, React creates a Virtual DOM, which is a lightweight copy of the actual DOM.

When you make changes to your React components, these changes are first applied to the Virtual DOM. React then compares the Virtual DOM with the real DOM to figure out what parts of the actual DOM need to be updated. This comparison process is much faster than directly updating the real DOM every time you make a change.

So, think of the Virtual DOM as a smart assistant that helps React update the webpage efficiently. It's like making changes on a sketch before updating the actual painting, making the whole process smoother and faster.

</details>

<h3>3. What is SPA?</h3>

<details>
    <summary>Answer:</summary>
    
An SPA, which stands for "Single Page Application," is a type of website that loads and displays all its content on a single web page. Traditional websites often load new pages when you click on links, which can make them a bit slower as the whole page needs to reload.

But with SPAs, things work differently. When you interact with a button or a link in an SPA, only the necessary parts of the page get updated or replaced, without needing to reload the entire page. This makes SPAs feel faster and more responsive, similar to using a desktop application.

</details>

<h3>4. What is the difference between class and functional components?</h3>

<details>
  <summary>Answer:</summary>
    <table width="100%">
      <tr>
         <th>Aspect</th>
         <th>Class Components</th>
         <th>Functional Components</th>
      </tr>
      <tr>
         <td>Definition</td>
         <td>Defined using ES6 classes.</td>
         <td>Defined as JavaScript functions.</td>     
      </tr>
     <tr>
        <td>State Management</td>
        <td>Can have local state using <code>this.state.</code></td>
        <td>Use the <code>useState</code> hook for state.</td>     
     </tr>
     <tr>
        <td>Lifecycle Methods</td>
        <td>Use lifecycle methods like <code>componentDidMount</code>, etc.</td>
        <td>Use the <code>useEffect</code> hook.</td>     
     </tr>
     <tr>
        <td>Syntax</td>
        <td>More verbose and requires binding of event handlers.</td>
        <td>Simpler syntax and no binding needed.</td>     
     </tr>
     <tr>
        <td>Performance</td>
        <td>Slightly heavier due to JavaScript classes.</td>
        <td>Lighter weight, potentially better performance.</td>     
     </tr>
     <tr>
        <td>Reusability</td>
        <td>More complex to reuse logic.</td>
        <td>Easier to reuse through custom hooks.</td>     
     </tr>
     <tr>
        <td>Context and Refs</td>
        <td>Easier access to <code>this.context</code> and refs.</td>
        <td>No <code>this.context</code> and refs, but can use <code>useRef</code>.</td>     
     </tr>
     <tr>
        <td>Learning Curve</td>
        <td>Can be steeper, especially for beginners.</td>
        <td>Generally easier for beginners to grasp.</td>     
     </tr>
     <tr>
        <td>Modern React Practices</td>
        <td>Not fully aligned with modern React practices.</td>
        <td>More aligned with modern practices.</td>     
     </tr>
   </table>

</details>

<h3> 5. Difference b/w Stateful and stateless Component?</h3>

<details>
    <summary>Answer:</summary>

<table width="100%">
      <tr>
         <th>Aspect</th>
         <th>Stateful Components</th>
         <th>Stateless Components</th>
      </tr>
      <tr>
         <td>State Management</td>
         <td>Manage their own state using <code>this.state</code>.</td>
         <td>Receive data and display it, no internal state.</td>     
      </tr>
     <tr>
        <td>Purpose</td>
        <td>Used for dynamic behavior and interaction.</td>
        <td>Used for displaying UI without complex logic.</td>     
     </tr>
     <tr>
        <td>Functional Type</td>
        <td>Class components.</td>
        <td>Function components (using <code>function</code> keyword).</td>     
     </tr>
     <tr>
        <td>Lifecycle Methods</td>
        <td>Have access to lifecycle methods like <code>componentDidMount</code>, <code>componentDidUpdate</code>, etc.</td>
        <td>No lifecycle methods until React 16.8.</td>     
     </tr>
     <tr>
        <td>Reusability</td>
        <td>Slightly less reusable due to internal state.</td>
        <td>Highly reusable as they don't hold internal state.</td>     
     </tr>
     <tr>
        <td>Performance</td>
        <td>Can have some impact on performance due to state updates.</td>
        <td>Generally better for performance as they don't manage state.</td>     
     </tr>
        
   </table>

</details>

<h3></h3>

<details>
    <summary></summary>

</details>

<h3></h3>
<details>
    <summary></summary>

</details>


