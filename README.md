# 📧 Email Filtering System Using Set Theory

## 👥 Group Members
- Member 1: Wafi Wahid, 47322
- Member 2: Jaweriya Khan, 46549
- Member 3: Maria Kiran, 44565
- Member 4: Sana Arshad, 46189
- Member 5: Tehmina, 2396


---

## 🎯 Objective
To understand the application of **Set Theory in Software Engineering** through a real-world problem—**email filtering**—by using basic set operations such as union, intersection, difference, complement, and symmetric difference.

---

## 🧩 Problem Description 
In an email system, users receive different types of emails—spam, important, read, unread, or duplicate. Efficiently organizing these emails is crucial for user experience. This mini-project filters out spam, finds unread or important emails, and removes duplicates using **Set Theory**.

---

## 📚 Defined Sets
We define the following sets:
- `All_Emails` – All received emails.
- `Spam_Emails` – Emails identified as spam.
- `Important_Emails` – Marked as high-priority.
- `Read_Emails` – Emails already read.
- `Duplicate_Emails` – Repeated emails (simulated).

---

## 🧮 Set Operations 

| Operation              | Python Code                                       | Real-world Meaning                     |
|------------------------|--------------------------------------------------|----------------------------------------|
| Union (A ∪ B)          | `important_emails.union(spam_emails)`            | All flagged emails                     |
| Intersection (A ∩ B)   | `important_emails.intersection(read_emails)`     | Read & important emails                |
| Difference (A − B)     | `all_emails.difference(spam_emails)`             | Clean inbox (no spam)                  |
| Complement (~A)        | `all_emails.difference(read_emails)`             | Unread emails                          |
| Symmetric Diff (A △ B) | `important_emails.symmetric_difference(spam_emails)` | Emails needing special attention    |

---

## 💻 Code Implementation 

###  1. Clone Git repo

```bash
git clone https://github.com/Wafi-wahid/EmailFiltering-FM-SetTheory-Python.git
```

### 2. Run File in your editor

## 📝 Conclusion
This mini-project showed how easily Set Theory can be applied in real-world software problems. Using Python’s set operations, we filtered spam, highlighted unread emails, and prioritized messages. Clean, efficient, and no chaos—just like a good inbox.


