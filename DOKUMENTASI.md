# **Anggota Kelompok**
1. Maulia Dwi Anthesa Sugeha - 235150201111060
2. Irene Noer Ramadhany - 235150207111064

Pada arsitektur awal terdapat 2 node worker. Lalu, kami melakukan penambahan 1 node worker sehingga total menjadi 3 node worker.
## **Seluruh node worker (Worker 1, Worker 2, dan Worker 3) berhasil dihubungkan ke node master dan menjadi bagian dari cluster Kubernetes.**

Worker 1 berhasil terhubung ke master
<img width="873" height="520" alt="image" src="https://github.com/user-attachments/assets/88f4ded0-4c3d-4153-9cbd-928635dfde60" />

Worker 2 berhasil terhubung ke master
<img width="736" height="523" alt="Screenshot 2026-04-15 130708" src="https://github.com/user-attachments/assets/d7601087-a0dd-4f89-af8f-e58b14080e6b" />

Worker 3 berhasil terhubung ke master
<img width="738" height="522" alt="Screenshot 2026-04-15 130634" src="https://github.com/user-attachments/assets/5ff4f0d6-e3bc-458b-9134-b9fac4dfe241" />

Seluruh worker sudah terhubung ke master
<img width="738" height="130" alt="image" src="https://github.com/user-attachments/assets/95b38e80-d45a-424c-bc05-0b18733d51b5" />

## **Deploy aplikasi k8s-login-app/aplikasi lain sebanyak 3 replicas**

Setelah seluruh node (master dan worker) berhasil terhubung dalam satu cluster, tahap selanjutnya adalah kami melakukan deployment aplikasi pada Kubernetes. 
Kami berhasil melakukan deployment:
<img width="736" height="219" alt="image" src="https://github.com/user-attachments/assets/6fd8909f-ad92-48d3-9600-c8766fdb42fa" />
<img width="1300" height="867" alt="image" src="https://github.com/user-attachments/assets/76cb8ba0-6aa1-4ce2-83f0-e57d08da23ef" />
