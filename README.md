# Intro to Formik

HTML forms can be complex. Rails made them easier by introducing helping methods, such as `form_tag`, `form_for` and `form_with`.

[Building forms with React](https://reactjs.org/docs/forms.html) is even more complex. There is a lot to keep track of. It is not enough to just render a form in the DOM. React has to store and update state, validate inputs, and handle form submissions.

So far, we have only dealt with React forms using [class inheritance (Class components), vs. object composition (Functional components)](https://medium.com/javascript-scene/master-the-javascript-interview-what-s-the-difference-between-class-prototypal-inheritance-e4cd0a7562e9). Now that React Hooks have allowed us to build our React in a slicker, simpler syntax, is there a better way to create React forms?

Yes.

[`Formik`](https://jaredpalmer.com/formik) is a popular React form library that works great with functional components. Its documentation states that it is designed to help with 3 core form complications:

1. Getting values in and out of form state
1. Validation and error messages
1. Handling form submission.

Nitro uses `Formik` for all its new React forms. So let's learn about it :).

## Resources

- [Formik docs](https://jaredpalmer.com/formik/docs/overview)
- [Functional vs Class-Components in React](https://medium.com/@Zwenza/functional-vs-class-components-in-react-231e3fbd7108)
