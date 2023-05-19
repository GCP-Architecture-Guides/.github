# Google Cloud Springboard - Program Description

The Google Cloud Security Architect team helps Google Cloud customers secure their cloud workloads based on real best-practice architectures that were built for customers over the last several years. The architectures in this repo are scoped down to focus on a specific goal. The architectures are designed with the intent to enable customers to test them in a sandbox environment. Architectures are also packaged with Terraform code to get you started within minutes.

We also heard from customers that operationalization of new services and features can pose a challenge, so we added applicable details around logging, alerting, incident response and more, where applicable. Complex incident response procedures in some architectures were reviewed by our Mandiant colleagues. 

We hope you find these secured architectures useful and easy to integrate into your environment.


# Architectural Patterns and Guides

The repo includes two types of architectures: patterns and guides.
An architectural pattern is a reusable solution to a common architectural problem that has been proven to work well in multiple situations. It provides a set of options and design decisions for how to organize, integrate and configure services and features to achieve certain qualities, such as security, maintainability, and reliability. Patterns can include multiple design options.
An architectural guide provides guidance on the architecture of a specific workload. It typically includes information on the system's overall structure, design principles, and practices to be used, as well guidelines for making architectural-related decisions. It can help to align the architecture with the business and technical goals of the system, ensuring that the system is scalable, maintainable, and robust. Guides are opinionated and focus on one specific design.    



# Architecture Lifecycle

Cloud architectures need to be reviewed and validated periodically to ensure they continue to meet the evolving needs of workloads and organizations. As technology and business requirements change, architectures that were once effective may become outdated or inefficient. Regular reviews and validations help to identify potential problems and areas for improvement, such as security vulnerabilities, performance bottlenecks, or compliance issues. Thus, each architecture will have a predefined lifetime. If a cloud architecture is not reviewed and validated periodically, it will become obsolete and removed from the architecture repository. 

# Secured Architectures:

<table>
  <thead>
    <tr>
      <th><strong>Architecture</strong></th>
      <th><strong>Description</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://github.com/GCP-Architecture-Guides/csa-fw-microsegmentation">Network Firewall Microsegmentation </a></td>
      <td>Springboard Architecture Pattern for Network Microsegmentation </td>
    </tr>
    <tr>
      <td><a href="https://github.com/GCP-Architecture-Guides/csa-certificate-authority-service">Google Cloud Certificate Authority Service deployment </a></td>
      <td>Springboard Architecture <u>Guide</u> for deploying Certificate Authority Service</td>
    </tr>
    <tr>
      <td><a href="https://github.com/GCP-Architecture-Guides/csa-il4-assured-workload">Deploying IL4 Assured Workload </a></td>
      <td>Creating an Assured Workloads folder for an IL4 compliance framework with VPC Service Control perimeter</td>
    </tr>
    <tr>
      <td><a href="https://github.com/GCP-Architecture-Guides/vertex-ai">Securing User Managed Vertex-AI Workbench </a></td>
      <td>Securing Vertex AI Workbench on Google Cloud</td>
    </tr>
  </tbody>
</table>
