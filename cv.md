# Nikita Olchowski

## Contact Information
- **Email:** nikita.olchowski@gmail.com
- **Phone:** 576 046 593
- **LinkedIn:** [linkedin.com/in/olchowski-nikita](https://www.linkedin.com/in/olchowski-nikita/)

## Professional Experience
### Test Engineer
**ALTEN Polska _(Project for APTIV)_**  
_September 2023 - Present_
- BCM (body control module) for Jeep, Fiat. Automatic tests.
- Functional Safety Tests
- CI/CT systems integration

**ALTEN Polska _(Project for ZF)_**  
_July 2022 - September 2023_
- Testing Advanced Driver assistance systems (KAFAS) for BMW, Rolls-Royce
- Functional Safety Tests

### Junior Test Engineer
**Kawasaki Robotics Central and Eastern Europe HUB**  

_January 2020 - July 2022_
- Testing Kawasaki DuAro robot (Colaborative robot)
- Development and simulation of robotic workstations using K-Roset software

## Code Example:
### There is example from leetcode

#### Problem
You are given two non-empty linked lists representing two non-negative integers. The digits are stored in reverse order, and each of their nodes contains a single digit. Add the two numbers and return the sum as a linked list.
You may assume the two numbers do not contain any leading zero, except the number 0 itself.
#### Solutuion:
***

    def addTwoNumbers(self, l1: Optional[ListNode], l2: Optional[ListNode]) -> Optional[ListNode]:
        dummyHead = ListNode(0)
        tail = dummyHead
        carry = 0

        while l1 is not None or l2 is not None or carry != 0:
            digit1 = l1.val if l1 is not None else 0
            digit2 = l2.val if l2 is not None else 0

            sum = digit1 + digit2 + carry
            digit = sum % 10
            carry = sum // 10

            newNode = ListNode(digit)
            tail.next = newNode
            tail = tail.next

            l1 = l1.next if l1 is not None else None
            l2 = l2.next if l2 is not None else None

        result = dummyHead.next
        dummyHead.next = None
        return result

## Education

### Master
**Cracow University of Technology**  
_2021 - 2022_  
**Field of Study:** Infotroniks

### Engineer
**Cracow University of Technology**  
_2017 - 2021_  
**Field of Study:** Power Engineering / Electrical machines and devices


## Technical Skills

- Python
- Django framework
- Test Management Platforms (JIRA, DOORS, Polarion)
- Automated Testing (Selenium, CANoe)
- API Testing
- CI/CD (Jenkins,Wind River)
- Prototyping and modeling in Autodesk Inventor, Fusion 360

## Languages
- **Polish:** C2
- **Russian:** C2
- **English:** C1

## Certificates
- Laureate of the Academy of Young Project Manager (2020)
- Nokia Academy certificate: 2-month long in-house testing-oriented training (I&V Engineer) (2022)

