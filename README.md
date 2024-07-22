![TS4NFDI_short1](https://github.com/base4nfdi/ts4nfdi/assets/67650599/f2e483e8-fd21-44b8-a5ed-34c160bb8e3f)

# TS4NFDI
Terminology Services 4 NFDI (TS4NFDI) is a cross domain service for the provision, curation, development, harmonization 
and mapping of terminologies. It aims to facilitate consensus-building and interoperability of services across 
disciplines to achieve a shared knowledge representation and knowledge engineering framework. The service seeks to 
integrate and converge individual solutions into a standardized, interoperable, and sustainable service suite with 
Service Wrapper, API Gateway, mapping service and reusable GUI widgets.

## Workplace
All repositories of TS4NFDI are maintained in a __GitHub organization__. Which means that the code, the documentation 
and the issue tracking is directly accessible via GitHub. 

### Terminology Service Suite
The [Terminology Service Suite](https://github.com/ts4nfdi/terminology-service-suite) was derived from the 
[SemLookP](https://semanticlookup.zbmed.de/) project and is now hosted on GitHub under the 
[TS4NFDI](https://github.com/ts4nfdi) organization. It is a collection of interactive widgets designed to ease the 
integration of terminology service functions into third-party applications.

The widgets are built using React and TypeScript and can be used in both React and plain HTML applications. The
functionality and arguments are the same for the React and plain HTML versions. Only the code snippet you get when you
click "Show code" in the Storybook is different.

#### Terminology Service Suite Documentation
You will find an interactive documentation of the widget component library in a 
[Storybook](https://ts4nfdi.github.io/terminology-service-suite/comp/latest/).

#### Demo projects

##### React demo project
A simple Next.js project to demonstrate the integration of the Terminology Service Suite widgets.
[Terminology Service Suite Widgets React Application](https://github.com/ts4nfdi/react-widgets-demo-project)

##### PlainJS demo project
This is an example project illustrating the use of Terminology Service Suite widgets in a plain JavaScript environment.
[Terminology Service Suite Widgets JavaScript Application](https://github.com/ts4nfdi/JS-Widgets-Demo-Project)

### API Gateway
The [API Gateway](https://github.com/ts4nfdi/api-gateway) acts as a single access point for API requests over various 
NFDI terminology services. It will provide standardised APIs for all NFDI services to access all available 
terminologies. The gateway could handle [OLS](https://github.com/EBISPOT/ols4/), 
[OntoPortal](https://github.com/ontoportal/) and [Skosmos](https://github.com/NatLibFi/Skosmos) as technology 
software stacks as backend system.

## Proposal
Further information about the project could be found in the [proposal](https://doi.org/10.5281/zenodo.12188787).

## Website
More information about TS4NFDI could be found on the [Base4NFDI website](https://base4nfdi.de/projects/ts4nfdi).

## License
This repository is licenced under the Creative Commons 
[CC-BY-SA-4.0 licence](https://creativecommons.org/licenses/by-sa/4.0/).

