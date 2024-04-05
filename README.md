# E-0923 React Jotai Exercise

1. After creating a `dev` branch and switching, install React by running `npm create vite@latest jotai-exercise --template react`
2. Run `cd jotai-exercise` and then `npm install` to install the node packages
3. Run `npm install jotai` to install Jotai in your application
4. Create one atom store called `atom-users.tsx`
5. In your atom store, create four atoms:
  
   - firstNameAtom (string)
   - lastnameAtom (string)
   - ageAtom (number)
   - hobbiesAtom (array of strings)

6. Create a component called `Users.tsx`
7. Import and display the four atoms in your component
8. Create a form with a two input fields (one for firstname and one for lastname) and a submit button
9. Clicking on the submit button will update the *firstname* atom and *lastname* atom
10. When you are done, push your changes to `dev` branch, create a PR from `dev` to `master` and merge
