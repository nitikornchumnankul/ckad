# เตรียมสอบ CKAD ฉบับภาษาไทย

### การเตรียมการตั้งค่าก่อนสอบ

```
vim ~/.bashrc
alias k="kubectl"
alias kf="kubectl apply -f"
alias kgp="kubectl get po -o wide"
alias kn=" kubectl config set-context --current --namespace"
alias krm="kubectl delete --force --grace-periods=0"
```
### declarative command line ของ kubernetes ที่ใช้ kubectl create ได้ (ขอบเขตในข้อสอบ)
1. Deployment
```
kubectl create deploy 
```
2. configmap
```
kubectl create cm 
```

3. cronjob
```
kubectl create cj
```

4. job
```
kubectl create job
```

5. namespace
```
kubectl create namespace
```

6. quota
```
kubectl create quota
```
7. secret
```
kubectl create secret generic
```
8. serviceaccount
```
kubectl create sa
```

### กรณีลืมระหว่างสอบ
```
kubectl create ขนิด --help
```

### การใช้ VI ให้ไว
```
:<line-number> — go to line
/<text> — find text
<n>yy — copy n number of lines from cursor. Just yy to copy a single line
p — paste copied lines
G — go to end of file
gg — go to start of file
x — delete character
<n>dd — delete n nmber of lines. Just dd to delete a single line
```
### vim
```
~/.vimrc
set tabstop=2
set expandtab
set list
```
### หน้าตา Terminal ตอนสอบ
![หน้าตา Terminal ตอนสอบ](https://gblobscdn.gitbook.com/assets%2F-M1fWjlaqrc5PxRuWkRx%2F-MACIp1sRjCeyzqaACz5%2F-MACPci2XER6SneRwukr%2FLF%20Certification%20Exams%20ExamUI.png?alt=media&token=7c2ae009-8cd4-4d28-ae6f-d2fdcee2feb8)

### หน้าตาฝึกซ้อมจำลองของ [killer.sh](https://killer.sh/login)
![หน้าตาฝึกซ้อมจำลองของ killer.sh](https://miro.medium.com/max/1000/1*lYPcto6TAy2oSh7O2u49_Q.png)


## [ตรวจสอบเครื่องมือก่อนสอบ](https://www.examslocal.com/ScheduleExam/Home/CompatibilityCheck)

![](https://github.com/nitikornchumnankul/ckad/blob/main/resources/Screenshot%202020-10-10%20152928.png)

![](https://github.com/nitikornchumnankul/ckad/blob/main/resources/Screenshot%202020-10-10%20153029.png)

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
### [คะแนนในแต่ละหัวข้อ](https://github.com/cncf/curriculum)
![](https://github.com/nitikornchumnankul/ckad/blob/main/resources/Exam%20Curriculum.png)


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

[Kubernetes - tips for your CKAD exam by CNCF***](https://en.sokube.ch/post/kubernetes-tips-for-your-ckad-exam-by-cncfX
