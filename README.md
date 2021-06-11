# Reporter


Example:
  
  
  #init
  
  from reporter import Reporter
  reporter=Reporter("logs","ocr_license_plate") # logs : folder:save , ocr_license_plate:name
  
  #write log
  
  reporter.log_metric("val_acc", float(epoch_val_acc), epoch)
