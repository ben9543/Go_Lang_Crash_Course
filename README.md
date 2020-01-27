## GO LANG CRASH COURSE

> YOUTUBE LINK : https://www.youtube.com/watch?v=YS4e4q9oBaU&t=1312s

⭐️ Course Contents ⭐️

* 😎 (0:00:00) Introduction 
* 😎 (0:16:57) Setting Up a Development Environment 
* 😎 (0:35:48) Variables
  #### 1. Variable Declaration
    > - var foo int
    > - var foo int = 42
    > - foo := 42
  #### 2. Can't redeclare variables, but can shadow them
  #### 3. All variables must be used
  #### 4. Visibility
    >  - **Lower case first letter for package scope**
        - Means that lowercased variables are scoped to the package
        - All of the source files that are into same packages have access to the variables
    > - **Upper case first letter to export**
        - Means eligible to use the variables globally in any packages
    > - **No private scope**
        - But we can declare variables inside of a block, and it will be scoped
  #### 5. Naming conventions
    > - **PascalConvention or camelCase**
        - Capitalize acronyms(HTTP, URL)
    > - **As short as reasonable**
        - Longer names for longer lives

  #### 6. Type conversions
    > - **DestinationType(variable)**
        - For example: Use **strconv** package for converting types to strings
* 😪 (0:57:05) Primitives 
* 😪 (1:26:29) Constants 
* 😪 (1:47:53) Arrays and Slices 
* 😪 (2:17:20) Maps and Structs
* 😪 (2:48:00) If and Switch Statements 
* 😪 (3:21:17) Looping 
* 😪 (3:41:34) Defer, Panic, and Recover 
* 😪 (4:03:57) Pointers 
* 😪 (4:21:30) Functions 
* 😪 (4:57:59) Interfaces 
* 😪 (5:33:57) Goroutines 
* 😪 (6:05:10) Channels