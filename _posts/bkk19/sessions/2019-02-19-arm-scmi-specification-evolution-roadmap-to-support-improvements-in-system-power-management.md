---
categories:
- bkk19
description: <br /> Most SoC designs today implement a central entity that orchestrates
  System and Power Management controls. Such an entity may often be referred to as
  the System Control Processor (SCP), which is often a microcontroller. We use the
  term SCP to refer to the concept of such an entity throughout the rest of this abstract.
  The communication interface to the SCP is via transport channels.<br /> <br /> The
  ARM System Control & Management Interface (SCMI) specification v1.0 was designed
  to provide an industry standard transport independent interface to the SCP to enable
  system and power management. SCMI enables transport channels to ferry SCMI commands
  from an agent sitting on a Processing Entity (like an Application Processor) to
  the SCP. The SCP then decodes and implements the actions described by the SCMI commands.
  SCMIv1.0 is an already published specification supporting power, performance, clocks,
  sensors and system state management.<br /> <br /> Our presentation will talk about
  the vision of SCMI to enable a truly scalable Power Management software stack that
  can work across all compliant devices with minimal modification, with device specific
  controls resident in firmware. It will talk about evolution of the ARM SCMI Specification
  and how the next revision of the specification will enable next-generation system
  designs, especially touching a few key areas as outlined below.<br /> <br /> There
  is a growing requirement in certain segments of the industry to deploy virtualized
  systems, especially in the automotive domain. We will explain how SCMI can enable
  Power Management virtualization in such systems and design considerations thereof.
  We will also introduce the concept of Reset Domains and their Management via SCMI.
  Currently most Operating Systems manage Device Power, Clock and Performance via
  various frameworks in order to control a device. We envision a unified way of managing
  a device via a Device-centric model of Power Management. We will explain how SCMI
  can enable such a model and simplify current Power Management stacks.<br /> <br
  /> Our presentation will be of interest to people and organizations who are looking
  to enable scalable Power Management stacks for future devices where multiple Operating
  Systems may run concurrently in the same SoC, either physically on different Processing
  Entities, or via Virtualization.<br />
image:
  featured: 'true'
  path: /assets/images/featured-images/bkk19/BKK19-313.png
session_attendee_num: '15'
session_id: BKK19-313
session_room: Session Room 2 (Lotus 3-4)
session_slot:
  end_time: '2019-04-03 12:55:00'
  start_time: '2019-04-03 12:30:00'
session_speakers:
- speaker_bio: Souvik is a Staff Software Engineer in the Architecture and Technology
    Group at Arm, where his primary areas of focus are System and Power Management
    software standards and specifications. Souvik has ~13 years of experience in architecture
    and development of Power Management stacks on various OS and Firmware technologies.
    Prior to working at ARM, he was a technical lead at Intel where he was involved
    in Android Power &amp; Performance Management of various generations of Intel
    Atom platforms, and with STEricsson where he was involved with Symbian Power Management
    on the Nomadik series of SoCs.
  speaker_company: ARM
  speaker_image: /assets/images/speakers/bkk19/souvik-chakravarty.jpg
  speaker_location: ''
  speaker_name: Souvik Chakravarty
  speaker_position: Staff Software Engineer
  speaker_username: souvik.chakravarty
- speaker_bio: Kangkang Shen is a Chief Architect for System Firmware with Huawei.
    He is also the CCIX Firmware group chair and the firmware lead in the CCIX software
    work group. He is a steering committee member of the Linaro Data Center Group
    and leads the Heterogeneous Memory Sub Team in UEFI Forum.<br><br>Thanu Rangarajan
    is an OS Software and Firmware Technical Lead at Arm Limited. He co--chairs the
    CCIX Firmware group, and is a Firmware lead with the CCIX software work group.
    He is Arms key representative in the UEFI and ACPI forums.
  speaker_company: Arm Limited
  speaker_image: /assets/images/speakers/bkk19/thanunathan-rangarajan.jpg
  speaker_location: ''
  speaker_name: Thanunathan Rangarajan
  speaker_position: Principal Engineer
  speaker_username: thanu.rangarajan
session_track: Power Management
tag: session
tags:
- Automotive
- Android
- Power Management
- Linux Kernel
- IoT and Embedded
title: ARM SCMI Specification - Evolution & Roadmap to support improvements in System
  & Power Management
---