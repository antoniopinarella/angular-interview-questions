# Angular Interview Questions & Answers

> Click :star:if you like the project. Pull Requests are highly appreciated.

### Table of Contents

| No. | Questions                                                                     |
| --- | ----------------------------------------------------------------------------- |
| 1   | [Name Main Building Blocks in Angular](#name-main-building-blocks-in-angular) |

1.  ### Name Main Building Blocks in Angular

    The main building blocks for Angular are:

    **Angular Modules**

    Differs from js modules, it declares compilation context of related components dedicated to some features or domains. Groups set of related componetns, directives, pipes etc. Helps Angular compiler to properly resolve components and attach them to DOM.

    **Directives**

    Classes decorated with @Directive anotations, attribute directive which changes appereance of html element, hover, click...
    Structural Directive - *ngIf, *ngFor - built in angular core
    Directive that has template = Component.

    **Data Binding**

    Sync between the model(class) and the component's template
    Event Binding - handling of events from the template
    Property Binding - render some value in a view {{}}
    One-way vs Two-Way data binding - change a value in ts and its viewed in template. missing two way

    **Services & DI** - simple class decorated with @Injectable anotations. inject into classes, directives, services. Mechanism in angular which is repsonsible for creating, resolving and providing dependencies.

    **Pipes** - Classes with @Pipe anotation, transformation of data in templates and ts.

    **Angular Router** - allows to handle navigation in different pages in app.
