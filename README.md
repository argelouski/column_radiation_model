# CCM3 Column Radiation Model (CRM) description:

The CRM is a standalone version of the column radiation code employed
by the NCAR Community Climate Model (CCM3).  Thus the CRM is a
physical process model which isolates the energetics of radiative
transfer from the rest of the CCM3.  The CRM is built from the
radiation routines from CCM3, along with a simple text interface for
the user to input information needed by the radiation calculation.

# Installation:

## For NERSC-CORI:
```
module load cray-netcdf cray-hdf5
```
### Then, from the bld folder run:
```
 make MPI=Y NETCDF_ROOT=${NETCDF_DIR}
```

# Version:

The versions of the CRM and CCM code in this distribution are contained
in the file VERSION. Please include this version number in any
correspondence with the authors. 

# Where to find more information:

The CRM homepage is at URL http://www.cgd.ucar.edu/cms/crm.  This page
always contains the latest information on the CRM.  The CRM FAQ is
also available from this site, and should be consulted before
contacting the authors.  Significant changes to the CRM are announced
to the community via the ccm-users email list, see
http://www.cgd.ucar.edu/cms/ccm3/ccm-users.html for instructions on
how to join this list.

The physics routines underlying the CRM are fully described in NCAR
Tech. Note 420, "Description of the NCAR Community Climate Model
(CCM3)" which is available in postscript format from
http://www.cgd.ucar.edu/cms/ccm3/TN-420/index.html.

# Contact information:

Charlie Zender and Bruce Briegleb
Climate Modeling Section
Climate and Global Dynamics Division
National Center for Atmospheric Research
P.O. Box 3000
Boulder, Colorado  80307-3000
USA

E-mail: zender@ncar.ucar.edu and bruceb@ncar.ucar.edu 



