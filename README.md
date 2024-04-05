# E-0923 React Jotai Exercise

1. After creating a `dev` branch and switching, install React by running `npm create vite@latest jotai-exercise --template react`
2. Run `cd jotai-exercise` and then `npm install` to install the node packages
3. Run `npm install jotai` to install Jotai in your application
4. Create one atom store called `atom-users.tsx`
5. In your atom store, create four atoms:
  
   - firstNameAtom (string): Your first name
   - lastnameAtom (string): Your last name
   - ageAtom (number): Your age
   - hobbiesAtom (array of strings): Your hobbies

6. Create a component called `Users.tsx`
7. Import and display the four atoms in your component. You can output them in separate span or div tags. Use `.map` for the hobbies since it's an array
8. Create a form with a two input fields (one for firstname and one for lastname) and a submit button
9. Clicking on the submit button will update the *firstname* atom and *lastname* atom
10. When you are done, push your changes to `dev` branch, create a PR from `dev` to `master` and merge
