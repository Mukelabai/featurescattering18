# Feature Scattering in the Large

#Scattering database
Our longitudinal study is based on a feature-oriented analysis of the Linux kernel git repository. Using a custom made tool (see infrastructure), we convert the kernel git repository into a relational database, which we make available for download (scatdb_dump.zip).

#Sample classification and criteria

    Classification of a sample of scattered driver features (scat_grps.ods)
    Classification of all outlier features (outliers.ods) 

The classification procedure of features as infrastructure or platform is documented here (criteria.tar.gz).

All the documents made available in this section are compatible with Open Office: odt (for text documents) and ods (for spreadsheet documents).

#Infrastructure

To create and analyze features in the Linux kernel, we rely on the following tools:

    scat_linux (scat_linux_db.zip): a tool that, given a snapshot of a Linux kernel repository, generates a database with scattering information of Kconfig features (configuration options).
    kconfig_info (kconfig_info.zip): a tool to recover information relative to a single feature.
    A set of helper scripts in R and Bash, which can be downloaded from here (scripts.tar.gz). 

Contact

In case of any problem, please contact one of the following:

    Leonardo Passos (lpassos at gsd dot uwaterloo dot ca)
    Rodrigo Queiroz (rqueiroz at gsd dot uwaterloo dot ca)
	Mukelabai Mukelabai (mukelabai dot mukelabai at gu dot se)