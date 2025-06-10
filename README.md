# Microfrontend Projects Portfolio

Welcome to my Microfrontend Projects collection! This repository serves as a centralized showcase for all my microfrontend repositories.

## Projects

### 1. [Shell/ Orchestrator App](https://github.com/leslie628/Shell-app)  
This is the main container App that has minimal UI code, focusing solely on orchestrating the different micro apps. It has System JS and import maps (Azure storage path).

### 2. [Dashboard shell Microfrontend](https://github.com/leslie628/dashboard-shell)  
Dashboard shell micro app which orchestrates its own child micro apps. The purpose of this is to facilitate flexibility in the future addition of new features as new micro apps, as the dashboard shell evolves. The dashboard shell will register the micro apps dynamically, but the micro apps will be added to the shell app import maps. Therefore, there is no need to redeploy the dashboard shell microapp to reflect new child micro apps, as these can be added directly from the root app.

### 3. [Dashboard Microfrontend](https://github.com/leslie628/dashboard-app)  
Main user dashboard micro app -> child micro app of Dashboard shell.

### 4. [Settings Microfrontend](https://github.com/leslie628/settings-app)  
Settings micro app.

### 5. [User profile Microfrontend](https://github.com/leslie628/user-profile)  
User profile micro app.

---

## Overview

Each microfrontend is developed as an independent repository to allow modular development, easy deployment, and seamless integration using microfrontend architecture principles.

Feel free to explore the code, issues, and demos in each repository.

---

## Contact

[fernandesleslie48@gmail.com].

---

*Last updated: June 2025*
