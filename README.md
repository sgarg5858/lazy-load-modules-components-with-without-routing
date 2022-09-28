# lazy-load-modules-components-with-without-routing

We have login page and Home page Initially we need Login Page only! We dont need home page initially!
Home Page shows 2 more thing skills and experiences! They are from separate modules, they dont need to be shown immediately, we can 
ask user to you know load skills,experiences while user sees other things on home page or we can load asynchronously!

1-eager-loading

Everything is put inside Main Bundle as We are importing Both AuthModule and Home Module in AppModule and Home Module imports SkillsModule and
Experience Module. This makes the intial bunde big. The point is we dont need home page on load, we only need it after user is logged in!
