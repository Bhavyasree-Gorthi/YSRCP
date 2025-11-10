# TODO: Update Header Navigation to "Services" Linking to Student Assistance

## Tasks
- [x] Add id="student-assistance" to the Student Assistance initiative div in Initiatives.tsx
- [x] Update Header.tsx desktop menu: change "Mission" to "Services" and update onClick to scrollToSection('student-assistance')
- [x] Update Header.tsx mobile menu: change "Mission" to "Services" and update onClick to scrollToSection('student-assistance')
- [ ] Test the scrolling functionality to ensure it works correctly

## New Tasks: Update Jagan-Mark Dropdown and Menus
- [x] Add more schemes to WelfarePage.tsx (add 2-3 more to existing Amma Vodi, Vidya Deevena, Vasathi Deevena, NRI Connect)
- [x] Update Header.tsx: Change Welfare to a submenu with schemes
- [x] Change "Contact" to "Suggestions" in desktop and mobile menus, link to suggestions section
- [x] Add more content to pages (Health, Education, Agriculture, Women, StudentYouth) to make them scrollable

## Additional Tasks: Connect Schemes, Add Suggestions, Mobile Responsiveness
- [x] Create individual pages for each welfare scheme (AmmaVodi, VidyaDeevena, etc.)
- [x] Add routes in App.tsx for /welfare/:scheme
- [x] Create Suggestions.tsx component and add route for /suggestions
- [ ] Add scrollable images to all pages for better mobile experience
- [ ] Ensure full mobile responsiveness: fix Jagan Mark dropdown on mobile, make all content responsive
- [ ] Test mobile functionality and scrolling
