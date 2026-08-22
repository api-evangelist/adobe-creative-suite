# Adobe Creative Suite (adobe-creative-suite)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Adobe Creative Suite is a collection of professional software applications for graphic design, video editing, web development, and photography.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/adobe-creative-suite/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/adobe-creative-suite/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Creative
- Design
- Graphics
- Photography
- Video

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Adobe Photoshop API

The Adobe Photoshop API provides programmatic access to Photoshop image manipulation capabilities including automated editing, masking, and compositing. It enables developers to integrate Photoshop processing into workflows and applications without requiring a desktop installation. The API supports common Photoshop operations such as layer manipulation, smart object editing, and image transformation.

- **Human URL:** [https://developer.adobe.com/photoshop/](https://developer.adobe.com/photoshop/)
- **Base URL:** `https://image.adobe.io`

#### Tags

- Automation
- Graphics
- Image Editing
- Photoshop

#### Properties

- [Documentation](https://developer.adobe.com/photoshop/api/)
- [OpenAPI](https://developer.adobe.com/photoshop/api/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/adobe-creative-suite-photoshop-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/adobe-creative-suite-photoshop.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-photoshop.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/adobe-creative-suite-image-job-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Authentication](https://developer.adobe.com/developer-console/docs/guides/authentication/)

### Adobe Lightroom API

The Adobe Lightroom API provides access to photo management features including albums, collections, and editing presets stored in the Lightroom cloud catalog. Developers can use it to build integrations that read, organize, and manage photos on behalf of Lightroom users. The API uses OAuth 2.0 for user authentication and follows RESTful conventions.

- **Human URL:** [https://developer.adobe.com/lightroom/](https://developer.adobe.com/lightroom/)
- **Base URL:** `https://lr.adobe.io`

#### Tags

- Editing
- Lightroom
- Photo Management
- Photography

#### Properties

- [Documentation](https://developer.adobe.com/lightroom/api/)
- [OpenAPI](https://developer.adobe.com/lightroom/api/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Authentication](https://developer.adobe.com/developer-console/docs/guides/authentication/)
- [Postman Collection](collections/adobe-creative-suite-firefly.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-firefly.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/adobe-creative-suite-pdf-services.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-pdf-services.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/adobe-creative-suite-photoshop.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-photoshop.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/adobe-creative-suite-stock.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-stock.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Adobe Illustrator API

The Adobe Illustrator API enables programmatic creation and manipulation of vector graphics through scripting and plugin interfaces. It exposes the Illustrator object model so developers can automate repetitive design tasks, generate artwork, and integrate Illustrator into production pipelines. The API is available via UXP plugins and CEP extensions as well as scripting environments.

- **Human URL:** [https://developer.adobe.com/illustrator/](https://developer.adobe.com/illustrator/)
- **Base URL:** `https://image.adobe.io`

#### Tags

- Automation
- Design
- Illustrator
- Vector Graphics

#### Properties

- [Documentation](https://developer.adobe.com/illustrator/api/)
- [Authentication](https://developer.adobe.com/developer-console/docs/guides/authentication/)
- [Postman Collection](collections/adobe-creative-suite-firefly.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-firefly.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/adobe-creative-suite-pdf-services.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-pdf-services.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/adobe-creative-suite-photoshop.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-photoshop.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/adobe-creative-suite-stock.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-stock.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Adobe InDesign API

The Adobe InDesign API allows developers to automate document layout and publishing workflows through scripting and UXP plugins. It exposes InDesign's document model for tasks such as batch exporting, template population, and preflight automation. The API supports JavaScript, AppleScript, and VBScript as well as the newer UXP plugin architecture.

- **Human URL:** [https://developer.adobe.com/indesign/](https://developer.adobe.com/indesign/)
- **Base URL:** `https://indesign-api.adobe.io`

#### Tags

- Documents
- InDesign
- Layout
- Publishing

#### Properties

- [Documentation](https://developer.adobe.com/indesign/uxp/)
- [Authentication](https://developer.adobe.com/developer-console/docs/guides/authentication/)
- [Postman Collection](collections/adobe-creative-suite-firefly.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-firefly.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/adobe-creative-suite-pdf-services.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-pdf-services.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/adobe-creative-suite-photoshop.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-photoshop.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/adobe-creative-suite-stock.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-stock.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Adobe Premiere Pro API

The Adobe Premiere Pro API gives developers access to video editing automation through scripting and panel extensions. It allows integration with external media asset management systems, automated sequence assembly, and custom export workflows. The API is accessible through CEP extensions and the UXP plugin framework.

- **Human URL:** [https://developer.adobe.com/premiere-pro/](https://developer.adobe.com/premiere-pro/)
- **Base URL:** `https://premiere-api.adobe.io`

#### Tags

- Automation
- Media
- Premiere Pro
- Video Editing

#### Properties

- [Documentation](https://developer.adobe.com/premiere-pro/docs/)
- [Authentication](https://developer.adobe.com/developer-console/docs/guides/authentication/)
- [Postman Collection](collections/adobe-creative-suite-firefly.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-firefly.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/adobe-creative-suite-pdf-services.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-pdf-services.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/adobe-creative-suite-photoshop.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-photoshop.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/adobe-creative-suite-stock.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-stock.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Adobe After Effects API

The Adobe After Effects API enables scripting and plugin development for motion graphics and visual effects workflows. Developers can automate rendering, manipulate compositions programmatically, and build custom effects using the SDK. The API supports ExtendScript, CEP panels, and the newer UXP and plugin SDK approaches.

- **Human URL:** [https://developer.adobe.com/after-effects/](https://developer.adobe.com/after-effects/)
- **Base URL:** `https://aftereffects-api.adobe.io`

#### Tags

- After Effects
- Animation
- Motion Graphics
- Visual Effects

#### Properties

- [Documentation](https://developer.adobe.com/after-effects/docs/)
- [Reference](https://ae-scripting.docsforadobe.dev/)
- [Authentication](https://developer.adobe.com/developer-console/docs/guides/authentication/)
- [Postman Collection](collections/adobe-creative-suite-firefly.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-firefly.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/adobe-creative-suite-pdf-services.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-pdf-services.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/adobe-creative-suite-photoshop.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-photoshop.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/adobe-creative-suite-stock.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-stock.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Adobe Creative Cloud Libraries API

The Adobe Creative Cloud Libraries API provides access to shared design assets stored in Creative Cloud Libraries, including colors, character styles, graphics, and components. It allows applications to read and write library elements on behalf of authenticated users. The API is commonly used to sync brand assets across design tools and third-party platforms.

- **Human URL:** [https://developer.adobe.com/creative-cloud-libraries/](https://developer.adobe.com/creative-cloud-libraries/)
- **Base URL:** `https://cc-libraries.adobe.io`

#### Tags

- Assets
- Collaboration
- Creative Cloud
- Libraries

#### Properties

- [Documentation](https://developer.adobe.com/creative-cloud-libraries/docs/)
- [Reference](https://developer.adobe.com/creative-cloud-libraries/api/)
- [Authentication](https://developer.adobe.com/developer-console/docs/guides/authentication/)
- [Postman Collection](collections/adobe-creative-suite-firefly.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-firefly.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/adobe-creative-suite-pdf-services.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-pdf-services.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/adobe-creative-suite-photoshop.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-photoshop.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/adobe-creative-suite-stock.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-stock.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Adobe Stock API

The Adobe Stock API enables search, licensing, and retrieval of stock photos, illustrations, vectors, videos, and templates from the Adobe Stock marketplace. It supports both editorial and commercial licensing workflows and can be integrated into creative applications and DAM systems. The API uses OAuth 2.0 and API key authentication depending on the operation.

- **Human URL:** [https://developer.adobe.com/stock/](https://developer.adobe.com/stock/)
- **Base URL:** `https://stock.adobe.io`

#### Tags

- Images
- Licensing
- Stock
- Video

#### Properties

- [Documentation](https://developer.adobe.com/stock/docs/)
- [Reference](https://developer.adobe.com/stock/docs/api/)
- [OpenAPI](https://developer.adobe.com/stock/docs/api/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/adobe-creative-suite-stock-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/adobe-creative-suite-stock.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-stock.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/adobe-creative-suite-stock-file-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Authentication](https://developer.adobe.com/developer-console/docs/guides/authentication/)

### Adobe Firefly API

The Adobe Firefly API provides access to Adobe's generative AI capabilities for creating and editing images, vectors, and text effects from natural language prompts. It is built on the Firefly family of creative generative models trained on licensed and public domain content. The API supports text-to-image generation, generative fill, generative expand, and style transfer operations.

- **Human URL:** [https://developer.adobe.com/firefly-api/](https://developer.adobe.com/firefly-api/)
- **Base URL:** `https://firefly-api.adobe.io/v3`

#### Tags

- Creative AI
- Firefly
- Generative AI
- Image Generation

#### Properties

- [Documentation](https://developer.adobe.com/firefly-api/docs/)
- [Getting Started](https://developer.adobe.com/firefly-api/docs/guides/get-started/)
- [Reference](https://developer.adobe.com/firefly-api/docs/api/)
- [OpenAPI](openapi/adobe-creative-suite-firefly-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/adobe-creative-suite-firefly.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-firefly.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/adobe-creative-suite-firefly-generation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Authentication](https://developer.adobe.com/developer-console/docs/guides/authentication/)

### Adobe PDF Services API

The Adobe PDF Services API provides cloud-based tools for creating, converting, combining, compressing, and extracting content from PDF documents. It is part of the Adobe Acrobat Services platform and supports operations such as HTML-to-PDF, PDF-to-Word, OCR, and PDF accessibility auto-tagging. The API offers SDKs for Java, Node.js, .NET, and Python.

- **Human URL:** [https://developer.adobe.com/document-services/](https://developer.adobe.com/document-services/)
- **Base URL:** `https://pdf-services.adobe.io`

#### Tags

- Acrobat
- Document Conversion
- Document Services
- PDF

#### Properties

- [Documentation](https://developer.adobe.com/document-services/docs/overview/)
- [Getting Started](https://developer.adobe.com/document-services/docs/overview/pdf-services-api/gettingstarted/)
- [Reference](https://developer.adobe.com/document-services/docs/apis/)
- [Client  Libraries](https://developer.adobe.com/document-services/docs/overview/pdf-services-api/sdks/)
- [OpenAPI](openapi/adobe-creative-suite-pdf-services-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/adobe-creative-suite-pdf-services.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-pdf-services.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://developer.adobe.com/developer-console/docs/guides/authentication/)

### Adobe Analytics API

The Adobe Analytics API provides programmatic access to Adobe Analytics report suites for retrieving, segmenting, and analyzing web and app behavioral data. It supports both the Reporting API for querying metrics and dimensions and the Data Insertion API for sending custom event data. The API is used to automate reporting, build custom dashboards, and integrate analytics data into external systems.

- **Human URL:** [https://developer.adobe.com/analytics-apis/docs/2.0/](https://developer.adobe.com/analytics-apis/docs/2.0/)
- **Base URL:** `https://analytics.adobe.io/api`

#### Tags

- Analytics
- Data
- Experience Cloud
- Reporting

#### Properties

- [Documentation](https://developer.adobe.com/analytics-apis/docs/2.0/)
- [Getting Started](https://developer.adobe.com/analytics-apis/docs/2.0/guides/)
- [Reference](https://developer.adobe.com/analytics-apis/docs/2.0/api/)
- [Authentication](https://developer.adobe.com/developer-console/docs/guides/authentication/)
- [Postman Collection](collections/adobe-creative-suite-firefly.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-firefly.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/adobe-creative-suite-pdf-services.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-pdf-services.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/adobe-creative-suite-photoshop.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-photoshop.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/adobe-creative-suite-stock.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-stock.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Adobe Experience Manager Assets API

The Adobe Experience Manager Assets API provides access to the AEM digital asset management system for uploading, retrieving, and managing assets stored in AEM as a Cloud Service. It enables integration with external systems for asset ingestion, metadata management, and rendition retrieval. The API follows RESTful conventions and uses Adobe IMS for authentication.

- **Human URL:** [https://developer.adobe.com/experience-manager/](https://developer.adobe.com/experience-manager/)
- **Base URL:** `https://author-{program}-{environment}.adobeaemcloud.com/api`

#### Tags

- AEM
- Content Management
- Digital Asset Management
- Experience Manager

#### Properties

- [Documentation](https://developer.adobe.com/experience-manager/reference-materials/cloud-service/javadoc/)
- [Getting Started](https://developer.adobe.com/experience-manager/documentation/)
- [Reference](https://developer.adobe.com/experience-manager/reference-materials/)
- [Authentication](https://developer.adobe.com/developer-console/docs/guides/authentication/)
- [Postman Collection](collections/adobe-creative-suite-firefly.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-firefly.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/adobe-creative-suite-pdf-services.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-pdf-services.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/adobe-creative-suite-photoshop.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-photoshop.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/adobe-creative-suite-stock.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-stock.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Adobe Acrobat Sign API

The Adobe Acrobat Sign API enables sending, tracking, and managing electronic signature agreements programmatically. It supports creating agreements from documents or templates, managing signers and routing, and retrieving signed documents and audit trails. The API is available in region-specific deployments and uses OAuth 2.0 for authentication.

- **Human URL:** [https://developer.adobe.com/adobesign/docs/](https://developer.adobe.com/adobesign/docs/)
- **Base URL:** `https://api.na1.adobesign.com/api/rest/v6`

#### Tags

- Acrobat Sign
- Agreements
- Documents
- Electronic Signatures

#### Properties

- [Documentation](https://developer.adobe.com/adobesign/docs/)
- [Getting Started](https://developer.adobe.com/adobesign/docs/gstarted/)
- [Reference](https://developer.adobe.com/adobesign/docs/apis/)
- [Authentication](https://developer.adobe.com/adobesign/docs/gstarted/authentication/)
- [Postman Collection](collections/adobe-creative-suite-firefly.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-firefly.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/adobe-creative-suite-pdf-services.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-pdf-services.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/adobe-creative-suite-photoshop.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-photoshop.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/adobe-creative-suite-stock.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-stock.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Adobe Fonts API

The Adobe Fonts API provides access to the Adobe Fonts library for discovering and embedding web fonts in applications and websites. It allows querying font families, retrieving font metadata, and generating web font embed codes for use with Creative Cloud subscriptions. The API is commonly used by design tools and CMSs to expose the Adobe Fonts catalog to users.

- **Human URL:** [https://fonts.adobe.com/](https://fonts.adobe.com/)
- **Base URL:** `https://fonts.adobe.io`

#### Tags

- Design
- Fonts
- Typography
- Web Fonts

#### Properties

- [Documentation](https://developer.adobe.com/fonts/docs/)
- [Reference](https://developer.adobe.com/fonts/docs/api/)
- [Authentication](https://developer.adobe.com/developer-console/docs/guides/authentication/)
- [Postman Collection](collections/adobe-creative-suite-firefly.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-firefly.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/adobe-creative-suite-pdf-services.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-pdf-services.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/adobe-creative-suite-photoshop.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-photoshop.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/adobe-creative-suite-stock.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-stock.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Adobe Express Embed SDK

The Adobe Express Embed SDK allows developers to embed Adobe Express editing capabilities directly into their own web applications. It provides a customizable in-app editing experience for images, videos, and templates powered by the Adobe Express platform. The SDK supports use cases such as branded template creation, social media asset editing, and document design within third-party products.

- **Human URL:** [https://developer.adobe.com/express/embed-sdk/](https://developer.adobe.com/express/embed-sdk/)
- **Base URL:** `https://express-api.adobe.io`

#### Tags

- Design
- Embed SDK
- Express
- Templates

#### Properties

- [Documentation](https://developer.adobe.com/express/embed-sdk/docs/)
- [Getting Started](https://developer.adobe.com/express/embed-sdk/docs/guides/getting_started/)
- [Reference](https://developer.adobe.com/express/embed-sdk/docs/reference/)
- [Authentication](https://developer.adobe.com/developer-console/docs/guides/authentication/)
- [Postman Collection](collections/adobe-creative-suite-firefly.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-firefly.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/adobe-creative-suite-pdf-services.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-pdf-services.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/adobe-creative-suite-photoshop.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-photoshop.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/adobe-creative-suite-stock.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-stock.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Adobe UXP

Adobe UXP (Unified Extensibility Platform) is the modern plugin and scripting platform used across Adobe creative applications including Photoshop, InDesign, Illustrator, and XD. It provides a JavaScript-based runtime with access to application APIs, a React-compatible UI framework, and a unified plugin distribution system via the Creative Cloud marketplace. UXP replaces the older CEP (Common Extensibility Platform) and ExtendScript plugin architectures.

- **Human URL:** [https://developer.adobe.com/uxp/](https://developer.adobe.com/uxp/)
- **Base URL:** `https://developer.adobe.com/uxp/`

#### Tags

- Creative Cloud
- Extensibility
- Plugins
- UXP

#### Properties

- [Documentation](https://developer.adobe.com/uxp/docs/)
- [Getting Started](https://developer.adobe.com/uxp/docs/guides/)
- [Reference](https://developer.adobe.com/uxp/docs/reference/)
- [GitHub Repository](https://github.com/adobe/uxp-photoshop)
- [Authentication](https://developer.adobe.com/developer-console/docs/guides/authentication/)
- [Postman Collection](collections/adobe-creative-suite-firefly.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-firefly.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/adobe-creative-suite-pdf-services.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-pdf-services.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/adobe-creative-suite-photoshop.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-photoshop.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/adobe-creative-suite-stock.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/adobe-creative-suite-stock.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [JSON-LD](json-ld/adobe-creative-suite-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/adobe-creative-suite-image-job-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/adobe-creative-suite-firefly-generation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/adobe-creative-suite-stock-file-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Portal](https://developer.adobe.com/)
- [Sign Up](https://developer.adobe.com/console/home)
- [Getting Started](https://developer.adobe.com/developer-console/docs/guides/getting-started/)
- [Documentation](https://developer.adobe.com/developer-console/docs/)
- [Blog](https://blog.developer.adobe.com/)
- [GitHub Organization](https://github.com/adobe)
- [Community](https://community.adobe.com/t5/developers/ct-p/developers)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/adobe)
- [Console](https://developer.adobe.com/console/)
- [Authentication](https://developer.adobe.com/developer-console/docs/guides/authentication/)
- [Changelog](https://developer.adobe.com/developer-console/docs/release-notes/)
- [Support](https://developer.adobe.com/support/)
- [Status Page](https://status.adobe.com/)
- [Terms of Service](https://www.adobe.com/legal/terms.html)
- [Privacy Policy](https://www.adobe.com/privacy.html)
- [Features](undefined)
- [Use Cases](undefined)
- [Solutions](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
