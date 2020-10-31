# เตรียมสอบ CKAD ฉบับพัท

### การเตรียมการตั้งค่าก่อนสอบ

```
vim ~/.bashrc หรือ ไม่ต้องเข้าไปจัดการส่วนนี้ก็ได้
alias k="kubectl"
alias kf="kubectl apply -f"
alias kgp="kubectl get po -o wide"
alias kn=" kubectl config set-context --current --namespace"
alias krm="kubectl delete --force --grace-periods=0"
```
### กรณีลืมระหว่างสอบ
```
kubectl create ขนิด --help
```
### ฟังก์ชั่น vim ที่ใช้บ่อย
```
:<line-number> — ไปยังบรรทัดที่ต้องการ
/<text> — หา text
:2,20d - ลบบรรทัดั้งแต่บรรทัดที่ 2 ถึง 20
```
### ตั้งค่า vim ก่อนสอบ
```
~/.vimrc
set tabstop=2  # เมื่อกด Tab แล้วให้ขยับหรือ หยุดที่ 2 space
set expandtab # เอาไว้ตอนกด Tab และให้เปลี่ยนเป็น spaces
set list # เพื่อดูว่า ช่องว่างนั้นเป็น Tab หรือไม่ เพราะ yaml ของ kubernetes ไม่อนุญาติให้มี Tab
set shiftwidth=2 # ใช้ตอนโหมด virsual(v) กรณีที่จะปรับ spaces พร้อม ๆ กัน แบบหลายบรรทัด ( shift + >)
set nu # เพื่อแสดงตัวเลข
set paste # เพื่อที่จะสามารถ copy and paste ลง vim แล้ว format เดิมไม่เสีย
```
### [คะแนนในแต่ละหัวข้อ](https://github.com/cncf/curriculum)
![](https://github.com/nitikornchumnankul/ckad/blob/main/resources/Exam%20Curriculum.png)

### [ทำความเข้าใจในแต่ละหัวข้อ](https://github.com/nitikornchumnankul/ckad/wiki)

#### [1. Core Concept](https://github.com/nitikornchumnankul/ckad/wiki/1.-Core-Concept)

#### [2. Configuration](https://github.com/nitikornchumnankul/ckad/wiki/2.-Configuration)

#### [3. Multi Container Pods](https://github.com/nitikornchumnankul/ckad/wiki/3.-Multi-Container-Pods)

#### [4. Observability](https://github.com/nitikornchumnankul/ckad/wiki/4.-Observability)

#### [5. Pod Design](https://github.com/nitikornchumnankul/ckad/wiki/5.-Pod-Design)

#### [6. Services & Networking](https://github.com/nitikornchumnankul/ckad/wiki/6.-Services-&-Networking)

#### [7. State Persistence](https://github.com/nitikornchumnankul/ckad/wiki/7.-State-Persistence)


## [ตรวจสอบเครื่องมือก่อนสอบ](https://www.examslocal.com/ScheduleExam/Home/CompatibilityCheck)

![](https://github.com/nitikornchumnankul/ckad/blob/main/resources/Screenshot%202020-10-10%20152928.png)

## ติดตั้ง PSI, เช็คความพร้อมของเครื่องคอมและอินเตอร์เน็ต
![](https://github.com/nitikornchumnankul/ckad/blob/main/resources/Screenshot%202020-10-10%20153029.png)

### หน้าตา Terminal ตอนสอบ
![หน้าตา Terminal ตอนสอบ](https://gblobscdn.gitbook.com/assets%2F-M1fWjlaqrc5PxRuWkRx%2F-MACIp1sRjCeyzqaACz5%2F-MACPci2XER6SneRwukr%2FLF%20Certification%20Exams%20ExamUI.png?alt=media&token=7c2ae009-8cd4-4d28-ae6f-d2fdcee2feb8)

### หน้าตาฝึกซ้อมจำลองของ [killer.sh](https://killer.sh/login)
![หน้าตาฝึกซ้อมจำลองของ killer.sh](https://miro.medium.com/max/1000/1*lYPcto6TAy2oSh7O2u49_Q.png)




## [System Requirements to take the exam](https://docs.linuxfoundation.org/tc-docs/certification/tips-cka-and-ckad)

Exams are delivered online and Candidates must provide their own computer with:

Current version of Chrome or Chromium
you don’t need to install a virtual machine, use a client machine, or anything beyond a Chrome or Chromium browser
Make sure you have third party cookies turned on for the duration of the exam.

Reliable internet access
Turn off bandwidth-intensive services (e.g. file sync, dropbox, BitTorrent)
Ask others who may be sharing your Internet connection not to stream video or download large files.

Microphone
Please check to make sure it is working before you start your exam session.

Webcam
Ensure the webcam is capable of being moved as the proctor may ask you to pan your surroundings to check for potential violations of exam policy.
Try holding up your ID while viewing your webcam feed to ensure your placement and resolution are sufficient for the person viewing your feed to read your ID.
If you will be testing from an employer-provide ISP or will use an employer provided machine, please ensure that streaming will be allowed using WebRTC.

### [Exam Preparation Checklist](https://docs.linuxfoundation.org/tc-docs/certification/lf-candidate-handbook/exam-preparation-checklist#checklist-items)
![](https://gblobscdn.gitbook.com/assets%2F-M1fWjlaqrc5PxRuWkRx%2F-MABF2cv7lBvbGMGKiqO%2F-MABGlPn5fhdzevUhOP4%2Fexam%20checklist.png?alt=media&token=0d10ac41-3998-4df5-b0cb-b4826b3a8450)

### [My Profile](https://docs.linuxfoundation.org/tc-docs/certification/lf-candidate-handbook/my-profile)
![](https://gblobscdn.gitbook.com/assets%2F-M5QaeeC1mG9VndIpgJe%2F-MCQgtM4-VukLM1tG7xH%2F-MCQmzJ_-hjLYg8SqXXM%2F2.png?alt=media&token=743afd30-84a8-4ee5-9e28-112511c8146f)



## [What score is needed to pass the exam?](https://docs.linuxfoundation.org/tc-docs/certification/faq-cka-ckad-cks)

For the CKAD Exam, a score of 66% or above must be earned to pass.


# References

[ตัวอย่างข้อสอบ](https://www.youtube.com/watch?v=5cgpFWVD8ds)

[สอนวิธีทำให้ไว](https://www.youtube.com/watch?v=dIBX8TQJxW8)

[The CKAD browser terminal](https://codeburst.io/the-ckad-browser-terminal-10fab2e8122e)

[Passing CKAD — tips & tricks](https://medium.com/@afkham_azeez/passing-ckad-tips-tricks-e24712f3e4a4)

[How to pass CKAD exam in first attempt ? Tips & Tricks in Kubernetes](https://medium.com/@nikhilagrawal577/how-to-pass-ckad-exam-in-1st-attempt-tips-tricks-in-k8s-9e14477699ca)

[Exam User Interface](https://docs.linuxfoundation.org/tc-docs/certification/lf-candidate-handbook/exam-user-interface#linux-server-terminal)

[ckad-prep-notes ****](https://github.com/twajr/ckad-prep-notes)

[CKAD Tips Kubernetes](https://killer.sh/attendee/b3b6d191-f657-43f6-ae07-7663fe9dc375/tips)

[CKAD-commands](https://github.com/marcusvieira88/CKAD-commands)

[Kubernetes - tips for your CKAD exam by CNCF***](https://en.sokube.ch/post/kubernetes-tips-for-your-ckad-exam-by-cncfX)

[CKAD Certification Exam Preparation Guide and Tips (Aspect)](https://kloudnative.blogspot.com/2020/09/ckad-certification-exam-preparation.html?m=1&fbclid=IwAR3x-EgpkNt2C31o9vw3jzrJSxiI2LkDW2GgQGLjgaTf0ABCAa3jaK1Ejus)
