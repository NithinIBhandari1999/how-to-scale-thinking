# how-to-scale-thinking

## Question
Estimate the annual network bandwidth usage for a mobile messaging app.
User Base: Let’s assume the app aims to reach 100 million users.
Messages Sent: Estimate an average of 40 messages sent per user per day.
Average Message Size: Assume each message is approximately 2.5 KB in size (including metadata).

## Requirement
User = 100,000,000
Message send by a user / per day = 40
Message send by a user / per year = 40 * 365 = 14600
Storage per message = 2.5 kb

## Per user bandwidth usage
Bandwidth in KB = A User * Bandwidth send by a user / per year * Storage per message
Bandwidth in KB = 1 * 14600 * 2.5
Per User Bandwidth in KB Per Year = 36500 KB

## 100 million user
Bandwith in KB = per user bandwith per year * 100 million
Bandwith in KB = 36500 KB * 100 million
Bandwith in KB = 3650000000000

Bandwidth in MB = 3650000000000 KB / 1024
Bandwidth in MB = 3564453125 MB

Bandwidth in GB = 3564453125 MB / 1024
Bandwidth in GB = 3480911.2548828125 GB

Bandwidth in TB =  3480911.2548828125 GB / 1024
Bandwidth in TB = 3399.3273973464966 TB

Bandwidth in PB =  3399.3273973464966 TB / 1024
Bandwidth in PB = 3.319655661471188 PB
