# Chatur Backend

The Chatur Backend includes virtual machines running on a self-managed :simple-openstack: OpenStack Cloud.

We'll use the analogy of building a digital :material-sail-boat: boat for the project.

Chatur is built of a combination of open-source projects including: 

| Backend - Rudder | LLM - Sails/Propellers | UI - Crow's Nest | UX - Anchor |
|------------------|------------------------|------------------|-------------|
| [FastChat]() | [LangServ(LangChain)]() | [PrivateGPT]() | Tests |
| [Ray.io]() | [ollama]() | React / NextJS | QA/QC |
| [CyVerse]() | [Mistral]() | MaterialUI | |
| [Jetstream-2]() | | OAuth | |

:simple-ansible: Ansible Playbooks are used to deploy the software on :simple-openstack: OpenStack Cloud managed hardware

:simple-kubernetes: K8s Helm Charts deploy the backend [API](api.md)

:simple-nextdotjs: NextJS and React are used for the `https://` user interface [UI](ui.md)

OAuth & LDAP secure authentication are provided by CyVerse and University of Arizona. 
