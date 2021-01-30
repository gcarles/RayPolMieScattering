# RayPolMieScattering

==============================================================================
Ray Tracing Polarisation-sensitive Mie Scattering for Zemax-OpticStudio(TM)
==============================================================================

Enables polarisation-sensitive Mie scattering in Zemax-OpticStudio(TM). Version v2 also adds the capability of modeling fluorescence as isotropic incoherent emission. Version v3 enables defining a smaller mean-path for fluorescence. Version v4 provides fluorescence- and non-fluorescence instances for simultaneous use. Version v4.2 solves issues (bug fixing) that appeared when rays experience large numbers of scattering events.

Citation: Carles, G., Zammit, P., and Harvey, A.R., "Holistic Monte-Carlo optical modelling of biological imaging," Sci Rep 9, 15832 (2019). https://doi.org/10.1038/s41598-019-51850-1


INSTALLATION:

Extract and copy files 'MSP_v<x>.dll' and 'MSP_v<x>.def' into folder ‘<installation directory>\DLL\BulkScatter’ where <installation directory> is the Zemax install directory and <x> is the DLL version.


USAGE:

Navigate to the "Volume physics" tab on a volume-object defined in a non-sequential Zemax model. Select "DLL Defined Scattering" and select 'MSP_v<x>' from the drop-down list. The material used within Zemax must not have absorption (if Lamber-Beer absorption is to be accounted ‘Bulk absorption’ parameter of this DLL should be used instead).
