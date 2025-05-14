Effective User Experience (UX) design is not purely a matter of opinion or taste; it can and should be evaluated using objective criteria and established principles. This note covers key methods and frameworks for evaluating UX, with a strong focus on heuristic evaluation.

**Tags:** #Week1 #UX #Evaluation #Heuristics #Usability #Nielsen #Krug #Cooper #Affordances

## The Importance of Evaluation in UX

* **Objectivity:** Evaluation provides a structured way to assess design quality beyond subjective preferences.
* **Identify Problems:** Helps pinpoint usability issues and areas for improvement early in the design process.
* **Refine Skills:** Understanding evaluation criteria enhances a designer's own skills and knowledge.
* **Standardization:** Allows for consistent assessment across different projects or versions of a product.
* **Communication:** Provides a common language and framework for discussing design decisions with stakeholders.

## Heuristic Evaluation

A cornerstone of UX evaluation, heuristic evaluation is a usability inspection method where evaluators assess an interface against a set of recognized usability principles known as "heuristics."

* **Definition:** A systematic inspection of a user interface design for usability. The goal is to find usability problems in the design so that they can be attended to as part of an iterative design process.
* **Process:** Typically involves a small set of evaluators (3-5) examining the interface independently and then aggregating their findings.
* **Characteristics:**
    * Uses "rules of thumb" or established best practices.
    * Provides criteria to measure a design against.
    * Helps identify potential usability issues quickly and cost-effectively.

### 1. Jakob Nielsen's 10 Usability Heuristics

These are perhaps the most widely known and used set of usability heuristics for user interface design:

1.  **Visibility of System Status:**
    * **Principle:** The system should always keep users informed about what is going on, through appropriate feedback within a reasonable time.
    * **Examples:** Progress bars during downloads, loading spinners, "message sent" confirmations, clear indication of the current page in navigation.

2.  **Match Between System and the Real World:**
    * **Principle:** The system should speak the users' language, with words, phrases, and concepts familiar to the user, rather than system-oriented terms. Follow real-world conventions, making information appear in a natural and logical order.
    * **Examples:** Using a trash can icon for deleting files, a shopping cart icon for e-commerce, language that is clear and avoids jargon.

3.  **User Control and Freedom:**
    * **Principle:** Users often choose system functions by mistake and will need a clearly marked "emergency exit" to leave the unwanted state without having to go through an extended dialogue. Support undo and redo.
    * **Examples:** "Undo" and "Redo" buttons, "Cancel" buttons in processes, clear back navigation.

4.  **Consistency and Standards:**
    * **Principle:** Users should not have to wonder whether different words, situations, or actions mean the same thing.
    * **Internal Consistency:** Consistent use of terminology, layout, and behavior within the product itself.
    * **External Consistency:** Adherence to platform (e.g., iOS, Android, Web) and industry conventions. For instance, the placement of a logo or main navigation.

5.  **Error Prevention:**
    * **Principle:** Even better than good error messages is a careful design which prevents a problem from occurring in the first place. Either eliminate error-prone conditions or check for them and present users with a confirmation option before they commit to the action.
    * **Examples:** Disabling a "submit" button until all required form fields are completed, providing suggestions for search queries to prevent typos, asking for confirmation before a destructive action like "delete all."

6.  **Recognition Rather Than Recall:**
    * **Principle:** Minimize the user's memory load by making objects, actions, and options visible. The user should not have to remember information from one part of the dialogue to another. Instructions for use of the system should be visible or easily retrievable whenever appropriate.
    * **Examples:** Menus showing available options (recognition) are easier than command-line interfaces requiring users to remember commands (recall). Recently viewed items lists.

7.  **Flexibility and Efficiency of Use:**
    * **Principle:** Accelerators—unseen by the novice user—may often speed up the interaction for the expert user such that the system can cater to both inexperienced and experienced users. Allow users to customize frequent actions.
    * **Examples:** Keyboard shortcuts for power users (e.g., Ctrl+S to save), advanced search options, customizable dashboards.

8.  **Aesthetic and Minimalist Design:**
    * **Principle:** Dialogues should not contain information that is irrelevant or rarely needed. Every extra unit of information in a dialogue competes with the relevant units of information and diminishes their relative visibility.
    * **Examples:** Clean, uncluttered interfaces that prioritize essential content and functionality. Good use of white space.

9.  **Help Users Recognize, Diagnose, and Recover from Errors:**
    * **Principle:** Error messages should be expressed in plain language (no error codes), precisely indicate the problem, and constructively suggest a solution.
    * **Examples:** "Incorrect password" is better than "Error #123." Providing a link to "Forgot password?" when a login fails.

10. **Help and Documentation:**
    * **Principle:** Even though it is better if the system can be used without documentation, it may be necessary to provide help and documentation. Any such information should be easy to search, focused on the user's task, list concrete steps to be carried out, and not be too large.
    * **Examples:** FAQs, tooltips, contextual help links, searchable knowledge bases.

### 2. Donald Norman's 7 Stages of Action

While Nielsen's heuristics focus on interface attributes, Norman's model describes the psychological stages a user goes through when interacting with a system. Understanding these stages can help identify where a design might fail to support the user's cognitive process.
*(This is more for conceptual understanding of user interaction rather than a direct evaluative checklist like Nielsen's heuristics in the context of this course's initial focus).*

1.  **Goal:** What do I want to accomplish?
2.  **Plan (Intention):** What are the alternative action sequences?
3.  **Specify:** What action can I do now?
4.  **Perform (Execute):** How do I do it?
5.  **Perceive:** What happened? (Feedback from the system)
6.  **Interpret:** What does it mean?
7.  **Compare (Evaluate):** Is this okay? Have I accomplished my goal?

### 3. Steve Krug's Usability Principles (from "Don't Make Me Think")

Krug's principles emphasize simplicity, clarity, and intuitiveness, making them highly practical for web and application design.

1.  **First Law of Usability - Don't make people think:** A design should be self-evident and obvious. Users shouldn't have to puzzle things out.
2.  **Design for scanning, not reading:** Users typically scan web pages for relevant information rather than reading every word. Use clear headings, short paragraphs, bullet points, and visual cues.
3.  **Make clicks mindless:** Navigation and interactive elements should be unambiguous. Users should be confident about what will happen when they click. (A common rule of thumb mentioned in lectures: aim for goal achievement in approximately 3 clicks).
4.  **Less is more (Omit needless words/elements):** Strive for simplicity. Remove anything that isn't essential, as it adds noise and cognitive load.
5.  **Help users to easily navigate:** Provide clear, consistent, and predictable navigation systems. Users should always know where they are and how to get where they want to go.
6.  **Don't argue but test:** Instead of debating design choices internally, conduct user testing to see what actually works for users.
7.  **Usability testing - do it regularly:** Testing with a few users early and often is more valuable than extensive testing late in the process.
8.  **Increase your Reservoir of Goodwill:** Positive user experiences build "goodwill." Users are more forgiving of minor issues if they generally like and trust a product.

### 4. Key Heuristics for INFS3700 (Combined Approach)

This course emphasizes a practical, combined set of five key heuristics drawn from the work of Alan Cooper, Jakob Nielsen, and Steve Krug:

1.  **Software should be forthcoming (Alan Cooper):**
    * **Principle:** The software should proactively offer information or assistance that is relevant to the user's current context or task, without explicit prompting. It anticipates needs.
    * **Example:** Google Maps automatically informing about road congestion ahead and suggesting an alternative route.

2.  **Software should be self-confident (Alan Cooper):**
    * **Principle:** The software should behave as if it knows what it's doing. It avoids unnecessary confirmations for routine actions, which can be annoying and imply the system is unsure. Instead, provide easy ways to undo actions if needed.
    * **Example:** Gmail's "Undo Send" feature allows users to retract an email shortly after sending, rather than asking "Are you absolutely sure you want to send this?" for every email.

3.  **Visibility of system status (Nielsen):** (As described in Nielsen's list)
    * Keep users informed about ongoing processes and current states.

4.  **Match between system & real world (Nielsen):** (As described in Nielsen's list)
    * Use familiar language, concepts, and conventions.

5.  **Don't waste my time! (Steve Krug):**
    * **Principle:** Respect the user's time. Help them make decisions quickly and complete their tasks with ease. Avoid overwhelming them with too many options, unclear paths, or misleading information.
    * **Example:** Clear pricing pages that allow for easy comparison, streamlined checkout processes.

## Natural Mapping & Affordances

These concepts are crucial for designing intuitive interactions.

* **Natural Mapping:**
    * **Definition:** Refers to the relationship between controls and their effects in the world. The best mapping is one where it is clear what a control does without needing labels or instructions.
    * **Examples:**
        * Stove burner controls arranged in the same spatial layout as the burners themselves.
        * Pushing a light switch up to turn a light on (in some cultures where this is the convention).
* **Affordances (and Perceived Affordances):**
    * **Definition (Gibson):** The properties of an object that determine the actions that can be taken on it. For example, a chair *affords* sitting.
    * **Perceived Affordances (Norman):** What a user *perceives* an object can do, based on its appearance and other sensory information. Good design makes affordances clear.
    * **Examples:** A button looks "pressable," a handle looks "graspable," a text field looks "type-in-able."
    * **Context Dependency:** Perceived affordances can change with context. A chair normally affords sitting, but in a burning room, it might be perceived as affording smashing a window to escape.

---
**Parent Topic:** [[Week 01 - UX Introduction]]
**Related Concepts:** [[W1 - UX, SD, and CX Concepts]], [[W1 - User Goals, Behaviour, and Context]], [[W1 - The Design Process]]
**Overall Course Context:** [[INFS3700 UX & IT Service Design - Main Summary]]