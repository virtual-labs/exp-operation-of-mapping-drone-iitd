### Marking Ground Control Points (GCPs) and Recording Coordinates

#### Step 1: Setting Up the Base Station
- Identify the survey location on the map.  
- Place the **stake** into the ground to mark the measurement point.  
- Use **spray paint** to highlight the area around the stake.  
- Place the **base tripod** over the stake.  
- Mount the **tribrach** on the tripod.  
- Align the instrument using the **optical plummet**.  
- Place the **GNSS Base Receiver** on the tribrach.  
- Power on the receiver and wait for initialization.  


#### Step 2: Connecting Mobile to GNSS Base Receiver
- Turn on Wi-Fi on the mobile phone.  
- Connect to the network **"reach:37:2F"**.  
- Open the **Emlid Flow** app.  
- Rename device to **"reach-base"**.  
- Set update rate to **5 Hz** under GNSS settings.  
- Configure **RTCM3 messages** under Base Mode.  
- Enable **LoRa** in Correction Output.  
- Close the phone screen after setup.  

#### Step 3: Setting Up the Rover (GCP 1)
- Place the **GCP marker** at the first location.  
- Position the **rover tripod** over it.  
- Mount the **GNSS Rover Receiver**.  
- Power it on and wait for initialization.  


#### Step 4: Recording Coordinates of GCP 1
- Connect mobile to rover Wi-Fi.  
- Open **Emlid Flow** and configure GNSS settings.  
- Enable **LoRa** in Correction Input.  
- Check correction status under **Status**.  
- Go to **Survey → Add** and label as **"GCP"**.  
- Enable **Fix Only** mode.  
- Click **Measure** and wait for completion.  
- Save and close after recording coordinates.  
- Fold the tripod and store it.  


#### Step 5: Recording Coordinates of GCP 2, 3, and 4
- Move to the next GCP location.  
- Place the marker and set up the rover.  
- Open **Survey → Add → Measure**.  
- Wait for completion and save data.  
- Store equipment after each measurement.  
- Repeat for all remaining GCPs.  

---

### Preparing the Drone for Survey

#### Steps
- Move to the drone take-off location.  
- Open the drone box and remove components.  
- Attach all **four propellers**.  
- Insert the **battery**.  
- Power on the drone and confirm readiness.  
---


### Conducting the Survey - Ready to Fly

#### Steps
- Select a safe, flat take-off area.  
- Place **four safety cones** around the area.  
- Position the drone at the center.  
- Power on the **remote controller**.  
- Open **Plan → 2D Photogrammetry**.  
- Define the survey boundary on the map.  
- Save the plan as **"DRONE JOB"**.  
- Click **Invoke → Start**.  
- Slide to **Execute** to launch the drone.  
- The drone captures images automatically.  
- After completion, it performs **Return to Home (RTH)** and lands.  

---

### Post-Survey Data Collection, Analysis, and Reporting

#### Steps
- Power off the drone.  
- Remove the **memory card**.  
- Insert it into the **laptop**.  
- Open **Pix4Dmatic** software.  
- Import images from the **Golf Part folder**.  
- Load **gcps.csv** under Tie Points.  
- Set coordinate reference systems and apply.  
- Open processing settings and enable:
  - Dense Point Cloud  
  - Image Pre-processing  
  - Mesh  
  - DSM  
  - Orthomosaic  
- Start processing and wait for completion.  
- View results in **3D mode**.  
- Import and save the **Quality Report**.  
- Download the report (PDF) for submission.