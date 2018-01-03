# javaproof
Java code to input a pdf attachment in an adobe form

    var annot = this.addAnnot({
        page: 0,
        type: “FileAttachment”,
        point: [500, 500]
        noView: true,
        author: “Attachment”
    });
    annot.cAttachmentPath;

    var attachmentObj = annot.attachment;
    if (attachmentObj !== null) {
        app.alert(“Add this file: “+attachmentObj.name);
        var 1 = this.getField(“1 st”);
        1. insertItemAt(attachmentObj.name, 0);
    }
    } catch (e)(
        if (e.name == “NotAllowedError”)(
            // do nothing
        }
    }
