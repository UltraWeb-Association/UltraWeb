# **UltraWeb or GUI?Doc (final name pending)  A GUI?Native, JSON Backed Web Platform**  
*A project of the UltraWeb Association (California Non?Profit)*

UltraWeb (or GUI?Doc) introduces a new class of **human?consumable interactive multimedia documents** built entirely from **Graphical User Interface elements**. Using a WYSIWYG editor, users assemble documents visually, link them together to form document webs, and enrich them with JavaScript?driven behavior. Pages are constructed from **JavaFX nodes**, stored as **JSON**, and rendered as structured GUI components rather than HTML tags. This makes UltraWeb approachable for everyone from children learning to write to developers building interactive applications.

UltraWeb provides templates for articles, newsletters, outlines, lists, hubs, blogs, charts, graphs, and more. Helper dialogs and toolbars accelerate the creation process, making GUI documents a near universal medium for human expression, communication, and organization.

UltraWeb is released under the **Apache License 2.0**, enabling broad adoption while protecting the Association from liability related to user?provided JavaScript.

---

## **Why UltraWeb / GUI Doc Exists**

The Graphical User Interface is the primary way humans interact with computers. UltraWeb explores a new frontier: using the GUI itself as a **major medium for human communication, collaboration, and thought organization**. GUI documents may become a powerful personal tool for developing ideas, expressing concepts, managing information, and linking knowledge together.

This platform also opens the door to new forms of communication such as **GUI?Mail**, a richer, more expressive evolution of email built on GUI documents. And with both sandboxed and unsandboxed JavaScript support, UltraWeb hints at new models for software development, application hosting, and internet?based SaaS.

UltraWeb includes an HTTP client for uploading, downloading, designing, and managing private, guest, and public sections of a personal account on a future GUIWeb Server.

This application is a **prototype** highly experimental, exploratory, and still in its infancy. It is a foundation for future ideas, experimentation, and play. From this seed may emerge multiple lines of software development.

UltraWeb is the first embodiment of the U.S. patents titled **The GUI Document Management System** (issued in 2013 and 2017). All are encouraged to review these patents for deeper insight into the underlying concepts.

---

## **Core Principles**

- Pages are **GUI node graphs**, not HTML documents.  
- Documents are **JSON**, not markup.  
- Editing is **visual**, not code?driven.  
- Behavior is added through **sandboxed JavaScript**, not browser?embedded JS engines.  
- Everything is **read?write** users can build, modify, and share documents easily.
- Builtin content management features.

UltraWeb aims to make document creation, app building, and interactive publishing accessible to everyone.

---

## **Current Status (Alpha)**

UltraWeb is in an early, exploratory, incubation phase. The current implementation includes:

- A JavaFX based GUI Web Browser?Editor  
- A JSON backed document format  
- A drag and drop node system for building GUI documents  
- A sandboxed JavaScript execution environment  
- Autosave and file?backed page persistence  
- A local UltraWeb Server client for future server integration  
- A growing set of templates and helper dialogs 
- A content management system for projects and templates. 

The system runs inside IntelliJ IDEA and is evolving rapidly. Many features are incomplete, experimental, or subject to redesign. This repository exists to open the platform to contributors, testers, and explorers who want to help shape a new medium for human?computer interaction.

---

## **Roadmap**

The UltraWeb Association envisions the following development path:

### **Near Term Goals**
- Upload the full UltraWeb Core codebase  
- Publish architecture documentation  
- Document the JSON schema and node graph model  
- Add example GUI documents and templates  
- Improve stability, autosave behavior, and undo/redo  
- Begin alpha testing with 25 - 50 users  
- Establish issue tracking and community discussions  

### **Mid Term Goals**
- Expand template library (articles, newsletters, outlines, hubs, blogs, charts)  
- Enhance the JavaScript sandbox and event model  
- Improve GUI editing tools, dialogs, and toolbars  
- Introduce multi?process tab architecture (TabWorker)  
- Modularize the codebase for clearer separation of concerns  
- Strengthen accessibility and internationalization support  

### **Long Term Vision**
- Develop the UltraWeb Server (commercial, unsandboxed JS)  
- Support private, guest, and public GUIWeb accounts  
- Enable GUI Mail as a richer communication medium  
- Explore UltraWeb as a platform for interactive SaaS applications  
- Foster an ecosystem of GUI native documents, apps, and services  

UltraWeb is intended to grow organically through experimentation, community input, and creative exploration.

---

## **Contributing**

Contribution guidelines will evolve as the project matures. The initial requirements are:

- **JetBrains IntelliJ IDEA** is the mandatory development environment  
- **AI assisted development tools** (any vendor) are required for code generation, refactoring, and documentation  
- Code must follow project formatting and structural conventions  
- All contributions must include clear explanations and testing notes  
- Pull requests should be focused, well?documented, and easy to review  

A full `CONTRIBUTING.md` will be published soon.

---

## **Documentation**

The `docs/` directory will contain:

- **Architecture Overview** - how UltraWeb is structured internally  
- **JSON Format Specification** - the document schema and node graph model  
- **Sandbox Documentation** - how JavaScript is executed safely  
- **Security Model** - sandboxing, permissions, and future server considerations  
- **Roadmap** - development plans and milestones  

These documents will expand as the project evolves.

---

## **About the UltraWeb Association**

UltraWeb is developed and maintained by the **UltraWeb Association**, a California non profit dedicated to creating accessible, empowering software tools. The Association may offer commercial services, accept donations, and hire development staff to support ongoing work. The open?source UltraWeb Core is the foundation for a broader ecosystem of GUI native documents and applications.

