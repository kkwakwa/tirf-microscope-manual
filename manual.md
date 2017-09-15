# Single molecule microscope manual

## Starting up the microscope


1.  Turn on the microscope components. Not necessarily in this order, but this isn't a bad one

    1. Toptica Laser box(to the right of the microscope frame)

       <img src="/images/toptica_key.jpg" alt="Toptica Switch" style="width: 400px;"/>

    1.  Microscope(on the shelf, behind the microscope)

        <img src="/images/Olympus_switch.jpg" alt="Olympus Power Switch" style="width: 400px;"/>

    1.  Mirror(to the right of the microscope control box)

        <img src="/images/mirror_switch.jpg" alt="Mirror Power Switch" style="width: 400px;"/>

    1.  Water Cooler(under the table to the left of the microscope)

        <img src="/images/water_cooler_switch.jpg" alt="Water Cooler Power Switch" style="width: 400px;"/>

    1.  Camera

        <img src="/images/camera_switch.jpg" alt="Orca Power Switch" style="width: 400px;"/>

    1.  PC(On the shelf above and to the left of the microscope)

        <img src="/images/pc_switch.jpg" alt="PC Power Switch" style="width: 400px;"/>

    1.  UV laser(Only if you are running an experiment that needs it, directly behind the laser box)

        <img src="/images/405_switch.jpg" alt="UV Laser Power Switch" style="width: 400px;"/>

1.  Turn on the control software on the PC

    1. ### Micro-Manager
    This controls the microscope frame, the camera and the laser box

        <img src="/images/mm_click.png" alt="Micro-Manager start" style="width: 200px;"/>

        <img src="/images/mm_configuration.png" alt="Micro-Manager start" style="width: 400px;"/>

        <img src="/images/mm_configuration_folder.png" alt="Micro-Manager start" style="width: 400px;"/>

        <img src="/images/mm_configuration_file.png" alt="Micro-Manager start" style="width: 400px;"/>

    1. ### Octopus(for the mirror)
        Octopus is currently the way we control the spinning mirror. If you don't need the mirror, there is no need to turn it on

        <img src="/images/Octopus_start.png" alt="Micro-Manager start" style="width: 200px;"/>

        Once you have started up Octopus, you will see the window below

        <img src="/images/Octopus_configuration.png" alt="Micro-Manager start" style="width: 400px;"/>

        Now select the

        <img src="/images/Octopus_config_file.png" alt="Micro-Manager start" style="width: 400px;"/>

        Once the config file loads, you can move off or minimize every window except for the one below, which will allow you to change the angle at which the laser comes out of the objective from epi-illumination to TIRF to HILO

        <img src="/images/Octopus_mirror.png" alt="Micro-Manager start" style="width: 400px;"/>

    1. ### PIMicroMove(for the stage)
       PIMicroMove is currently the way we control the PI stage, because it doesn't talk properly to Micro-manager 

        <img src="/images/pimicro_click.png" alt="Micro-Manager start" style="width: 300px;"/>

## Using the Microscope

* ### Illuminating your sample
* ### Snapping a single picture
* ### Taking an image stack
