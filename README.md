Building the software layer between physical machines and the cloud.

I work on electric mobility platforms — chargers, vehicles, telemetry — and the backends that turn raw device traffic into something a product can actually use. Embedded side and cloud side, because the interesting bugs live between them.

### Four things a connected product needs

🔌 **Measure** — real sensors drift, real clocks skew, real chargers lie. Calibration and sanity checks before anything reaches a database.
`IoT` `embedded` `Raspberry Pi` `Arduino`

📡 **Connect** — protocols that survive bad networks and cheap hardware. Reconnection, backpressure, idempotency.
`OCPP` `MQTT` `serial` `retry semantics`

⚙️ **Serve** — typed APIs and infrastructure you can rebuild from scratch.
`Python` `FastAPI` `AWS` `Terraform`

🔍 **Operate** — know what the fleet is doing without SSHing into it.
`telemetry` `logs` `simulation` `deterministic tests`

### Projects

**[Gitpulpu](https://github.com/LaNeigeLuge/Gitpulpu)** — a FOSS multiplatform Git client for people who find Git hostile. *Kotlin Multiplatform → one client, every desktop.*

**[vigia](https://github.com/LaNeigeLuge/vigia)** — mood and productivity tracker. *Track what actually moved, not what you remember.*

**[Mortician-Journey](https://github.com/LaNeigeLuge/Mortician-Journey)** — medieval looting and mini-games, built in Godot. *Prototype first, systems after.*

**[PFC — Personal Food Computer](https://github.com/LaNeigeLuge/PFC-Personal-Food-Computer)** — a controlled greenhouse wired to an IoT hub. 5th-year engineering project, ESME Sudria. *Sensors → control loop → crops.*

**[Aquarium Monitoring System](https://github.com/LaNeigeLuge/Aquarium-Monitoring-System)** — the same idea, smaller tank, Java.

---

Python · AWS · Terraform · FastAPI · a soldering iron within reach.
