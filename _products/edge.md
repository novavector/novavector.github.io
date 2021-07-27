---
layout: featured
title: Nova Edge Computing
description: Nova Edge is edge computing platform is based on EdgeX Foundry project.
---

<div class="row">
    <div class="col-xl-6 col-lg-12">
        <div class="service-details mb-40">
            <h3>Why Edge Computing</h3>
            <p>
                Unpredictable network disruptions, latency and bandwidth limitations can bring lot of issues to traditional enterprise computing paradigm built around centralized server architecture.
                <br><br>
                Nova Vector Platform provides integrated Edge Computing solution and management tools. 
                <br><br>
                We allow you to move some of the data processing out of the data center, to the factory floor. Once deployed, Nova Edge enables you to send only the results of that computing work at the edge, such as real-time business insights, equipment maintenance predictions or other actionable answers, back to the main data center for review and other human interactions.
            </p>
            <br><br>
            <h3>Nova Edge - Computing on the IoT Edge</h3>
            <p>
                Nova Edge is based on Linux Foundation IoT edge computing project - EdgeX Foundry.
                Once we verify that the EdgeX Foundry release is compatible with the Nova Vector Industry 4.0 platform and behaving as expected we fork it and add it to our Support and Professional Service plans.
                <br><br>
                Nova Edge can be deployed on the network edge, close to devices and sensors. The data can be processed and stored locally. Using the Application Services, you can filter and push only the vital information to the Nova Vector Platform. However, you are not locked into the Nova Vector Platform. You can push the data to any supported cloud provider like Amazon, Azure, Google or other enterprise applications.
            </p>
        </div>
    </div>
    <div class="col-xl-6 col-lg-12">
        <div class="s-details-img mb-30">
            <img src="{{site.baseurl}}/assets/img/products/edge/edge-thing.jpg" alt="{{page.title}}">
        </div>
    </div>
</div>

<div class="row">
    <div class="col-xl-6 col-lg-12">
        <div class="s-details-img mb-30">
            <img src="{{site.baseurl}}/assets/img/products/edge/edge-edgex.jpg" alt="{{page.title}}">
        </div>
    </div>
    <div class="col-xl-6 col-lg-12">
        <div class="service-details mb-40">
            <h3>EdgeX Foundry</h3>
            <p>
                EdgeX Foundry is a vendor-neutral open-source platform hosted by the Linux Foundation, providing a common framework for industrial IoT edge computing. 
                Support for containerization (e.g., docker) enables application portability and helps simplify application deployment and orchestration. EdgeX provides a standard open framework around which an ecosystem can emerge.
                <br><br>
                Janko Isidorovic, the founder of Nova Vector, was Chair of the Application Working Group in the Linux Foundation EdgeX Foundry from the project start until the release of EdgeX Foundry v1.0.
            </p>
        </div>
    </div>
</div>

<div class="row">    
    <div class="col-xl-6 col-lg-12">
        <div class="service-details mb-40">
            <h3>Modular, Microservice Architecture</h3>
            <p>Just like Nova Vector Platform, the Nova Edge is designed as a set of microservices. The Nova Edge microservices can be divided into several logical groups.
            <br>
            - Device Services provide connections to the devices and sensors. 
            <br>
            - Core Services are responsible for device management, sending commands to connected devices, and configuration of the edge server.
            <br>
            - Supporting Services consist of Rule Engine, Scheduling, and Alerts and Notification services.
            <br>
            - Application Services are on the northbridge and are in charge of pushing the data out of the edge server to the next component in the IoT landscape.
            </p>
        </div>
    </div>
    <div class="col-xl-6 col-lg-12">
        <div class="s-details-img mb-30">
            <img src="{{site.baseurl}}/assets/img/products/edge/edge-microservice-architecture.jpg" alt="{{page.title}}">
        </div>
    </div>
</div>

<div class="row">
    <div class="col-xl-6 col-lg-12">
        <div class="s-details-img mb-30">
            <img src="{{site.baseurl}}/assets/img/products/edge/platform-portainer.jpg" alt="{{page.title}}">
        </div>
    </div>
    <div class="col-xl-6 col-lg-12">
        <div class="service-details mb-40">
            <h3>Edge Server Management</h3>
            <p>
            Nova Vector Platform has container management component that can be used to manage edge servers. First you have to deploy management container on the edge server. The management container connects to Nova Vector platform and enables you to deploy docker containers or docker-compose scripts to the edge server.
            <br><br>
            Using our integrated FaaS component you can develop functions on the main server, package them as containers and then push them to the edge.
            </p>
        </div>
    </div>
</div>


<div class="row">
    <div class="col-xl-6 col-lg-12">
        <div class="service-details mb-40">
            <h3>Device and Asset Management on the Edge</h3>
            <p>
            Latency, bandwidth limitations, and network disruptions can be problem in some use cases. With Nova Edge you can connect your devices and sensors to the locally installed edge server and manage the assets on premise even if the network connection is compromised.
            <br><br>
            Nova Edge store and forward capability helps overcome network issues and reduce dependency on the internet connectivity.
            </p>
        </div>
    </div>
    <div class="col-xl-6 col-lg-12">
        <div class="s-details-img mb-30">
            <img src="{{site.baseurl}}/assets/img/products/edge/edge-edgex-device-services.jpg" alt="{{page.title}}">
        </div>
    </div>
</div>

<div class="row">
    <div class="col-xl-6 col-lg-12">
        <div class="s-details-img mb-30">
            <img src="{{site.baseurl}}/assets/img/products/edge/edge-edgex-app-services.jpg" alt="{{page.title}}">
        </div>
    </div>
    <div class="col-xl-6 col-lg-12">
        <div class="service-details mb-40">
            <h3>Realtime Data Processing on the Edge</h3>
            <p>
            Nova Edge enables data processing at the IoT edge. The device data streams can be forwarded to the built-in rules engine, where they can be transformed using SQL-like language.  The rules engine output can be pushed to the Rest HTTP server, MQTT broker, EdgeX message bus, or log file.
            Besides the rules engine, the system has Application Services that provide several standard functions for data transformation:
            <br>- Compression
            <br>- Conversion
            <br>- Encryption
            <br>- Filtering
            <br>- Export
            </p>
        </div>
    </div>
</div>

<div class="service-details mb-30">
    <h3>Supported Protocols on the Edge</h3>
    <p>Nova Edge currently supports the following Edge protocols:
        <br>- HTTP/REST
        <br>- OPC-UA
        <br>- MODBUS
        <br>- BACNET
        <br>- Zigbee
        <br>- BLE
        <br>- MQTT
        <br>- SNMP
        <br><br>
        *Additional edge and server-side protocols can be added at clients request. Please contact our <a href="{{site.baseurl}}/services/professional_services">Professional Services</a> for more information.
</p>
</div>
