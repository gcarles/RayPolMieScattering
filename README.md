# RayPolMieScattering
Ray Tracing Polarisation-sensitive Mie Scattering

Enables Polarisation-sensitive Mie Scattering in Zemax-OpticStudio(TM), version v2 also adds the capability of modeling fluorescence as isotropic incoherent emission.

Citation: "in preparation"

INSTALLATION:
Extract and copy files 'MSP_v\<x>.dll' and 'MSP_v\<x>.def' into folder ‘\<installation directory>\DLL\BulkScatter’ where \<installation directory> is the Zemax install directory and \<x> is the DLL version.

USAGE:
Navigate to the "Volume physics" tab on a volume-object defined in a non-sequential Zemax model. Select "DLL Defined Scattering" and select 'MSP_v\<x>' from the drop-down list. The material used within Zemax must not have absorption (if Lamber-Beer absorption is to be accounted ‘Bulk absorption’ parameter of this DLL should be used instead).
