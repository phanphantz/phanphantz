# 👋 About Me
Hello! I'm Phun Peeticharoenthum ( Pun ), a passionate Unity Developer and Programmer based in Bangkok, Thailand. Welcome to my GitHub portfolio page, where I showcase a selection of open-source and public projects I've worked on. If you're interested in learning more about my experience, feel free to reach out directly for my resume, portfolio, or showreel highlighting my past work.

**Contact:** phun.peeticharoenthum@gmail.com

 ## ✨Open-Source Projects
This section features all of my open-source projects, primarily Unity-based tools that I’ve developed and actively use in both personal and freelance projects.

### 🔥GameDevSecretSauce
These are the tools and game development materials I share on [น้ำจิ้มสูตรลับของนักพัฒนาเกม](https://www.facebook.com/GameDevSecretSauce/). It's a Facebook page dedicated to providing valuable knowledge and techniques for Thai game developers.
- [**Thai Font Doctor**](https://github.com/phanphantz/GameDevSecretSauce/tree/main/ThaiFontDoctor) - An Editor Tool for solving Thai font's vowel and tone mark issues in just minutes! It automates glyph pair adjustments within TextMeshPro's Font Asset, transforming a tedious process into a quick and effortless task.
- [**Google Sheet Downloader**](https://github.com/phanphantz/GameDevSecretSauce/tree/main/GoogleSheetDownloader) - A Helper script for downloading a private Google sheet as a serializable data list using Google Sheet API v.4

### 🔧PhEngine Packages
A collection of Unity Editor Tool packages I’ve developed to address various aspects of game development.
- [**PhEngine - Core**](https://github.com/phanphantz/PhEngine-Core) - A Core package that provides essential components for other packages and includes commonly used utility classes.
  - Include useful stuff like Singletions, Service Locator, JSON Tools, and Logger
  - Features **Operations**, a custom coroutine wrapper inspired by DOTween and UniTask. It allows users to bind callbacks to coroutine-like operations and manage them easily with control functions like Pause, Resume, Cancel, and more. All operations can also be chained together as a series or parallel calls.
 
- [**PhEngine - Network**](https://github.com/phanphantz/PhEngine-Network) - My version of RESTful API connector for developing online games
  - All APIs are treated as ScriptableObjects, making it easy to customize each endpoint's behavior, such as configuring error handling methods.
  - Supports API calls as Coroutines or UniTasks (using the async-await pattern).
  - Includes features like callback bindings, error handling, environment switching, and data center patterns.
  - Test any API directly from the ScriptableObject by specifying the JSON body and clicking the test button.
  - Easily disable any API and mock API responses as either failed or successful with mock data.
  - Provides insightful logging with four modes: Pretty, Verbose, Minimal, and None.
  
- [**PhEngine - Thai Text**](https://github.com/phanphantz/PhEngine-ThaiText) - A package contains useful tools for handling Thai text in Unity
  - ThaiTextMeshPro components for displaying Thai font correctly using [ThaiFontAdjustor](https://github.com/SaladLab/Unity3D.ThaiFontAdjuster)
  - A Unity supported version of [ThaiStringTokenizer](https://github.com/chaiwatmat/ThaiStringTokenizer) library for dictionary-based word wrapping.
  
- [**PhEngine - UI**](https://github.com/phanphantz/PhEngine-UI) - My UI engine for managing UI Panels, UI Layers, and Transitions.
- [**PhEngine - Motion**](https://github.com/phanphantz/PhEngine-Motion) - A Scriptable Animation Config solution that allows you to reuse Animations and Tweens in the form of ScriptableObjects. Similar concept to **DOTweenPro.**
- [**PhEngine - Sound**](https://github.com/phanphantz/PhEngine-Sound) - A sound engine. Modified from [EazySoundManager](https://github.com/JackM36/Eazy-Sound-Manager)
- [**PhEngine - Scene**](https://github.com/phanphantz/PhEngine-Scene) - A scene management package based on **SceneReference.**

### 📦Miscellaneous
- [**Content Size Fitter With Limit**](https://github.com/phanphantz/Unity3D.ContentSizeFitterWithLimit)
- [**National Election 2023 Top-Down Voting Unit Structures**](https://github.com/phanphantz/th-vote-66-top-down-structures)

 ## 🥋Clean Code Lecture Materials
This section features my lecture materials for teaching game development to university students as a speaker and technical assistant at Media Technology, KMUTT. The focus is primarily on demonstrating clean coding practices, design patterns, and various popular topics commonly used in the industry. You can view the tags in the repository to explore the various lecture topics or clone the project to examine the commit history and see the progression of changes.

- [**GDM 330**](https://github.com/phanphantz/GDM330) - This project is designed to teach junior (3rd-year) game development students over a 6-week period **from August to September 2023**
  - **Week 1** - Source Control using Git
  - **Week 2** - MVP patterns for UI development
  - **Week 3** - Utilizing Singletons
  - **Week 4**
    - Do Not Repeat Yourself (DRY)
    - Single Responsibility Principle (SRP)
    - Open-Closed Principle (OCP)
  - **Week 5**
    - Observer Pattern
    - DOTween
  - **Week 6**
    - Scriptable Objects
    - Saving & Loading from JSON
    - Web Requests
   
- [**MDT Bitcoin Runner**](https://github.com/phanphantz/MDTBitcoinRunner123) - The project I picked from a [bitcoin-runner-unity](https://github.com/berkanuslu/bitcoin-runner-unity) GitHub repository and use to teach junior (3rd-year) game development students over 5-weeks period **from August to October 2022**
  - **Week 3** - Extract Method & Do Not Repeat Yourself (DRY)
  - **Week 5** - Clean Codes
    -  Either Call or Pass
    -  Prefer **If** not **If Else**
    -  Push Codes into Classes
    -  Prefer No Prefixes
    -  Meaningful Names
  - **Week 7** 
    - Single Responsibility Principle (SRP)
    - Open-Closed Principle (OCP)
  - **Week 9**
    - Observer Pattern
    - DOTween
    - Clean Architecture
  - **Week 10**
      - LINQ
      - Generic
      - TimeSpan
