# Heart Rate Recovery (HRR) Calculator
A browser-based tool that measures how quickly your heart rate drops after exercise — one of the simplest and most reliable indicators of cardiovascular fitness you can track at home.
No sign-ups. No installs. No data collection. Just open the file and test.

<img width="779" height="797" alt="image" src="https://github.com/user-attachments/assets/7cd8528f-3673-4203-a0b6-131dea1529ec" />


# What Is Heart Rate Recovery?
Heart Rate Recovery (HRR) is the difference between your heart rate at peak exercise and your heart rate exactly one minute later. It reflects how efficiently your autonomic nervous system — specifically vagal tone — can bring your body back to rest after exertion.
Research published in the New England Journal of Medicine found that an HRR of less than 12 BPM after one minute is an independent predictor of increased mortality risk, regardless of age or fitness level. On the other end, athletes and highly conditioned individuals typically see drops of 40–60+ BPM.
In short: the faster your heart rate falls, the healthier your heart likely is.

# Who Is This For?

Everyday fitness enthusiasts who want a quick, no-equipment cardiac health check at home
Runners, cyclists, and endurance athletes looking to track autonomic recovery over weeks and months of training
Personal trainers and coaches who need a simple tool to baseline client cardiovascular fitness
People beginning a fitness journey who want a measurable starting point and a way to see progress
Health-conscious individuals curious about their heart's efficiency without visiting a clinic
Students and educators studying exercise physiology or cardiac health

# Who Should NOT Use This
This tool is not a medical device. Do not use it as a substitute for professional cardiac evaluation. Avoid performing the exercise test if you:

Have a diagnosed heart condition, arrhythmia, or are on cardiac medication
Experience chest pain, shortness of breath, or dizziness during exertion
Have been advised by a doctor to avoid vigorous physical activity
Are recovering from surgery, illness, or injury

If your result falls in the "Poor" category (HRR below 12 BPM), consult a healthcare professional before continuing any vigorous exercise program.

# How to Use the Tool

Step 1 — Open the File
Open heart_rate_recovery.html in any modern browser (Chrome, Firefox, Safari, Edge). Everything runs locally in your browser. Nothing is sent to any server.
Step 2 — Read the Test Protocol
Click the "How To Test" tab. It walks you through six steps:

Warm up for 2 minutes with light movement
Exercise vigorously for 3–5 minutes (jogging, jumping jacks, stair climbing, burpees — anything that gets your heart rate near its maximum)
Measure your Peak Heart Rate immediately after stopping — count your pulse for 15 seconds and multiply by 4, or use a fitness watch
Rest for exactly 1 minute — stand still or sit (pick one posture and stay consistent across tests)
Measure your Recovery Heart Rate after the minute is up
Enter both values in the Calculator tab

Step 3 — Use the Built-In Timer
Switch to the "Timer" tab. Press Start the instant you stop exercising. The countdown runs for 60 seconds with a visual progress bar, an amber warning at 10 seconds remaining, and a vibration alert on mobile when the minute is complete.
Step 4 — Calculate Your HRR
Switch to the "Calculator" tab and enter:
FieldDescriptionPeak Heart RateYour BPM immediately after exerciseRecovery Heart RateYour BPM after 1 minute of restAge (optional)Used for contextual percentage calculationsRecovery Posture (optional)Whether you stood or sat during the rest period
Press Calculate HRR. The tool displays:

Your HRR value (Peak HR minus Recovery HR)
An animated gauge visualization
A color-coded fitness rating with a detailed explanation
Percentage of heart rate recovered
All three key metrics at a glance


# Understanding Your Results

HRR (BPM drop in 1 min)RatingWhat It Means< 12PoorReduced cardiovascular health — medical consultation recommended12 – 20Below AverageRoom for significant improvement through regular aerobic exercise21 – 30AverageNormal range — consistent training will push this higher31 – 40GoodAbove average cardiovascular fitness41 – 50ExcellentStrong vagal tone and rapid autonomic recovery> 50Athlete-LevelOutstanding — typical of endurance-trained athletes

# Tips for Accurate Results

Be consistent. Always use the same exercise type, duration, intensity, and recovery posture when comparing results over time.
Don't control your breathing during the rest period. Breathe naturally.
Measure at the same time of day. Heart rate variability shifts with circadian rhythm, caffeine, sleep quality, and stress.
Track over time. A single reading is a snapshot. Testing weekly or biweekly over several months reveals the real trend of your cardiac fitness.
Hydrate beforehand. Dehydration elevates resting heart rate and can skew results.


# Technical Details

Pure HTML + CSS + JS — no frameworks, no dependencies, no build step
Fully offline — works without an internet connection after the first load (fonts are the only external resource)
Mobile-friendly — responsive layout tested on phones and tablets
Zero data storage — nothing is saved, logged, or transmitted
~15 KB single file


# Running Locally
bash# Simply open the file in a browser
open heart_rate_recovery.html

# Or serve it locally
python3 -m http.server 8000
# then visit http://localhost:8000/heart_rate_recovery.html

# Disclaimer
This tool is for informational and educational purposes only. It is not a certified medical device and does not provide medical advice, diagnosis, or treatment. The HRR reference ranges are based on published exercise physiology research but are general guidelines, not clinical thresholds. Always consult a qualified healthcare provider for any concerns about your cardiovascular health.
