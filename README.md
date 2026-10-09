# UFI003 IMS kernel experiment

This isolated branch builds the pinned public ImmortalWrt source and a complete matching kernel module set, adding XFRM and ESP capabilities required by the tested IMS path. It has no deployment steps and does not modify the main branch. Outputs are experimental kernel files only, not a whole-device firmware image. Device identities, SMS, captures, firmware partitions, private configuration, and recovery backups are excluded. A successful build alone does not establish working SMS.
