## End-to-End Pipeline Flow
![Java-maven-CI-CD-Project](https://github.com/user-attachments/assets/5d27b124-31c9-43c0-a0ee-decc0748d9f4)



---

##  Features

- **Jenkins** pipeline triggered via GitHub Webhook  
- **Maven** build and test automation  
- **SonarQube** static code analysis  
- **Docker** image build and push to DockerHub  
- **Shell Script** to update Kubernetes manifest with the latest image tag  
- **ArgoCD** GitOps-driven deployment to Kubernetes  

---

## Tools & Technologies

- Jenkins  
- Maven  
- SonarQube  
- Docker  
- Kubernetes  
- ArgoCD  
- GitHub Webhooks  
- Shell scripting  

---

##  CI/CD Pipeline Flow

flowchart TD
    A[Developer Pushes Code] --> B[GitHub Webhook]
    B --> C[Jenkins Pipeline]
    C --> D[Maven Build & Test]
    D --> E[SonarQube Analysis]
    E --> F[Docker Build & Push to DockerHub]
    F --> G[Update Kubernetes Manifest (Shell Script)]
    G --> H[ArgoCD Syncs to Kubernetes]

## Screenshots
**GitHub Webhook**
<img width="1890" height="927" alt="github-webhook" src="https://github.com/user-attachments/assets/77c64a1d-102a-4328-8df6-a314e4af4aa1" />
**Jenkins**
<img width="1860" height="935" alt="jenkins" src="https://github.com/user-attachments/assets/65a590fc-79d5-4a0e-b947-60a505c461e3" />
**SonarQube**
<img width="1522" height="823" alt="sonarqube new" src="https://github.com/user-attachments/assets/23fbd78a-a4a2-4b97-a6cd-bee99ca2f9d8" />
**ArgoCD**
<img width="1862" height="937" alt="argocd new" src="https://github.com/user-attachments/assets/3278ab12-8884-4d1a-aaf1-f2c98a08babc" />
