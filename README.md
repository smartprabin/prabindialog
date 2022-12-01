# prabindialog


        //Simple example
        BeautifulDialog.build(this)
            .title("Title success", titleColor = R.color.black)
            .description("Description success", color = R.color.black)
            .type(type = BeautifulDialog.TYPE.SUCCESS)
            .position(BeautifulDialog.POSITIONS.CENTER)
            .onPositive("Confirm") {
                Toast.makeText(this, "confirm", Toast.LENGTH_SHORT).show()
            }
            .onNegative("Cancel") {
                Toast.makeText(this, "cancel", Toast.LENGTH_SHORT).show()
            }
            .hideNegativeButton(hide = false)
            .setCancelable(true)
    }
