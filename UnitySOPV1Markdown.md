
## 1. Purpose Statement

The purpose of this procedure is to provide employees with standardized access to Unity, Visual Studio and GitHub Desktop. By establishing a link to the project repository, this process integrates a basic workflow for developers to ensure consistent environment setups across the organization.

## 2. Scope

-   **Who:** This procedure applies to most development teams within the organization.
    
-   **What:** It covers the installation of basic development tools, and the establishing a link to the repository.
    
-   **When:** This is to be performed during initial onboarding or when a new development machine is being provisioned for the project.
    

## 3. Roles and Responsibilities

-   **Developers:** Responsible for following these steps to install software, clone repositories, and verify their local environment through a test commit.
    
-   **Project Teams/Colleagues:** Responsible for providing guidance on specific package versions and third-party extension compatibility.
    

## 4. Inputs and Outputs
 **Inputs:** Company credentials (username and password).
-   Access to the project repository
    
-   Access to Unity account
    
**Outputs:** A fully configured local development environment.
-   A verified local fork and branch for staging changes.
    

## 5. Step-by-Step Procedure

### Phase I: Software Installation

 1. Navigate to Unity.com and go to the downloads page.
 2. Download and run Unity Hub.
 3. Launch Unity Hub and sign in using your company username and password.
 4. Navigate to the "Installs" section and select the 6000.0.61f1 LTS.
 5. While customizing the install, opt to install Visual StudioCommunity

### Phase II: Repository Setup

 1. Log in to GitHub.com using your company credentials.
 2. Locate the shared project repository and click the "Code" button.
 3. Download and install GitHub Desktop by following the directions after hitting “Open with GitHub Desktop”
 4. Sign in to GitHub Desktop using your Github credentials.
 5. Clone the project repository to your designated local project folder.

### Phase III: Project Configuration

 1. Return to Unity and select "Add a project repository" and navigate to the folder where you cloned the files.
 2. Open the project with the 6000.0.61f1 LTS version you just installed.

### Phase IV: Verification (The Test Commit)

 1. Create a fork of the main branch on Github.
 2. In Github Desktop, point the application to your new fork and clone it.
 3. Reopen the project and make a minor, visible change (e.g., editing a text file).
 4. Save the project and return to Github Desktop to stage and commit the changes.
 5. Push the changes to your branch to confirm the workflow is functional.

## 6. Exceptions or Known Rework

**Package/Dependency Errors:** Upon first launch, you may see errors regarding outdated or uninstalled packages.
-   **Rework:** Cross-reference these dependencies with project documentation and colleagues to ensure you install the correct, compatible versions of third-party extensions.
    

**Specialized Tools:** This procedure does not include the installation of specialized tools; these are delegated to specific teams and must be handled separately.

**Credential Errors:** Credentials do not allow access to required materials, such as Unity Hub
-   **Rework:** Retry credentials, ensuring accuracy. If a second attempt fails, reset credentials through your administrator and re-attempt access
    

## 7. Capture Checklist

**Recorded**
Screenshots of Unity Hub Menu, Sign-in, Github using Snipping Tool application

**Never Recorded**
Personal info that could be used harmfully (log-ins, computer identifiers)
    

**Redacted**
Names of the technologies used as well as login identifiers were redacted from the transcript and replaced with placeholders prior to upload, screenshots were never given to Gemini and were redacted to obscure personal project information
    

## 8. Change Log

**Removed AI Preamble and post-generation question(s)**
-   Howard Hall, 2/3/2026
    
-   Unnecessary for SOP readability

**Removed the codenames for software used by the SOP**

-   Howard Hall, 2/3/2026
    
-   Obscure SOP purpose and technologies used as much as possible from being recorded by LLM 

**Removed lines hallucinating installation options and manually clarified**

-   Howard Hall, 2/3/2026
    
-   Inaccurate representation of step, implied options existed that are not present during the installation process 

**Added known rework for login issues**
-   Howard Hall, 2/13/2026
    
-   Added steps to reset login if it fails to access required materials
    

## 8. QA Checklist

**All steps are active voice and use precise action verbs**
Each instruction is delivered in present tense
    
**No ambiguous pronouns or role references**
Ambiguity is used only for establishing scope, since this SOP is for a baseline development setup and not for specialized teams
    
**All inputs, outputs, and systems are named explicitly**
 Completed with system names bolded

**Decision points have clear criteria and branches**
NA
    
**No missing preconditions (prerequisites before starting)**
I don’t believe employee credentials need to be a prerequisite if reading this document implies either that you have them, or stole the document. Otherwise, no prerequisites are required prior to following these steps
    
**Exception paths are documented**
As package needs are a case-by-case basis for Unity and project needs, the exception advising to reference colleagues and documentation is complete
    

**Cycle time or SLA is mentioned if relevant**
NA, dependent on system specs, multitasking, etc.
    

## 9. Glossary

-   **Unity** - Game development engine with free and paid tiers of access capable of creating 2D and 3D games, and compatible with third-party plug-ins
    
-   **Unity Hub** - GUI for managing Unity Installs, repository management, and add-on installation
    
-   **Microsoft Visual Studio** - Programming IDE created by Microsoft that Unity supports direct integration with.
    
-   **GitHub** - Repository management web service for data analytics, software development, and more
    
-   **GitHub Desktop** - GUI interface for GitHub that allows for more fluid management of local and web repositories on GitHub
    

## 10. Prompt Log

Model: Google Gemini 3

Prompt:

> I need you to use this transcript to create a standard operating
> procedure that includes the following elements:
> 
> - Purpose statement
> 
> - Scope (who, what, when)
> 
> - Roles and responsibilities
> 
> - Inputs and outputs
> 
> - Step-by-step procedure (numbered steps)
> 
> - Exceptions or known rework scenarios

  

Response:

> This Standard Operating Procedure (SOP) outlines the requirements for
> configuring a development environment for [SYSTEM_NAME].
> 
> ----------
> 
> ## 1. Purpose Statement
> 
> The purpose of this procedure is to provide employees with
> standardized access to [SYSTEM_NAME] and [DEVELOPMENT_ENVIRONMENT]. By
> establishing a link to the project repository, this process integrates
> a basic workflow for developers to ensure consistent environment
> setups across the organization.
> 
> ## 2. Scope
> 
> -   Who: This procedure applies to most development teams within the organization.
>     
> -   What: It covers the installation of the [SYSTEM_MANAGER], [DEVELOPMENT_ENVIRONMENT], and the setup of the
> [REPOSITORY_INTERFACE].
>     
> -   When: This is to be performed during initial onboarding or when a new development machine is being provisioned for the project.
>     
> 
> ## 3. Roles and Responsibilities
> 
> -   Developers: Responsible for following these steps to install software, clone repositories, and verify their local environment
> through a test commit.
>     
> -   Project Teams/Colleagues: Responsible for providing guidance on specific package versions and third-party extension compatibility.
>     
> 
> ## 4. Inputs and Outputs
> 
> -   Inputs: * Company credentials ([USERNAME] and password).
>     
> 
> -   Access to the project repository on [REPOSITORY_NAME].com.
>     
> 
> -   Outputs: * A fully configured local development environment.
>     
> 
> -   A verified local fork and branch for staging changes.
>     
> 
> ## 5. Step-by-Step Procedure
> 
> ### Phase I: Software Installation
> 
> 1.  Navigate to [SYSTEM_NAME].com and go to the downloads page.
>     
> 2.  Download and run the installer for [SYSTEM_NAME] [SYSTEM_MANAGER].
>     
> 3.  Launch the manager and sign in using your company [USERNAME] and password.
>     
> 4.  Navigate to the "Installs" section and select the [SOFTWARE_VERSION] release.
>     
> 5.  Select "Customize Install" and ensure [DEVELOPMENT_ENVIRONMENT] is selected to ensure version compatibility.
>     
> 
> ### Phase II: Repository Setup
> 
> 6.  Log in to [REPOSITORY_NAME].com using your company credentials.
>     
> 7.  Locate the shared project repository and click the "Code" button.
>     
> 8.  Download and install [REPOSITORY_INTERFACE] using default options.
>     
> 9.  Sign in to the interface using your [REPOSITORY_NAME] credentials.
>     
> 10.  Clone the project repository to your designated local project folder.
>     
> 
> ### Phase III: Project Configuration
> 
> 11.  Return to [SYSTEM_NAME] [SYSTEM_MANAGER] and select the [SOFTWARE_VERSION] version.
>     
> 12.  Select "Add a project repository" and navigate to the folder where you cloned the files.
>     
> 13.  Open the project.
>     
> 
> ### Phase IV: Verification (The Test Commit)
> 
> 14.  Create a fork of the main branch on [REPOSITORY_NAME].
>     
> 15.  In [REPOSITORY_INTERFACE], point the application to your new fork and clone it.
>     
> 16.  Reopen the project and make a minor, visible change (e.g., editing a text file).
>     
> 17.  Save the project and return to [REPOSITORY_INTERFACE] to stage and commit the changes.
>     
> 18.  Push the changes to your branch to confirm the workflow is functional.
>     
> 
> ## 6. Exceptions or Known Rework
> 
> -   Package/Dependency Errors: Upon first launch, you may see errors regarding outdated or uninstalled packages.
>     
> 
> -   Rework: Cross-reference these dependencies with project documentation and colleagues to ensure you install the correct,
> compatible versions of third-party extensions.
>     
> 
> -   Specialized Tools: This procedure does not include the installation of specialized tools; these are delegated to specific
> teams and must be handled separately.
>     
> 
> ----------
> 
> Would you like me to create a checklist based on these steps to help
> new hires track their progress?

