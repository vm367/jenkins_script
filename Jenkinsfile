node() {
  def std_out = new StringBuilder()
  def std_err = new StringBuilder()
  def proc = "sudo ls".execute()
  proc.consumeProcessOutput(std_out, std_err)
  println std_out
}
