In my DevOps learning journey (Week 13), I deployed a **Node.js app** with both simple and multi-stage Docker builds on **AWS EC2**.  

## 📊 Results
- Simple Dockerfile: **1.2 GB**
- Multi-Stage Dockerfile (distroless): **3 MB**

## 🛠️ Steps I Followed
1. Created a Node.js app with frontend.
2. Wrote two Dockerfiles:
   - `Dockerfile.simple` → single-stage (large size).
   - `Dockerfile.multistage` → optimized multi-stage (tiny size).
3. Built and ran both images on AWS EC2.
4. Compared memory usage and performance.

## 🚀 Why Multi-Stage?
- Smaller image size = faster deployment.
- Cost-effective storage & bandwidth.
- More secure, fewer vulnerabilities.
- Industry standard for CI/CD pipelines.

## 🔗 Resources
- Project Repo: [simple-and-multi-stage-docker](https://github.com/azmatahmed11/simple-and-multi-stage-docker)
- My Portfolio: [azmatahmed.netlify.app](https://azmatahmed.netlify.app/)

## 🔑 Keywords
Docker, Multi-Stage Dockerfile, Node.js, DevOps Journey, AWS EC2, Distroless, Lightweight
