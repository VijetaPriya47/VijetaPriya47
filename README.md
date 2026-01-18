<h1  <div style="text-align: center;"> 
 <img width="400" src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=600&size=30&duration=3000&color=FFFFFF&width=535&lines=Hi%2C+I'm+Vijeta+Priya%F0%9F%91%8B;Let's+Code+and+build+together!!."/>
</div>
</h1>
</h1>
<h3 align="center">I like cats but hate bugs in my code.</h3>
<!-- <style>
h2{
  width: max-content;
  position: relative;
  cursor: pointer;
  /* margin: 100px auto; */
}
h2::after{
  content:"";
  position: absolute;
  bottom:-5px;
  height: 4px;
  width: 200px;
  left: 0;
  background-color: #490351;
  transition: 0.3s;
  transition-timing-function: ease-in-out;
  transform: scaleX(0);
}
h2:hover::after{
  transform: scaleX(1);
}
</style> -->



<h2>💫 About Me:</h2>
🔭 I'm Vijeta Priya, a determined Undergrad at NIT Agartala. My fervour for software engineering propels me to excel in DSA, Competitive Programming, Web Development, and Machine Learning basics. <br>With a passion for experimenting, I always strive to learn something new and try my hands at multiple things. <br>I’m currently working on DevOps and GoLang.

<img align="right" alt="coding" width="300" height="290" src="cats.gif">


## 🌐 Socials:
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://in.linkedin.com/in/vzsaz) 

# 💻 Tech Stack:
![C](https://img.shields.io/badge/c-%2300599C.svg?style=plastic&logo=c&logoColor=white) ![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=plastic&logo=c%2B%2B&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=plastic&logo=css3&logoColor=white)  ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=plastic&logo=html5&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=plastic&logo=javascript&logoColor=%23F7DF1E) ![Windows Terminal](https://img.shields.io/badge/Windows%20Terminal-%234D4D4D.svg?style=plastic&logo=windows-terminal&logoColor=white) ![Shell Script](https://img.shields.io/badge/shell_script-%23121011.svg?style=plastic&logo=gnu-bash&logoColor=white) ![Netlify](https://img.shields.io/badge/netlify-%23000000.svg?style=plastic&logo=netlify&logoColor=#00C7B7) ![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=plastic&logo=vercel&logoColor=white) ![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=plastic&logo=bootstrap&logoColor=white) ![DaisyUI](https://img.shields.io/badge/daisyui-5A0EF8?style=plastic&logo=daisyui&logoColor=white) ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=plastic&logo=express&logoColor=%2361DAFB) ![jQuery](https://img.shields.io/badge/jquery-%230769AD.svg?style=plastic&logo=jquery&logoColor=white) ![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=plastic&logo=npm&logoColor=white) ![Next JS](https://img.shields.io/badge/Next-black?style=plastic&logo=next.js&logoColor=white) ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=plastic&logo=node.js&logoColor=white) ![React](https://img.shields.io/badge/react-%2320232a.svg?style=plastic&logo=react&logoColor=%2361DAFB) ![React Router](https://img.shields.io/badge/React_Router-CA4245?style=plastic&logo=react-router&logoColor=white) ![React Hook Form](https://img.shields.io/badge/React%20Hook%20Form-%23EC5990.svg?style=plastic&logo=reacthookform&logoColor=white) 

# <img width="30" height="40" alt="image" src="https://github.com/user-attachments/assets/84ca4a02-a4dc-447b-a4f9-181b2ce3c401" />  GitLab Terraform Provider Contributions

| Merge Request | Status | Description |
| :--- | :--- | :--- |
| **[fix: changed GitPod References to Ona (!2806)](https://gitlab.com/gitlab-org/terraform-provider-gitlab/-/merge_requests/2806)** | Merged | Fixed a broken badge by removing Gitpod integration and updating references to Ona. |
| **[feat: add gitlab_group_service_account_access_tokens data source (!2805)](https://gitlab.com/gitlab-org/terraform-provider-gitlab/-/merge_requests/2805)** | Merged | Implemented a new data source to retrieve access tokens for group service accounts. |
| **[Add gitlab_artifact_file data source (!2721)](https://gitlab.com/gitlab-org/terraform-provider-gitlab/-/merge_requests/2721)** | Merged | Added a data source to download specific artifact files from a tag or branch. |
| **[Updated DetermineExpiryDate function signature in utils/expiry_date.go to handle the new return type(!2722)](https://gitlab.com/gitlab-org/terraform-provider-gitlab/-/merge_requests/2722)** | Merged | Fixed a logic flaw in the GitLab Terraform Provider by updating the DetermineExpiryDate signature to propagate return types correctly, ensuring callers handle potential nil values. |
| **[Add gitlab_project_package_dependency_proxy resource (!2802)](https://gitlab.com/gitlab-org/terraform-provider-gitlab/-/merge_requests/2802)** | Merged | Added a resource for configuring the project package dependency proxy. |
| **[Allow gitlab_project_label name updates without replacement (!2719)](https://gitlab.com/gitlab-org/terraform-provider-gitlab/-/merge_requests/2719)** | Merged | Proposed changes to allow updating project label names without forcing a resource replacement. |
| **[feat: add gitlab_compliance_requirement resource (!2804)](https://gitlab.com/gitlab-org/terraform-provider-gitlab/-/merge_requests/2804)** | Open | Created a new resource to manage compliance requirements within GitLab. |
| **[fix(issue-6546): trigger token rotation when expiration_days changes(!2826)](https://gitlab.com/gitlab-org/terraform-provider-gitlab/-/merge_requests/2826)** | Open |  Modified the ModifyPlan function in internal/provider/resource_gitlab_project_access_token.go to explicitly check for changes in rotation_configuration.expiration_days. If a change is detected, it now forces a plan update to rotate the token.|


### Open Source Contributions

| Project | Pull Request | Status | Description |
| :--- | :--- | :--- | :--- |
| **Hyperledger Fablo** | **[fix: Verify if post-generate.sh exists before executing (!521)](https://github.com/hyperledger-labs/fablo/pull/521)** | Merged | Fixed a bug where the network generation script would fail if the optional `post-generate.sh` hook was missing. |
| **Hyperledger Fablo** | https://github.com/hyperledger-labs/fablo/pull/594| Merged | Co-Commited with others |
| **Volcano (CNCF)** | **[Website Update (!377)](https://github.com/volcano-sh/website/pull/377)** | Merged | Contributed improvements to the official Volcano documentation site. |
| **Kubernetes** | **[Core Contribution (!135217)](https://github.com/kubernetes/kubernetes/pull/135217)** | Approved | Contributed code fixes/improvements to the core Kubernetes repository. |
| **Kubernetes** | **[Cluster Api (!13239)](https://github.com/kubernetes-sigs/cluster-api/pull/13239)** | Approved | CAPD: Remove finalizers during deletion if ownerRef was never set for cluster controllers |
| **Kubernetes** | **[Cluster Api (!13242)](https://github.com/kubernetes-sigs/cluster-api/pull/13242)** | Open | ✨Add events for automatic certificate rotation in KubeadmControlPlane |

### Open Source Contributions
Working on:
CAPI:
https://github.com/kubernetes-sigs/cluster-api/issues/12920  - MachineDrainRules WaitCompleted behavior still waits for completed Pods
#12920

https://github.com/kubernetes-sigs/cluster-api/issues/12553 - Add maxRetry to RemediationStrategy in Machinedeployment #12553
Open

Jaeger:
[Feature]: Support max_recv_msg_size_mib for gRPC storage client
#7670 - https://github.com/prometheus/prometheus/issues/17823


# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=VijetaPriya47&theme=great-gatsby&hide_border=false&include_all_commits=false&count_private=false)<br/>
![](https://github-readme-streak-stats.herokuapp.com/?user=VijetaPriya47&theme=great-gatsby&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=VijetaPriya47&theme=great-gatsby&hide_border=false&include_all_commits=false&count_private=false&layout=compact)

## 🏆 GitHub Trophies
![](https://github-profile-trophy.vercel.app/?username=VijetaPriya47&theme=monokai&no-frame=true&no-bg=false&margin-w=4)


---
[![](https://visitcount.itsvg.in/api?id=VijetaPriya47&icon=6&color=11)](https://visitcount.itsvg.in)

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->
