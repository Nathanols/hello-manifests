# ☸️ Hello Argo Manifests — GitOps na Prática com ArgoCD e Kubernetes

> “Infra como código, deploy como arte — este repositório é o coração GitOps do projeto **Hello Argo**.”

---

## 🧭 Visão Geral

O repositório **`hello-manifests`** contém todos os **manifestos Kubernetes** usados pelo **ArgoCD** para gerenciar o ciclo de *deploy* da aplicação no repositório [**hello-app**](https://github.com/Nathanols/hello-app).

Aqui, o **Git é a fonte da verdade**:  
toda alteração nos manifestos é automaticamente refletida no cluster Kubernetes via **ArgoCD**.

---

## 🔄 Relação entre os Repositórios

| Repositório | Função |
|--------------|--------|
| [**hello-app**](https://github.com/Nathanols/hello-app) | Código-fonte da aplicação e pipeline CI/CD |
| **hello-manifests** | Repositório GitOps — contém os manifestos Kubernetes |

A pipeline no repositório `hello-app` atualiza automaticamente este repositório com a nova **tag da imagem Docker** gerada em cada build.

---

## 🏁 Conclusão

Com o Hello Argo Manifests, você implementa o verdadeiro fluxo GitOps:
todo o estado de deploy da aplicação está versionado e sincronizado com o cluster.

✅ Deploy automatizado  
✅ Rollout controlado pelo Git  
✅ Estado do cluster versionado  
✅ CI/CD + GitOps totalmente integrados  

💡 “O código é o coração da aplicação.
Os manifests são a alma do deploy.” 💙

