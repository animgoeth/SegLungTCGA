# SegLungTCGA

SegLungTCGA is a dataset of segmented H&E tissue slides from TCGA lung cancer (lung adenocarcinoma) patients. Each slide is segmented into 87x87 μm colored patches. File names correspond to old TCGA file ids (before 10-2021). To make it possible to match them to the current file ids, a mapping file is provided - it contains TCGA patient id (*patient_id* column), SegLung file id (*seglung_file_id* column) and current TCGA file id (*tcga_file_id* column).

To view original whole slide images, use the following link: `https://portal.gdc.cancer.gov/files/<TCGA_FILE_ID>`, where `<TCGA_FILE_ID>` should be replaced by the value from the *tcga_file_id* column corresponding to your desired *seglung_file_id*.

Legend:
* orange - tumor
* green - stroma
* yellow - mixed
* purple - vessel
* grey - necrosis
* navy - lung
* light blue - immune
* light pink - bronchi
* dark grey - background
