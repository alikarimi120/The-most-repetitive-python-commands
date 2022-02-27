# Create Directory

def CreateDir(path):
  if not os.path.exists(path):
      os.makedirs(path)