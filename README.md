# LeeInSu
import Class from "lib/impactES6/Class";

ig.require('impact.entity');  // ig.require is used only for require an impact library

export default class EntityPlayer extends Class.inheritance(ig.Entity) {
  init (x, y, settings)
  {
    super.init(x, y, settings);
   
    this.ready = true;
  }
}
