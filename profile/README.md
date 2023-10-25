# Google Cloud Springboard - Program Description

The Google Cloud Specialist teams support customers on their  Google Cloud journey. They design, architect and optimize in the areas of Security, Networking, Data Management and analytics, AI/ML, SAP, and Modern Applications.

The design patterns in the repository are based on real best-practice architectures that were built for customers over the last several years. The architectures are scoped down to focus on a specific goal and help you to achieve your Cloud goals faster. We designed  the architecture patterns and guides for you to test them in a sandbox environment. Architectures are also packaged with Terraform code to get you started within minutes.

We also heard from our customers that operationalization of new services and features can pose a challenge, so we added applicable details around logging, alerting, incident response and more, where applicable. Complex incident response procedures in some architectures were reviewed by our Mandiant colleagues. 

We hope you find these architectures useful and easy to integrate into your environment! We’ll be adding new to this repository constantly. 


# Architectural Patterns and Guides

The repository includes two types of architectures: **patterns** and **guides**.

An architectural **pattern** is a reusable solution to a common architectural problem that has been proven to work well in multiple situations. It provides a set of options and design decisions for how to organize, integrate and configure services and features to achieve certain qualities, such as security, maintainability, and reliability. Patterns can include multiple design options.

An architectural **guide** provides guidance on the architecture of a specific workload. It typically includes information on the system's overall structure, design principles, and practices to be used, as well as guidelines for making architectural-related decisions. It can help to align the architecture with the business and technical goals of the system, ensuring that the system is scalable, maintainable, and robust. Guides are opinionated and focus on one specific design.   



# Secured Architectures and Guides:

<table>
  <thead>
    <tr>
      <th><strong>Architecture</strong></th>
      <th><strong>Description</strong></th>
    </tr>
  </thead>
  <tbody>
      <tr>
      <td><a href="https://github.com/GCP-Architecture-Guides/GenAI-vertex-security"> GenAI Vertex Security </a>        </td>
      <td>Springboard Architecture Pattern for Network Security for Vertex-AI covering Firewall+, Secure Web Proxy and VPC-SC </td>
    </tr>
    <tr>
      <td><a href="https://github.com/GCP-Architecture-Guides/csa-fw-microsegmentation">Network Firewall Microsegmentation </a></td>
      <td>Springboard Architecture Pattern for Network Microsegmentation </td>
    </tr>
    <tr>
      <td><a href="https://github.com/GCP-Architecture-Guides/csa-certificate-authority-service">Google Cloud Certificate Authority Service deployment </a></td>
      <td>Springboard Architecture <u>Guide</u> for deploying Certificate Authority Service</td>
    </tr>
        <tr>
      <td><a href="https://github.com/GCP-Architecture-Guides/csa-gen-ai-dlp-integration">Securing User Managed Vertex-AI Workbench </a></td>
      <td>Securing Vertex AI Workbench on Google Cloud</td>
    </tr>
    <tr>
      <td><a href="https://github.com/GCP-Architecture-Guides/csa-il4-assured-workload">Deploying IL4 Assured Workload </a></td>
      <td>Creating an Assured Workloads folder for an IL4 compliance framework with VPC Service Control perimeter</td>
    </tr>
    <tr>
      <td><a href="https://github.com/GCP-Architecture-Guides/assured-workloads-australia">Deploying Australia Regions with Assured Support Workload </a></td>
      <td>Creating an Assured Workloads folder for Australia Regions with Assured Support with VPC Service Control perimeter</td>
    </tr>
   <tr>
      <td><a href="https://github.com/GCP-Architecture-Guides/SCC-cryptomining-detection">SCC Cryptomining Program </a></td>
      <td>Springboard Architecture Pattern to validate SCC configurations for cryptomining detection </td>
    </tr>
    <tr>
      <td><a href="https://github.com/GCP-Architecture-Guides/csa-swp-vertex-ai"> Secure Web Proxy </a></td>
      <td>Springboard Architecture Pattern for Secure Web Proxy </td>
    </tr>
  </tbody>
</table>
